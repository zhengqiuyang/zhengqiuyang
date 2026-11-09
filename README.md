<div align="center">

# 郑润泽 · zhengqiuyang

做 AI Agent 工具链的开源贡献：provider 协议不一致、流式状态生命周期、SSRF 与 Windows 平台盲区。

**21 个仓库 · 50 个 PR · 30 个 issue · 19 个已合并**

</div>

## 已合并

11 个落在 5 个第三方仓库的主干，另有 5 个在 awesome-dsh-plugin 列表、3 个自有仓库。

| 仓库 | ★ | PR | 修了什么 |
|---|---|---|---|
| [cline](https://github.com/cline/cline) | 71k | [#15520](https://github.com/cline/cline/pull/15520) | 中断任务的 reasoning 文本泄漏进下一轮，以及自动续跑路径的同类重复 |
| [Home Assistant](https://github.com/home-assistant/core) | 92k | [#189635](https://github.com/home-assistant/core/pull/189635) [#189876](https://github.com/home-assistant/core/pull/189876) [#189882](https://github.com/home-assistant/core/pull/189882) | tplink_omada 诊断的 PSK 脱敏；imou 发现里过期的 Dahua DHCP 指纹 |
| [pr-agent](https://github.com/The-PR-Agent/pr-agent) | 16k | [#4651](https://github.com/The-PR-Agent/pr-agent/pull/4651) [#4652](https://github.com/The-PR-Agent/pr-agent/pull/4652) [#4761](https://github.com/The-PR-Agent/pr-agent/pull/4761) [#4787](https://github.com/The-PR-Agent/pr-agent/pull/4787) | GitLab diff 文件头被误计入每文件变更行数；describe 的围栏感知剥离（含四反引号与线性化性能测试）；删除 hunk 的 `+++` 文件头污染 |
| [geoai](https://github.com/opengeos/geoai) | 3.5k | [#949](https://github.com/opengeos/geoai/pull/949) [#950](https://github.com/opengeos/geoai/pull/950) | SamGeo `device="cpu"` 崩溃（参数未透传）；prithvi 缺 einops 依赖 |
| [Mika](https://github.com/wangzan101/Mika) | 7.7k | [#222](https://github.com/wangzan101/Mika/pull/222) [#309](https://github.com/wangzan101/Mika/pull/309) [#305](https://github.com/wangzan101/Mika/pull/305) | 跨时区计划重算、SSE 协议终态收尾、回放审批分叉。3 个 commit 的 author，随 v0.1.34 / v0.1.36 发布；PR 本身被维护者重整后关闭，commit 保留署名 |

## 自研工具：DSH 信任层

一套围绕 DeepSeek Harness 的“确定性信任”插件：不在信任路径上调用 LLM，全部是静态判定。10 个插件分 5 个 PR 收录进 [awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin)（23.8k★，2026-10-17 ~ 10-20）。

| 插件 | 守什么 |
|---|---|
| [dsh-read-guard](https://github.com/zhengqiuyang/dsh-read-guard) | 读：提示注入拦截，凭据文件按路径直接隔离 |
| [dsh-pr-gate](https://github.com/zhengqiuyang/dsh-pr-gate) | 写：写入瞬间的作用域策略与残留扫描 |
| [dsh-attest-chain](https://github.com/zhengqiuyang/dsh-attest-chain) | 做过什么：ed25519 签名的哈希链，commit 绑进链 |
| [dsh-mcp-test](https://github.com/zhengqiuyang/dsh-mcp-test) | 能调什么：工具面快照，静默变更即失败 |
| [dsh-egress-gate](https://github.com/zhengqiuyang/dsh-egress-gate) | 出网：按目的地白名单拦截 |
| [dsh-prompt-drift](https://github.com/zhengqiuyang/dsh-prompt-drift) | 被告知什么：system prompt 段落哈希基线 |
| [dsh-freeze](https://github.com/zhengqiuyang/dsh-freeze) | 组合锁定：profile 指纹漂移告警或失败 |
| [dsh-janitor](https://github.com/zhengqiuyang/dsh-janitor) | 产物生命周期：扫描并给出可审阅的清理计划 |
| [dsh-compaction-guard](https://github.com/zhengqiuyang/dsh-compaction-guard) | 压缩完整性：被压缩掉的约束是否被摘要丢掉 |
| [dsh-trust-panel](https://github.com/zhengqiuyang/dsh-trust-panel) | 给人看的：十路状态合成一盏灯 |

收录 PR：[#7227](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/7227) · [#7700](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/7700) · [#7701](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/7701) · [#7743](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/7743) · [#8133](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/8133)

## 在审

| 仓库 | ★ | PR | 状态 |
|---|---|---|---|
| [open-design](https://github.com/nexu-io/open-design) | 107k | [#9275](https://github.com/nexu-io/open-design/pull/9275) | APPROVED，等 QA |
| [OpenHands](https://github.com/OpenHands/OpenHands) | 93k | [#19281](https://github.com/OpenHands/OpenHands/pull/19281) [#19328](https://github.com/OpenHands/OpenHands/pull/19328) | CI 全绿，等 review |
| [opencode](https://github.com/anomalyco/opencode) | 225k | [#61462](https://github.com/anomalyco/opencode/pull/61462) [#61463](https://github.com/anomalyco/opencode/pull/61463) [#61464](https://github.com/anomalyco/opencode/pull/61464) | 事件重复投递的幂等三连修 |
| [litellm](https://github.com/BerriAI/litellm) | 63k | [#50249](https://github.com/BerriAI/litellm/pull/50249) | cohere embeddings 忽略 `COHERE_API_BASE`；审查意见已响应，CLA 已签 |
| [CopilotKit](https://github.com/CopilotKit/CopilotKit) | 39k | [#8222](https://github.com/CopilotKit/CopilotKit/pull/8222) [#8195](https://github.com/CopilotKit/CopilotKit/pull/8195) | HITL 应答按 tool call id 精确路由 |
| [GeoLibre](https://github.com/opengeos/GeoLibre) | 8.5k | [#3301](https://github.com/opengeos/GeoLibre/pull/3301) | 插件读取自身 bundle 内资源（#2782 item 1）；**APPROVED，CI 全绿** |

<details>
<summary>另外 9 个</summary>

| PR | 状态 |
|---|---|
| Home Assistant [#190963](https://github.com/home-assistant/core/pull/190963) | 端口/设备消失导致的 sensor KeyError，等 codeowner |
| Home Assistant [#189882](https://github.com/home-assistant/core/pull/189882) | gateway 端口传感器的 StopIteration，等 review |
| reticle [#2147](https://github.com/reticlehq/reticle/pull/2147) | FOREIGN 探针重试 + fill 拼写映射，等重审 |
| cindy [#8569](https://github.com/makecindy/cindy/pull/8569) | DeepSeek 自定义供应商出站 400，已 APPROVED |
| TestSprite [#723](https://github.com/TestSprite/testsprite-cli/pull/723) [#724](https://github.com/TestSprite/testsprite-cli/pull/724) | 报告标志校验、同名测试折叠 |
| open-design [#9276](https://github.com/nexu-io/open-design/pull/9276) | clipper 资源内联顺序 |

</details>

## 被采纳的报告与审查

- **[pydantic-ai](https://github.com/pydantic/pydantic-ai)** [#12367](https://github.com/pydantic/pydantic-ai/issues/12367)（`p:2-high`）：压缩的混合基数减法缺陷，官方 bot 在 2 小时内按这份诊断生成了修复 PR
- **[langfuse](https://github.com/langfuse/langfuse)** [#19924](https://github.com/langfuse/langfuse/issues/19924)：evaluator 对裸 403 不暂停、Topics 却暂停——维护者一小时内以 [#19940](https://github.com/langfuse/langfuse/pull/19940) 合入修复，并在实现里补了「内容过滤不该暂停」这一层
- **[caveman](https://github.com/JuliusBrussee/caveman)** [#1437](https://github.com/JuliusBrussee/caveman/issues/1437) / [#1453](https://github.com/JuliusBrussee/caveman/issues/1453)：hook 键序与计费限定符的根因——维护者称比 commit message 说得更清楚
- **[pr-agent](https://github.com/The-PR-Agent/pr-agent)** [#4653](https://github.com/The-PR-Agent/pr-agent/issues/4653)：Action 双跑，第三方次日按此修复
- **[OpenHands](https://github.com/OpenHands/OpenHands)** [#19278](https://github.com/OpenHands/OpenHands/issues/19278)：V0/V1 事件存储断层与静默丢弃
- **[Mika](https://github.com/wangzan101/Mika)** [#295](https://github.com/wangzan101/Mika/issues/295)：定位 Ollama 流式挂死，关闭说明把「流式响应在协议终态后立即收尾」列为修复项之一（即我们的改动），其余静默被认定在本地模型服务端；[#165](https://github.com/wangzan101/Mika/issues/165#issuecomment-3366098517)：导入技能时「不改全文就跳过校验」的边界

## 我挖什么

- **provider 协议不对称**：同一个 provider 的 embedding / rerank / chat 分支读取环境变量的行为不一致
- **流式状态生命周期**：协议终态收尾、中断后的状态残留、事件重投递去重
- **HTTP 客户端固定与 SSRF 防护**：DNS 重绑定窗口、地址固定、代理降级
- **Windows 平台盲区**：注册表代理、路径长度、home 目录探测——Linux-only CI 看不见的那些

---

<a id="verify"></a>
每条链接都指向原始 PR / issue，数字采于 2026-11-09。自己核验：

```bash
gh search prs --author zhengqiuyang --merged --limit 50
```

GitHub [@zhengqiuyang](https://github.com/zhengqiuyang) · 506166760@qq.com
