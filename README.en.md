## Hi, I'm Ade-hale ✨

[简体中文](./README.md) · **English**

**Reproduce first, fix with evidence.** Turn complex problems into small, verifiable steps.

📍 China · Java ·  Go ·  Python · TypeScript · JavaScript

**[Personal site →](https://ade-hale.github.io)** · [Open source ↓](#open-source)

---

### 🧭 What I'm Working On

I focus on the AI assistant ecosystem, messaging platform integrations, and agent tooling — mainly in TypeScript / JavaScript, while learning Go.

My public contributions centre on OpenClaw: finding the root cause, making small and complete fixes, adding regression tests, and verifying against real environments rather than only making unit tests pass.

I like to start from a concrete problem: reproduce it, break it down, ship a small verifiable version, then keep improving it.

### 🚀 My Projects

**[dsh-skill-conflicts](https://github.com/Ade-hale/dsh-skill-conflicts)**

**Group installed skills by capability, and flag the overlapping ones.** A DeepSeek Harness tool that reads the current skill directory, groups skills by capability (web search, deep research, code review, browser, Git, memory, and more), and marks any group with two or more members as potentially redundant.

Every entry carries its source (bundled / user / project / custom), so you can tell where a skill came from before removing it. Grouping is heuristic — flagged items are *suspected* overlaps, not confirmed conflicts.

[How to use it →](https://github.com/Ade-hale/dsh-skill-conflicts#用法)

### 🔀 Open Source

Public work I have submitted — each link goes to the actual change:

| Project | My contribution |
| --- | --- |
| [OpenClaw](https://github.com/openclaw/openclaw) | Fixed attachment filenames being dropped in the Feishu channel: explicit and positional filenames now survive the send, reply, and fallback paths, with regression tests and live verification read back from the Feishu API — [PR #205415](https://github.com/openclaw/openclaw/pull/205415) (fixes [issue #205246](https://github.com/openclaw/openclaw/issues/205246), in re-review) |

[All PRs →](https://github.com/pulls?q=is%3Apr+author%3AAde-hale) · [Issue reports →](https://github.com/issues?q=is%3Aissue+author%3AAde-hale)

### 🧱 Tech Focus

| Area | Practice in public projects & contributions |
| --- | --- |
| **TypeScript / JavaScript** | OpenClaw Feishu channel fix, dsh-skill-conflicts |
| **Messaging integrations** | Feishu / Lark file sending, reply delivery, and attachment metadata |
| **AI agent tooling** | Skill conflict detection, agent workflow tools |
| **Go** | Learning; interested in code review and CLI tooling |

> Understand the problem clearly first, then write a small version you can verify; improve a little with every iteration.

---

<sub>Get in touch: open an issue or discussion in any of my repositories.</sub>
