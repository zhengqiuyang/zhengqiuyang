<!-- privacy: handle-only — 全文仅使用 handle,无真名/位置/雇主信息 -->
<!-- English version: README.md -->

<img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:1e1b4b,50:7c3aed,100:06b6d4&section=header&text=zhengqiuyang&fontSize=46&fontColor=ffffff&animation=twinkling" width="100%" alt="header" />

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/lang-English-7C3AED?style=flat-square" alt="English" /></a>
  <a href="./README.zh-CN.md"><img src="https://img.shields.io/badge/lang-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-06B6D4?style=flat-square" alt="简体中文" /></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&center=true&vCenter=true&width=760&height=50&color=8B5CF6&lines=%E7%A1%AE%E5%AE%9A%E6%80%A7+agent+%E5%B7%A5%E5%85%B7%E9%93%BE+%C2%B7+%E6%9C%AC%E5%9C%B0%E4%BC%98%E5%85%88;50+%E4%B8%AA%E4%BB%93%E5%BA%93:+agent%E3%80%81%E6%B5%8B%E8%AF%95%E3%80%81%E9%80%8F%E8%A7%86%E9%95%9C%E5%B7%A5%E5%85%B7;home-assistant+%C2%B7+cline+%C2%B7+pr-agent+%C2%B7+opencode;%E6%AF%8F%E4%B8%80%E6%9D%A1%E9%83%BD%E5%8F%AF%E7%82%B9%E5%BC%80%E9%AA%8C%E8%AF%81" alt="typing" />
</p>

<p align="center">
  <strong>给 agent 造确定性的护栏 —— 顺手修真实项目里的真实 bug</strong><br/>
  <sub>building deterministic agent tooling — and fixing real bugs in the open source you actually run</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/%E8%87%AA%E5%BB%BA%E4%BB%93%E5%BA%93-50-7C3AED?style=flat-square&logo=github&logoColor=white" alt="repos" />
  <img src="https://img.shields.io/badge/awesome_dsh_plugin-10_plugins_%C2%B7_24.5k%E2%98%85-22C55E?style=flat-square" alt="awesome" />
  <img src="https://img.shields.io/badge/%E5%90%88%E8%BF%9B-210k%2B%E2%98%85_%E5%BC%80%E6%BA%90-06B6D4?style=flat-square" alt="reach" />
</p>

> 🧭 用确定性给 agent 造护栏 · 修进 210k+★ 的开源项目

### 🧰 项目

<sub>50 个仓库,一个信念:护栏必须是确定性的——信任路径上零 LLM。精选:</sub>

**Agent 信任与测试**

