<!-- 🚧 DRAFT — v2:项目前置、去 PR 强调、删在审区。发布步骤见 PUBLISH.md -->
<!-- privacy: handle-only — no real name, no location, no employer anywhere in this file -->

<img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:1e1b4b,50:7c3aed,100:06b6d4&section=header&text=zhengqiuyang&fontSize=46&fontColor=ffffff&animation=twinkling&desc=deterministic%20agent%20tooling%20%C2%B7%20mcp%20security%20%C2%B7%20local-first&descSize=16&descAlignY=72" width="100%" alt="header" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&center=true&vCenter=true&width=760&height=50&color=8B5CF6&lines=agent+tooling+%C2%B7+mcp+security+%C2%B7+local-first;50+repos:+agents,+testing,+x-ray+dev+tools;home-assistant+%C2%B7+cline+%C2%B7+pr-agent+%C2%B7+opencode;bug+hunter+%C2%B7+parser+surgeon+%C2%B7+fix+shipper" alt="typing" />
</p>

<p align="center">
  <strong>building deterministic agent tooling — and fixing real bugs in the open source you actually run</strong><br/>
  <sub>工具链造在确定性上,名字写在合并记录里 —— 每一条都能点开验证</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/repos_built-50-7C3AED?style=flat-square&logo=github&logoColor=white" alt="repos" />
  <img src="https://img.shields.io/badge/awesome_dsh_plugin-10_plugins_%C2%B7_24.5k%E2%98%85-22C55E?style=flat-square" alt="awesome" />
  <img src="https://img.shields.io/badge/merged_into-210k%2B%E2%98%85_of_OSS-06B6D4?style=flat-square" alt="reach" />
</p>

---

<a id="projects"></a>

### 🧰 Projects

<sub>50 repos, one thesis: the guard-rail must be deterministic — zero LLM in the trust path. Highlights:</sub>

**Agent trust & testing**

