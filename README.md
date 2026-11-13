<!-- 🚧 DRAFT — 未获用户批准前不发布。发布步骤见 PUBLISH.md -->
<!-- privacy: handle-only — no real name, no location, no employer anywhere in this file -->

<img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:1e1b4b,50:7c3aed,100:06b6d4&section=header&text=zhengqiuyang&fontSize=46&fontColor=ffffff&animation=twinkling&desc=bug%20hunter%20%C2%B7%20agent%20tooling%20%C2%B7%20parser%20surgery&descSize=16&descAlignY=72" width="100%" alt="header" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&center=true&vCenter=true&width=760&height=50&color=8B5CF6&lines=bug+hunter+%C2%B7+parser+surgeon+%C2%B7+fix+shipper;19+PRs+merged+into+210k%E2%98%85+of+open+source;home-assistant+%C2%B7+cline+%C2%B7+pr-agent+%C2%B7+opencode;in+review:+mujoco+%C2%B7+litellm+%C2%B7+haystack+%C2%B7+OpenHands" alt="typing" />
</p>

<p align="center">
  <strong>fixing real bugs in the open source you actually run</strong><br/>
  <sub>用真实的合并记录说话 —— 每一条都能点开验证</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/code_PRs_merged-19-7C3AED?style=flat-square&logo=github&logoColor=white" alt="merged" />
  <img src="https://img.shields.io/badge/merged_into-210k%2B%E2%98%85_of_OSS-06B6D4?style=flat-square" alt="reach" />
  <img src="https://img.shields.io/badge/under_review-14_PRs_%C2%B7_660k%2B%E2%98%85-F59E0B?style=flat-square" alt="review" />
  <img src="https://img.shields.io/badge/listed_%C3%975-awesome--dsh--plugin_24.5k%E2%98%85-22C55E?style=flat-square" alt="awesome" />
</p>

> 🎯 fixes shipped into codebases totalling **210k+ ★** · 14 more under review across **660k+ ★**

---

<a id="merged"></a>

### 🏆 Merged into