| 仓库 | 简介 |
|---|---|
| [mcp-test](https://github.com/zhengqiuyang/mcp-test) | MCP 服务器功能+安全测试:确定性注入探针,一个 YAML,一个退出码 |
| [agent-attest](https://github.com/zhengqiuyang/agent-attest) | AI 编码代理的签名监管链:记录代理做过什么,CI 中门禁保护路径 |
| [agent-pr-gate](https://github.com/zhengqiuyang/agent-pr-gate) | AI 代理 PR 的确定性 CI 门禁:范围策略、残留扫描、声明与 diff 对账 |
| [agentbench-local](https://github.com/zhengqiuyang/agentbench-local) | 把 SWE-bench 搬到你自己的仓库:从 git 历史挖任务,用你自己的测试评分 |
| [dsh-read-guard](https://github.com/zhengqiuyang/dsh-read-guard) | 提示注入拦截:在进入模型上下文之前扫描代理读了什么,抗混淆 |

**开发者的透视镜**

| 仓库 | 简介 |
|---|---|
| [backlens](https://github.com/zhengqiuyang/backlens) | 带透视能力的 numpy autograd 引擎:步进调试反向传播、NaN 追踪、反向传播动画 |
| [ctxlens](https://github.com/zhengqiuyang/ctxlens) | 编码代理上下文透视镜:token 都被谁吃了?确定性、零依赖、本地优先 |

**日常 AI 应用**

| 仓库 | 简介 |
|---|---|
| [interview-mate](https://github.com/zhengqiuyang/interview-mate) | 🎯 AI Agent 驱动的面试训练系统:智能体教练 / 模拟面试 / 间隔重复 / 岗位雷达,零依赖本地运行 |
| [clipbrain](https://github.com/zhengqiuyang/clipbrain) | AI 剪贴板大脑:语义检索你复制过的一切,本地优先,可选 Ollama embeddings |

<sub>…另有 40+ 个仓库:agent-janitor、cronagent、agent-skills、callkeeper、clauselens、dsh-guardian-pet、dsh-spend-audit、WattWatch 与 dsh 全家 —— <a href="https://github.com/zhengqiuyang?tab=repositories">完整列表</a></sub>

### 🏆 合并记录

| 仓库 | ★ | PRs | 修了什么 |
|---|:-:|:-:|---|
| [home-assistant/core](https://github.com/home-assistant/core) | ![](https://img.shields.io/github/stars/home-assistant/core?style=flat-square&label=%E2%98%85) | [#190963](https://github.com/home-assistant/core/pull/190963) · [#191537](https://github.com/home-assistant/core/pull/191537) · [#189882](https://github.com/home-assistant/core/pull/189882) · [#189876](https://github.com/home-assistant/core/pull/189876) · [#189635](https://github.com/home-assistant/core/pull/189635) | **×5** — tplink_omada 传感器崩溃修复、WeatherFlow 实体卡死、诊断信息 PSK 脱敏、imou 发现匹配器 |
| [The-PR-Agent/pr-agent](https://github.com/The-PR-Agent/pr-agent) | ![](https://img.shields.io/github/stars/The-PR-Agent/pr-agent?style=flat-square&label=%E2%98%85) | [#4651](https://github.com/The-PR-Agent/pr-agent/pull/4651) · [#4652](https://github.com/The-PR-Agent/pr-agent/pull/4652) · [#4761](https://github.com/The-PR-Agent/pr-agent/pull/4761) · [#4787](https://github.com/The-PR-Agent/pr-agent/pull/4787) · [#4799](https://github.com/The-PR-Agent/pr-agent/pull/4799) | **×5** — diff 解析健壮性:unified-diff 文件头、fence 感知剥离、hunk 映射、多 provider 行数统计 |
| [cline/cline](https://github.com/cline/cline) | ![](https://img.shields.io/github/stars/cline/cline?style=flat-square&label=%E2%98%85) | [#15520](https://github.com/cline/cline/pull/15520) | 会话重置时清空流式 reasoning 文本(VSCode) |
| [makecindy/cindy](https://github.com/makecindy/cindy) | ![](https://img.shields.io/github/stars/makecindy/cindy?style=flat-square&label=%E2%98%85) | [#8569](https://github.com/makecindy/cindy/pull/8569) | DeepSeek 自定义工具清洗覆盖所有型号拼写 |
| [opengeos/GeoLibre](https://github.com/opengeos/GeoLibre) | ![](https://img.shields.io/github/stars/opengeos/GeoLibre?style=flat-square&label=%E2%98%85) | [#3301](https://github.com/opengeos/GeoLibre/pull/3301) | 新增 `readPluginAsset` app API,供插件自带资源读取 |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | ![](https://img.shields.io/github/stars/wangzan101/Mika?style=flat-square&label=%E2%98%85) | [#222](https://github.com/wangzan101/Mika/pull/222) | 改时区后立即按新时区重算按当地时间的计划 |
| [TestSprite/testsprite-cli](https://github.com/TestSprite/testsprite-cli) | ![](https://img.shields.io/github/stars/TestSprite/testsprite-cli?style=flat-square&label=%E2%98%85) | [#723](https://github.com/TestSprite/testsprite-cli/pull/723) · [#724](https://github.com/TestSprite/testsprite-cli/pull/724) | **×2** — 统一 JUnit 报告参数规则;同名测试保持区分 |
| [opengeos/geoai](https://github.com/opengeos/geoai) | ![](https://img.shields.io/github/stars/opengeos/geoai?style=flat-square&label=%E2%98%85) | [#949](https://github.com/opengeos/geoai/pull/949) · [#950](https://github.com/opengeos/geoai/pull/950) | **×2** — 尊重 `device`/`model` 参数;补回缺失的 einops 依赖 |
| [reticlehq/reticle](https://github.com/reticlehq/reticle) | ![](https://img.shields.io/github/stars/reticlehq/reticle?style=flat-square&label=%E2%98%85) | [#2147](https://github.com/reticlehq/reticle/pull/2147) | FOREIGN 探测失败重试一次;fill 拼写映射到正确类型 |

<sub>19 个合并 PR 全部带链接——点任意编号即可核验</sub>

### 📊 数据

<table>
  <tr>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="assets/war-record-zh-dark.svg" />
        <img src="assets/war-record-zh-light.svg" alt="一图速览" width="100%" />
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

### 🐍 贡献蛇

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/github-snake-dark.svg" />
  <img src="assets/github-snake-light.svg" alt="snake" width="100%" />
</picture>

<sub>由 GitHub Action 生成 —— 每天与每次推送后自动刷新</sub>

### 🧰 工具箱

<p align="center">
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=py,ts,js,bash,git,md&perline=6" alt="toolbox" /></a>
</p>

---

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:1e1b4b,50:7c3aed,100:06b6d4&section=footer" width="100%" alt="footer" />

<!-- built with: capsule-render · readme-typing-svg · streak-stats · skillicons.dev · platane/snk · 自绘一图速览 SVG -->
