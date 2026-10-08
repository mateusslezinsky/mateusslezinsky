<div align="center">
  <h1>Mateus Slezinsky Pereira</h1>

  <a href="https://github.com/mateusslezinsky">
    <img
      src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&amp;size=19&amp;duration=3200&amp;pause=1200&amp;color=58A6FF&amp;center=true&amp;vCenter=true&amp;width=600&amp;height=40&amp;lines=Software+Engineer;Open+Source+Contributor;Building+Developer+Tools"
      alt="Software Engineer · Open Source Contributor · Building Developer Tools"
    />
  </a>

  <p>
    <a href="https://www.linkedin.com/in/mateus-slezinsky/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn" /></a>
    <a href="https://github.com/mateusslezinsky?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-24292F?style=flat-square&amp;logo=github&amp;logoColor=white" alt="GitHub repositories" /></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&amp;logo=typescript&amp;logoColor=white" alt="TypeScript" />
    <img src="https://img.shields.io/badge/React-20232A?style=flat-square&amp;logo=react&amp;logoColor=61DAFB" alt="React" />
    <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&amp;logo=nodedotjs&amp;logoColor=white" alt="Node.js" />
    <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&amp;logo=react&amp;logoColor=61DAFB" alt="React Native" />
  </p>
</div>

---

### About

I'm a software engineer based in Brazil, working remotely with a US team at [Pivot](https://pivot.app). I build web, mobile, and backend features, mostly with TypeScript, React, React Native, and Node.js.

My work has included notification services with 10+ gRPC flows, shared UI components across web and mobile, real-time features, and Playwright end-to-end testing. Outside of work, I contribute to open source and experiment with developer tooling.

### Open-source contributions

I've recently had changes merged into **OneUptime** and **PowerSync**. A few examples:

**[OneUptime](https://github.com/OneUptime/oneuptime)** — monitoring and incident management

- [Workflow scheduling](https://github.com/OneUptime/oneuptime/pull/4458): cleaned up stale BullMQ repeatable jobs after trigger changes or deletion, including reconnect and race-condition cases.
- [Monitor secret access](https://github.com/OneUptime/oneuptime/pull/4210): added project-wide and label-based grants with tests for isolation and batching.
- [Episode membership](https://github.com/OneUptime/oneuptime/pull/4423): fixed stale incident/alert references and added PostgreSQL regression tests.

<details>
  <summary><strong>See the workflow scheduling bug before and after the fix</strong></summary>
  <p><em>Before: the workflow was switched to Manual, but scheduled runs continued.</em></p>
  <p><img src="https://github.com/user-attachments/assets/4d8212b6-ad60-4ff1-9d4d-e98ab459b773" width="760" alt="OneUptime workflow kept running after its schedule was removed" /></p>
  <p><em>After: no new runs were created at the former schedule boundaries.</em></p>
  <p><img src="https://github.com/user-attachments/assets/826355e9-4906-4ace-ba84-87a6db131b3b" width="760" alt="OneUptime stopped producing scheduled runs after the fix" /></p>
  <p><a href="https://github.com/OneUptime/oneuptime/pull/4458">Read the PR and integration-test details.</a></p>
</details>

**[PowerSync](https://github.com/powersync-ja/powersync-js)** — JavaScript sync SDKs

- [Worker error handling](https://github.com/powersync-ja/powersync-js/pull/1136): preserved diagnostic details when errors crossed worker boundaries.
- [TypeScript credentials](https://github.com/powersync-ja/powersync-js/pull/1134): fixed compatibility with `exactOptionalPropertyTypes`.

### Public projects

<table>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/mateusslezinsky/react-native-virtualized-select">React Native Virtualized Select</a></strong>
      <p>A configurable virtualized select component for large React Native lists, with search and theming options.</p>
      <sub>TypeScript · React Native</sub>
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/mateusslezinsky/model-generator">Model Generator</a></strong>
      <p>A C# utility for generating TypeScript interfaces and types from backend models.</p>
      <sub>C# · TypeScript · Code generation</sub>
    </td>
  </tr>
</table>

I'm also working on coding-agent orchestration and PR verification tooling. Those repositories aren't public yet, so the linked work above is the best place to review my code today.

---

<p align="center">
  <a href="https://www.linkedin.com/in/mateus-slezinsky/">LinkedIn</a> · <a href="https://github.com/mateusslezinsky?tab=repositories">Repositories</a>
</p>
