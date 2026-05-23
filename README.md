<div align="center">

# Aditya Chilka

### Developer tools for the AI agent ecosystem.

Open-source author · MCP / agent infrastructure · TypeScript, Python, Rust

<br />

[![X](https://img.shields.io/badge/follow-@adityachilka-000?style=flat-square&logo=x)](https://x.com/adityachilka)
[![Email](https://img.shields.io/badge/aditya@rapidcircuitry.com-000?style=flat-square&logo=gmail&logoColor=white)](mailto:aditya@rapidcircuitry.com)
[![Sponsor](https://img.shields.io/badge/sponsor-pink?style=flat-square&logo=githubsponsors)](https://github.com/sponsors/adityachilka1)
[![Profile views](https://komarev.com/ghpvc/?username=adityachilka1&style=flat-square&color=BB9AF7&label=profile+views)](https://github.com/adityachilka1)

</div>

---

## Now shipping

I build the missing tools for engineers working on agents and the Model Context Protocol — the layer Anthropic, OpenAI, and the open-source agent community are converging on. Three repos take most of my time:

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>
        <a href="https://github.com/adityachilka1/mcp-devtools">mcp&#8209;devtools</a>
        &nbsp;
        <a href="https://www.npmjs.com/package/@adityachilka/mcp-devtools"><img alt="npm" src="https://img.shields.io/npm/v/@adityachilka/mcp-devtools?style=flat-square&color=BB9AF7&label=npm" /></a>
      </h3>
      <p>Chrome DevTools for the Model Context Protocol. Transparent proxy that inspects, profiles, replays, and diffs every MCP frame your agent makes. Per-call USD cost attribution, HTTP&nbsp;+&nbsp;SSE upstream, embed API, doctor diagnostics, cross-platform single binaries.</p>
      <p><sub><strong>Status:</strong> shipped — v0.1 on npm, six-piece CLI surface, 8-platform CI.</sub></p>
    </td>
    <td valign="top" width="50%">
      <h3>
        <a href="https://github.com/adityachilka1/skillforge">skillforge</a>
        &nbsp;
        <a href="https://www.npmjs.com/package/@adityachilka/skillforge"><img alt="npm" src="https://img.shields.io/npm/v/@adityachilka/skillforge?style=flat-square&color=BB9AF7&label=npm" /></a>
      </h3>
      <p>CLI for authoring Claude Skills. Six-piece workflow: <code>init → validate → lint → update → pack → install</code>. Produces <code>.skill</code> bundles that drop straight into Claude / Cowork's install flow. HTTPS-only installer with zip-slip&nbsp;/&nbsp;symlink&nbsp;/&nbsp;size guards.</p>
      <p><sub><strong>Status:</strong> v0.0.2 — author-side complete; remote registry next.</sub></p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>
        <a href="https://github.com/adityachilka1/agentbench">agentbench</a>
        &nbsp;
        <img alt="status" src="https://img.shields.io/badge/v0.0.1-7DCFFF?style=flat-square&label=status" />
      </h3>
      <p>Snapshot tests for AI agent traces. Framework-agnostic — works with CrewAI, LangGraph, Mastra, OpenAI Agents SDK. Four-piece CLI: <code>init</code>, <code>list</code>, <code>validate</code>, <code>compare</code>.</p>
      <p><sub><strong>Status:</strong> v0.1 in active iteration. Discriminated-union schema, deterministic diff.</sub></p>
    </td>
    <td valign="top" width="50%">
      <h3>
        <a href="https://github.com/adityachilka1/mcp-devtools-examples">mcp&#8209;devtools&#8209;examples</a>
      </h3>
      <p>Runnable examples for <code>mcp-devtools</code>: proxy, record + replay, HTTP transport + cost attribution, diff-driven regression catch. Each example is self-contained and live-verified.</p>
      <p><sub><strong>Status:</strong> 5 examples published. New examples land alongside features.</sub></p>
    </td>
  </tr>
</table>

## This month — May 2026

50+ merged PRs across own projects and upstream OSS in the last 30 days. Recent upstream contributions:

[`BerriAI/litellm`](https://github.com/BerriAI/litellm) · [`knurling-rs/defmt`](https://github.com/knurling-rs/defmt) · [`modelcontextprotocol/conformance`](https://github.com/modelcontextprotocol/conformance) · [`modelcontextprotocol/typescript-sdk`](https://github.com/modelcontextprotocol/typescript-sdk) · [`modelcontextprotocol/inspector`](https://github.com/modelcontextprotocol/inspector) · [`modelcontextprotocol/servers`](https://github.com/modelcontextprotocol/servers) · [`RIOT-OS/RIOT`](https://github.com/RIOT-OS/RIOT) · [`ThrowTheSwitch/Unity`](https://github.com/ThrowTheSwitch/Unity) · [`modm-io/modm`](https://github.com/modm-io/modm) · [`lvgl/lvgl`](https://github.com/lvgl/lvgl) · [`adafruit/Adafruit_SSD1306`](https://github.com/adafruit/Adafruit_SSD1306) · [`platformio/platformio-core`](https://github.com/platformio/platformio-core) · [`nanopb/nanopb`](https://github.com/nanopb/nanopb)

## A few principles

I write these down so the code knows where it came from.

1. **Local-first beats cloud-first** until proven otherwise. Most developer tools never needed the cloud.
2. **Drop-in beats opinionated.** If a user has to refactor to try the library, they won't try the library.
3. **Ship the smallest thing that's useful**, then iterate weekly in public. Boring beats brittle.
4. **Read the protocol spec, not the framework docs.** Frameworks come and go; protocols outlast them.

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-1a1b27?style=flat-square&logo=typescript&logoColor=7DCFFF)
![Node.js](https://img.shields.io/badge/Node.js-1a1b27?style=flat-square&logo=node.js&logoColor=BB9AF7)
![Python](https://img.shields.io/badge/Python-1a1b27?style=flat-square&logo=python&logoColor=7DCFFF)
![Rust](https://img.shields.io/badge/Rust-1a1b27?style=flat-square&logo=rust&logoColor=BB9AF7)
![Go](https://img.shields.io/badge/Go-1a1b27?style=flat-square&logo=go&logoColor=7DCFFF)
![React](https://img.shields.io/badge/React-1a1b27?style=flat-square&logo=react&logoColor=7DCFFF)
![Next.js](https://img.shields.io/badge/Next.js-1a1b27?style=flat-square&logo=nextdotjs&logoColor=BB9AF7)
![PostgreSQL](https://img.shields.io/badge/Postgres-1a1b27?style=flat-square&logo=postgresql&logoColor=7DCFFF)
![Vitest](https://img.shields.io/badge/Vitest-1a1b27?style=flat-square&logo=vitest&logoColor=BB9AF7)
![Biome](https://img.shields.io/badge/Biome-1a1b27?style=flat-square&logo=biome&logoColor=7DCFFF)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-1a1b27?style=flat-square&logo=opentelemetry&logoColor=BB9AF7)
![MCP SDK](https://img.shields.io/badge/MCP%20SDK-1a1b27?style=flat-square&logoColor=7DCFFF)

## Stats

<table>
  <tr>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=adityachilka1&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true">
        <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=adityachilka1&show_icons=true&hide_border=true&theme=default&include_all_commits=true&count_private=true">
        <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=adityachilka1&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true">
      </picture>
    </td>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=adityachilka1&layout=compact&hide_border=true&theme=tokyonight&langs_count=8">
        <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=adityachilka1&layout=compact&hide_border=true&theme=default&langs_count=8">
        <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adityachilka1&layout=compact&hide_border=true&theme=tokyonight&langs_count=8">
      </picture>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com?user=adityachilka1&hide_border=true&theme=tokyonight">
        <source media="(prefers-color-scheme: light)" srcset="https://github-readme-streak-stats.herokuapp.com?user=adityachilka1&hide_border=true&theme=default">
        <img alt="GitHub streak" src="https://github-readme-streak-stats.herokuapp.com?user=adityachilka1&hide_border=true&theme=tokyonight">
      </picture>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=adityachilka1&theme=tokyo-night&hide_border=true&area=true&custom_title=Contributions+over+time">
        <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=adityachilka1&theme=minimal&hide_border=true&area=true&custom_title=Contributions+over+time">
        <img alt="Contribution graph" src="https://github-readme-activity-graph.vercel.app/graph?username=adityachilka1&theme=tokyo-night&hide_border=true&area=true&custom_title=Contributions+over+time">
      </picture>
    </td>
  </tr>
</table>

<details>
  <summary><strong>Star history of pinned projects</strong></summary>
  <br />
  <a href="https://star-history.com/#adityachilka1/mcp-devtools&adityachilka1/skillforge&adityachilka1/agentbench&Date">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=adityachilka1/mcp-devtools,adityachilka1/skillforge,adityachilka1/agentbench&type=Date&theme=dark">
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=adityachilka1/mcp-devtools,adityachilka1/skillforge,adityachilka1/agentbench&type=Date">
      <img alt="Star history" src="https://api.star-history.com/svg?repos=adityachilka1/mcp-devtools,adityachilka1/skillforge,adityachilka1/agentbench&type=Date">
    </picture>
  </a>
</details>

## Want to contribute?

The fastest way in: open any pinned repo, find a `good-first-issue`, and send a PR. I respond within 24 hours and ship on a weekly cadence. If you're working on agent infrastructure and want to compare notes, my inbox is open.

<div align="center">
  <br />
  <sub>Made with care in Bengaluru.</sub>
</div>
