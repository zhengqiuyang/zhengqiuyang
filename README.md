# 你好，我是郑润泽（zhengqiuyang）

🔴 开源贡献者 · 专注 **AI Agent 工具链**（provider 协议 / 流式状态机 / SSRF 防护 / Windows 平台）

> 三个多月里向 **18 个开源仓库**提交了 **30+ 个 PR** 和 **20+ 个 issue**——其中 **15 个 commit 已合并**进 **6 个仓库**的主干，覆盖从 1.3万★ 的 geoai 到 **22.5万★ 的 opencode**。
## 🏆 已合并贡献

| 仓库 | ★ | 贡献 | 内容 |
|---|---|---|---|
| **cline** | **7.1万** | [#15520](https://github.com/cline/cline/pull/15520) ✅ | 修复 VS Code 扩展中断任务的 reasoning 文本泄漏 + 自动续跑路径的同类重复 |
| **Home Assistant** | **8万+** | [#189635](https://github.com/home-assistant/core/pull/189635) ✅ [#189876](https://github.com/home-assistant/core/pull/189876) ✅ · [#190963](https://github.com/home-assistant/core/pull/190963)（审查中） | 已合并：tplink_omada PSK 脱敏、imou 指纹清理；审查中：端口消失导致的 sensor KeyError 修复（core MEMBER 审查中） |
| **pr-agent** | 1.4万 | [#4651](https://github.com/The-PR-Agent/pr-agent/pull/4651) ✅ [#4761](https://github.com/The-PR-Agent/pr-agent/pull/4761) ✅ | GitLab diff 文件头误计入变更行数；压缩路径把 +++ 文件头误判为新增导致删除 hunk 永不剔除（官方 bot 审查全绿） |
| **geoai** | 1.3万+ | [#949](https://github.com/opengeos/geoai/pull/949) ✅ [#950](https://github.com/opengeos/geoai/pull/950) ✅ | 修复 SamGeo device="cpu" 崩溃（参数未透传）；补 prithvi 缺失的 einops 依赖——作者（田纳西大学 Qiusheng Wu 教授）双 PR 同日合并 |
| **Mika** | 7.7k | [#309](https://github.com/wangzan101/Mika/pull/309) ✅ [#305](https://github.com/wangzan101/Mika/pull/305) ✅ | 4 commits——**正式 contributor（3 个 commit 的 author）**：跨时区计划触发修复、计划触发预览、SSE 协议终态收尾、回放审批分叉；**随 v0.1.34/35/36 三个版本发布**，issue #304 被维护者确认修复并关闭 |

## 🚀 审查中

| 仓库 | ★ | PR | 状态 |
|---|---|---|---|
| **open-design** | 10.5万 | [#9275](https://github.com/nexu-io/open-design/pull/9275) | **APPROVED**，QA 验证中 |
| **OpenHands** | 9.3万 | [#19281](https://github.com/OpenHands/OpenHands/pull/19281) · [#19328](https://github.com/OpenHands/OpenHands/pull/19328) | CI 全绿，等 review |
| **CopilotKit** | 3万+ | [#8222](https://github.com/CopilotKit/CopilotKit/pull/8222) | HITL 交互按 toolCallId 精确路由（CodeRabbit 审查通过） |
| **pr-agent** | 1.4万 | [#4652](https://github.com/The-PR-Agent/pr-agent/pull/4652) | describe 标题剥除损坏 + 四反引号 fence 回归，等详审 |
| **cindy** | 1.05万 | [#8569](https://github.com/makecindy/cindy/pull/8569) | DeepSeek 自定义供应商出站 400 修复，格式门已过等续审 |
| **TestSprite** | 5千 | [#723](https://github.com/TestSprite/testsprite-cli/pull/723) · [#724](https://github.com/TestSprite/testsprite-cli/pull/724) | MERGEABLE，等评审窗口 |
| **opencode** | **22.5万** | [#61462](https://github.com/anomalyco/opencode/pull/61462) · [#61463](https://github.com/anomalyco/opencode/pull/61463) · [#61464](https://github.com/anomalyco/opencode/pull/61464) | 事件重投递去重三连修，等 triage |
| **litellm** | 6.3万 | [#50249](https://github.com/BerriAI/litellm/pull/50249) | cohere embeddings 忽略 COHERE_API_BASE（与 rerank 路径不对称）——审查意见三点已全部响应，CLA 已签 |

## 🎯 被采纳的报告与审查

- **pydantic-ai** [#12367](https://github.com/pydantic/pydantic-ai/issues/12367)（`p:2-high`）：压缩混合基数减法缺陷——官方 bot 2 小时内按我的诊断转成修复 PR
- **OpenHands** [#19278](https://github.com/OpenHands/OpenHands/issues/19278)：V0/V1 事件存储断层 + 静默丢弃——贡献者认领实现中，我提供了 resume 语义锚点（服务端 cap 路径）
- **Mika** [#295](https://github.com/wangzan101/Mika/issues/295)：Ollama 流式挂死定位——修复随 v0.1.37 发布，维护者公开致谢
- **Mika** [#165](https://github.com/wangzan101/Mika/issues/165#issuecomment-3366098517)：代码阅读发现导入技能的校验边界（不改全文即跳过校验）——采纳后 imported 草稿无条件校验，随 v0.1.35 落地
- **caveman** [#1437](https://github.com/JuliusBrussee/caveman/issues/1437)/[#1453](https://github.com/JuliusBrussee/caveman/issues/1453)/[#1457](https://github.com/JuliusBrussee/caveman/issues/1457)：三个诊断全部确认并修复——*「your diagnosis and your suggested fix were both right」*「a cleaner statement of it than the commit message manages」
- **pr-agent** [#4653](https://github.com/The-PR-Agent/pr-agent/issues/4653)：Action 双跑——第三方次日按此修复（#4654 合并），维护者致谢 *「precise report」*
- **证伪也被感谢**：[#1454](https://github.com/JuliusBrussee/caveman/issues/1454) 的假说被证伪，可证伪 caveat 让维护者一天定位——*「thank you for it」*

## 🔧 我挖 bug 的领域

- **provider 协议不对称**：同一 provider 的 embedding/rerank/chat 分支读取环境变量的行为不一致（litellm cohere/voyage）
- **流式状态生命周期**：协议终态收尾、中断后的状态残留、事件重投递去重（cline/Mika/opencode）
- **HTTP 客户端固定与 SSRF 防护**：DNS 重绑定窗口、地址固定、代理降级
- **Windows 平台盲区**：注册表代理、路径长度、home 目录探测——Linux-only CI 看不见的bug

## 📮 联系

- GitHub：[zhengqiuyang](https://github.com/zhengqiuyang)
- 邮箱：506166760@qq.com