| Repo | ★ | Shipped |
|---|:-:|---|
| [home-assistant/core](https://github.com/home-assistant/core) | ![](https://img.shields.io/github/stars/home-assistant/core?style=flat-square&label=%E2%98%85) | **×5** — tplink_omada sensor crash fixes, WeatherFlow stuck entities, PSK redaction in diagnostics, imou discovery matchers |
| [The-PR-Agent/pr-agent](https://github.com/The-PR-Agent/pr-agent) | ![](https://img.shields.io/github/stars/The-PR-Agent/pr-agent?style=flat-square&label=%E2%98%85) | **×5** — diff-parsing robustness: unified-diff headers, fence-aware stripping, hunk mapping, per-provider line counts |
| [cline/cline](https://github.com/cline/cline) | ![](https://img.shields.io/github/stars/cline/cline?style=flat-square&label=%E2%98%85) | streaming reasoning text cleared on session reset (VSCode) |
| [makecindy/cindy](https://github.com/makecindy/cindy) | ![](https://img.shields.io/github/stars/makecindy/cindy?style=flat-square&label=%E2%98%85) | DeepSeek custom tool-cleaning applied across all model spellings |
| [opengeos/GeoLibre](https://github.com/opengeos/GeoLibre) | ![](https://img.shields.io/github/stars/opengeos/GeoLibre?style=flat-square&label=%E2%98%85) | `readPluginAsset` app API for plugin-bundled assets |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | ![](https://img.shields.io/github/stars/wangzan101/Mika?style=flat-square&label=%E2%98%85) | schedules re-computed in local time right after timezone change |
| [TestSprite/testsprite-cli](https://github.com/TestSprite/testsprite-cli) | ![](https://img.shields.io/github/stars/TestSprite/testsprite-cli?style=flat-square&label=%E2%98%85) | **×2** — shared JUnit report-flag rules; same-name tests kept distinct |
| [opengeos/geoai](https://github.com/opengeos/geoai) | ![](https://img.shields.io/github/stars/opengeos/geoai?style=flat-square&label=%E2%98%85) | **×2** — honor `device`/`model` args; restore missing einops dependency |
| [reticlehq/reticle](https://github.com/reticlehq/reticle) | ![](https://img.shields.io/github/stars/reticlehq/reticle?style=flat-square&label=%E2%98%85) | FOREIGN probe retried once; fill spelling mapped onto type |

<details>
<summary>📋 every merged PR, linked (19)</summary>

**home-assistant/core**
- [#190963](https://github.com/home-assistant/core/pull/190963) — Fix KeyError in tplink_omada device and switch port sensors (2026-11-09)
- [#191537](https://github.com/home-assistant/core/pull/191537) — Fix WeatherFlow Cloud entities getting stuck when a station disappears (2026-11-09)
- [#189882](https://github.com/home-assistant/core/pull/189882) — Fix StopIteration in tplink_omada gateway port binary sensors (2026-11-09)
- [#189876](https://github.com/home-assistant/core/pull/189876) — Remove Dahua OUI DHCP matchers from imou discovery (2026-11-02)
- [#189635](https://github.com/home-assistant/core/pull/189635) — Redact PSK in tplink_omada diagnostics (2026-11-01)

**The-PR-Agent/pr-agent**
- [#4799](https://github.com/The-PR-Agent/pr-agent/pull/4799) — report diff line counts for gerrit, codecommit and local git (2026-11-09)
- [#4787](https://github.com/The-PR-Agent/pr-agent/pull/4787) — move non-committable comments into the nearest hunk (2026-11-09)
- [#4761](https://github.com/The-PR-Agent/pr-agent/pull/4761) — strip pre-hunk file headers in handle_patch_deletions output (2026-11-08)
- [#4652](https://github.com/The-PR-Agent/pr-agent/pull/4652) — fence-aware stripping for large-PR headers (2026-11-09)
- [#4651](https://github.com/The-PR-Agent/pr-agent/pull/4651) — gitlab: ignore unified-diff file headers in per-file line counts (2026-11-05)

**others**
- [cline#15520](https://github.com/cline/cline/pull/15520) — clear streaming reasoning text on reset (2026-11-05)
- [makecindy/cindy#8569](https://github.com/makecindy/cindy/pull/8569) — DeepSeek 自定义工具清洗覆盖所有型号拼写 (2026-11-12)
- [opengeos/GeoLibre#3301](https://github.com/opengeos/GeoLibre/pull/3301) — Add readPluginAsset app API for plugin-bundled assets (2026-11-09)
- [wangzan101/Mika#222](https://github.com/wangzan101/Mika/pull/222) — 改时区后立即按新时区重算按当地时间的计划 (2026-11-02)
- [TestSprite#723](https://github.com/TestSprite/testsprite-cli/pull/723) — enforce the shared JUnit report-flag rules in testlist run (2026-11-10)
- [TestSprite#724](https://github.com/TestSprite/testsprite-cli/pull/724) — keep same-name tests distinct in JUnit reports (2026-11-10)
- [opengeos/geoai#950](https://github.com/opengeos/geoai/pull/950) — sam: honor device and model arguments in prompted mode (2026-11-08)
- [opengeos/geoai#949](https://github.com/opengeos/geoai/pull/949) — prithvi: add missing einops dependency (2026-11-08)
- [reticlehq/reticle#2147](https://github.com/reticlehq/reticle/pull/2147) — retry the FOREIGN probe once; map the fill spelling onto type (2026-11-10)

</details>

---

<a id="review"></a>

### 🔬 Under review — 14 PRs across 8 repos (660k+ ★)

| Repo | ★ | In flight |
|---|:-:|---|
| [anomalyco/opencode](https://github.com/anomalyco/opencode) | ![](https://img.shields.io/github/stars/anomalyco/opencode?style=flat-square&label=%E2%98%85) | **×3** — duplicate-delivery safety: a re-delivered event must not duplicate tool parts, duplicate rows, or regress settled messages ([#61462](https://github.com/anomalyco/opencode/pull/61462), [#61463](https://github.com/anomalyco/opencode/pull/61463), [#61464](https://github.com/anomalyco/opencode/pull/61464)) |
| [nexu-io/open-design](https://github.com/nexu-io/open-design) | ![](https://img.shields.io/github/stars/nexu-io/open-design?style=flat-square&label=%E2%98%85) | **×2** — a throwing send must not crash the daemon or leak the agent process tree ([#9275](https://github.com/nexu-io/open-design/pull/9275)); inline resources longest-first through escaped spellings ([#9276](https://github.com/nexu-io/open-design/pull/9276)) |
| [OpenHands/OpenHands](https://github.com/OpenHands/OpenHands) | ![](https://img.shields.io/github/stars/OpenHands/OpenHands?style=flat-square&label=%E2%98%85) | **×2** — re-render Messages on mid-list streaming slot replacement ([#19328](https://github.com/OpenHands/OpenHands/pull/19328)); stop writing dead localStorage field ([#19281](https://github.com/OpenHands/OpenHands/pull/19281)) |
| [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit) | ![](https://img.shields.io/github/stars/CopilotKit/CopilotKit?style=flat-square&label=%E2%98%85) | **×2** — route HITL answers to their own interaction by tool call id ([#8222](https://github.com/CopilotKit/CopilotKit/pull/8222)); save post-apply agent state per run ([#8195](https://github.com/CopilotKit/CopilotKit/pull/8195)) |
| [BerriAI/litellm](https://github.com/BerriAI/litellm) | ![](https://img.shields.io/github/stars/BerriAI/litellm?style=flat-square&label=%E2%98%85) | COHERE_API_BASE honored for embeddings ([#50249](https://github.com/BerriAI/litellm/pull/50249)) |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | ![](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat-square&label=%E2%98%85) | reject non-mapping input when deserializing a Pipeline ([#13739](https://github.com/deepset-ai/haystack/pull/13739)) |
| [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) | ![](https://img.shields.io/github/stars/google-deepmind/mujoco?style=flat-square&label=%E2%98%85) | **×2** — rollout accepts a sequence of MjData ([#3818](https://github.com/google-deepmind/mujoco/pull/3818)); MJX honors `disableactuator` ([#3803](https://github.com/google-deepmind/mujoco/pull/3803)) |
| [home-assistant/core](https://github.com/home-assistant/core) | ![](https://img.shields.io/github/stars/home-assistant/core?style=flat-square&label=%E2%98%85) | WLED zeroconf discovery KeyError for ignored entries ([#191601](https://github.com/home-assistant/core/pull/191601)) |

---

<a id="stats"></a>

### 📊 Stats

<table>
  <tr>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="assets/war-record-dark.svg" />
        <img src="assets/war-record-light.svg" alt="war record" width="100%" />
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

<sub>数字采集于 2026-11-14 GitHub API · 每一条都能点开上面的 PR 链接验证</sub>

---

<a id="snake"></a>

### 🐍 Contribution snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/zhengqiuyang/zhengqiuyang/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/zhengqiuyang/zhengqiuyang/output/github-snake.svg" alt="snake" width="100%" />
</picture>

<sub>runs daily via GitHub Action — activates after publish</sub>

---

<a id="toolbox"></a>

### 🧰 Toolbox

<p align="center">
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=py,ts,js,bash,git,md&perline=6" alt="toolbox" /></a>
</p>

---

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:1e1b4b,50:7c3aed,100:06b6d4&section=footer" width="100%" alt="footer" />

<!-- built with: capsule-render · readme-typing-svg · streak-stats · skillicons.dev · platane/snk · 自绘 war-record SVG(github-readme-stats / activity-graph 服务已于 2026-11 实测下线,camo 502,不采用) -->