| Repo | What it is |
|---|---|
| [mcp-test](https://github.com/zhengqiuyang/mcp-test) | MCP servers 功能+安全测试 — deterministic injection probes, one YAML, one exit code |
| [agent-attest](https://github.com/zhengqiuyang/agent-attest) | Signed chain-of-custody for AI coding agents — attest what the agent did, gate protected paths in CI |
| [agent-pr-gate](https://github.com/zhengqiuyang/agent-pr-gate) | Deterministic CI gate for AI-agent PRs — scope policy, residue scan, claims-vs-diff |
| [agentbench-local](https://github.com/zhengqiuyang/agentbench-local) | SWE-bench for YOUR repo, on YOUR machine — mines tasks from git history, grades with your own tests |
| [dsh-read-guard](https://github.com/zhengqiuyang/dsh-read-guard) | Prompt-injection interception — scans what the agent READS before it enters model context; obfuscation-resistant |

**X-ray tools for developers**

| Repo | What it is |
|---|---|
| [backlens](https://github.com/zhengqiuyang/backlens) | numpy autograd engine with X-ray vision — step-through backward debugging, NaN tracing, animated backward-pass films |
| [ctxlens](https://github.com/zhengqiuyang/ctxlens) | X-ray for your coding agent's context window — what ate your tokens? Deterministic, zero deps, local-first |

**Everyday AI apps**

| Repo | What it is |
|---|---|
| [interview-mate](https://github.com/zhengqiuyang/interview-mate) | 🎯 AI Agent 驱动的面试训练系统:智能体教练 / 模拟面试 / 间隔重复 / 岗位雷达,零依赖本地运行 |
| [clipbrain](https://github.com/zhengqiuyang/clipbrain) | AI 剪贴板大脑 — 语义检索你复制过的一切,local-first,可选 Ollama embeddings |

<sub>…plus 40+ more: agent-janitor, cronagent, agent-skills, callkeeper, clauselens, dsh-guardian-pet, dsh-spend-audit, WattWatch and the rest of the dsh family — <a href="https://github.com/zhengqiuyang?tab=repositories">full list</a></sub>

---

<a id="merged"></a>

### 🏆 Merged into

| Repo | ★ | PRs | Shipped |
|---|:-:|:-:|---|
| [home-assistant/core](https://github.com/home-assistant/core) | ![](https://img.shields.io/github/stars/home-assistant/core?style=flat-square&label=%E2%98%85) | [#190963](https://github.com/home-assistant/core/pull/190963) · [#191537](https://github.com/home-assistant/core/pull/191537) · [#189882](https://github.com/home-assistant/core/pull/189882) · [#189876](https://github.com/home-assistant/core/pull/189876) · [#189635](https://github.com/home-assistant/core/pull/189635) | **×5** — tplink_omada sensor crash fixes, WeatherFlow stuck entities, PSK redaction in diagnostics, imou discovery matchers |
| [The-PR-Agent/pr-agent](https://github.com/The-PR-Agent/pr-agent) | ![](https://img.shields.io/github/stars/The-PR-Agent/pr-agent?style=flat-square&label=%E2%98%85) | [#4651](https://github.com/The-PR-Agent/pr-agent/pull/4651) · [#4652](https://github.com/The-PR-Agent/pr-agent/pull/4652) · [#4761](https://github.com/The-PR-Agent/pr-agent/pull/4761) · [#4787](https://github.com/The-PR-Agent/pr-agent/pull/4787) · [#4799](https://github.com/The-PR-Agent/pr-agent/pull/4799) | **×5** — diff-parsing robustness: unified-diff headers, fence-aware stripping, hunk mapping, per-provider line counts |
| [cline/cline](https://github.com/cline/cline) | ![](https://img.shields.io/github/stars/cline/cline?style=flat-square&label=%E2%98%85) | [#15520](https://github.com/cline/cline/pull/15520) | streaming reasoning text cleared on session reset (VSCode) |
| [makecindy/cindy](https://github.com/makecindy/cindy) | ![](https://img.shields.io/github/stars/makecindy/cindy?style=flat-square&label=%E2%98%85) | [#8569](https://github.com/makecindy/cindy/pull/8569) | DeepSeek custom tool-cleaning applied across all model spellings |
| [opengeos/GeoLibre](https://github.com/opengeos/GeoLibre) | ![](https://img.shields.io/github/stars/opengeos/GeoLibre?style=flat-square&label=%E2%98%85) | [#3301](https://github.com/opengeos/GeoLibre/pull/3301) | `readPluginAsset` app API for plugin-bundled assets |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | ![](https://img.shields.io/github/stars/wangzan101/Mika?style=flat-square&label=%E2%98%85) | [#222](https://github.com/wangzan101/Mika/pull/222) | schedules re-computed in local time right after timezone change |
| [TestSprite/testsprite-cli](https://github.com/TestSprite/testsprite-cli) | ![](https://img.shields.io/github/stars/TestSprite/testsprite-cli?style=flat-square&label=%E2%98%85) | [#723](https://github.com/TestSprite/testsprite-cli/pull/723) · [#724](https://github.com/TestSprite/testsprite-cli/pull/724) | **×2** — shared JUnit report-flag rules; same-name tests kept distinct |
| [opengeos/geoai](https://github.com/opengeos/geoai) | ![](https://img.shields.io/github/stars/opengeos/geoai?style=flat-square&label=%E2%98%85) | [#949](https://github.com/opengeos/geoai/pull/949) · [#950](https://github.com/opengeos/geoai/pull/950) | **×2** — honor `device`/`model` args; restore missing einops dependency |
| [reticlehq/reticle](https://github.com/reticlehq/reticle) | ![](https://img.shields.io/github/stars/reticlehq/reticle?style=flat-square&label=%E2%98%85) | [#2147](https://github.com/reticlehq/reticle/pull/2147) | FOREIGN probe retried once; fill spelling mapped onto type |

<sub>every one of the 19 merged PRs is linked in the table above — click any number to verify</sub>

---

<a id="stats"></a>

### 📊 Stats

<table>
  <tr>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="assets/war-record-dark.svg" />
        <img src="assets/war-record-light.svg" alt="at a glance" width="100%" />
      </picture>
    </td>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=zhengqiuyang&hide_border=true&background=0D1117&border=30363D&dates=8B949E&ring=8B5CF6&currStreakNum=FFFFFF&currStreakLabel=22D3EE&sideNums=C9D1D9&sideLabels=8B949E" />
        <img src="https://streak-stats.demolab.com?user=zhengqiuyang&hide_border=true" alt="streak" width="100%" />
      </picture>
    </td>
  </tr>
</table>

<sub>数字采集于 2026-11-14 GitHub API · 每一条都能点开上面的链接验证</sub>

---

<a id="snake"></a>

### 🐍 Contribution snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/github-snake-dark.svg" />
  <img src="assets/github-snake-light.svg" alt="snake" width="100%" />
</picture>

<sub>generated by GitHub Action — refreshed daily and on every push</sub>

---

<a id="toolbox"></a>

### 🧰 Toolbox

<p align="center">
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=py,ts,js,bash,git,md&perline=6" alt="toolbox" /></a>
</p>

---

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:1e1b4b,50:7c3aed,100:06b6d4&section=footer" width="100%" alt="footer" />

<!-- built with: capsule-render · readme-typing-svg · streak-stats · skillicons.dev · platane/snk · 自绘 at-a-glance SVG(github-readme-stats / activity-graph 服务已于 2026-11 实测下线,camo 502,不采用) -->
