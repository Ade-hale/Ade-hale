## Hi, I'm Ade-hale ✨

**简体中文** · [English](./README.en.md)

**先复现，再修复，用证据说话。** 把复杂问题，拆成可以验证的小步。

📍 China · Java ·  Go ·  Python · TypeScript · JavaScript 

**[个人网站 →](https://ade-hale.github.io)** · [开源贡献 ↓](#开源协作)

---

### 🧭 我在做什么

我关注 AI 助手生态、消息平台集成与 Agent 工具链，主要用 TypeScript / JavaScript，也在学习 Go。

公开贡献以 OpenClaw 为主：定位根因、做范围小而完整的修复、补回归测试，并尽量用真实环境验证，而不只是让单元测试变绿。

我喜欢从具体问题出发：复现、拆解、做出一个能验证的小版本，再继续改进。

### 🚀 我的项目

**[dsh-skill-conflicts](https://github.com/Ade-hale/dsh-skill-conflicts)**

**按能力把已装 skill 分组，标出功能重叠项。** 一个 DeepSeek Harness 工具：读取当前 skill 目录，按能力（联网搜索、深度研究、代码评审、浏览器、Git、记忆等）分组，列出每组成员；同组 ≥2 个即标为疑似冗余。

每条都带来源标记（bundled / user / project / custom），方便在删除前定位它到底来自哪里。分组是启发式判断，标出的只是「疑似」，不是确证冲突。

[查看用法 →](https://github.com/Ade-hale/dsh-skill-conflicts#用法)

### 🔀 开源协作

以下是我提交的公开工作，链接可直接查看具体改动：

| 项目 | 我参与的改进 |
| --- | --- |
| [OpenClaw](https://github.com/openclaw/openclaw) | 修复飞书渠道发送附件时文件名丢失的问题：显式文件名与位置文件名在 send、回复与 fallback 路径中不再丢失，并补充回归测试、附飞书 API 服务端读回的真实验证 [PR #205415](https://github.com/openclaw/openclaw/pull/205415)（修复 [issue #205246](https://github.com/openclaw/openclaw/issues/205246)，重审中） |

[全部 PR →](https://github.com/pulls?q=is%3Apr+author%3AAde-hale) · [问题报告 →](https://github.com/issues?q=is%3Aissue+author%3AAde-hale)

### 🧱 技术方向

| 方向 | 公开项目与贡献中的实践 |
| --- | --- |
| **TypeScript / JavaScript** | OpenClaw 飞书渠道修复、dsh-skill-conflicts |
| **消息平台集成** | 飞书 / Lark 文件发送、回复投递与附件元数据处理 |
| **AI Agent 工具** | Skill 冲突检测、Agent 工作流工具 |
| **Go** | 学习中，关注代码评审与 CLI 工具 |

> 先把问题看清楚，再写一个可以验证的小版本；每次都比上次前进一点点。

---

<sub>联系我：在任意仓库开 issue 或 discussion 即可。</sub>
