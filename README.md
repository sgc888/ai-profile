# 我的 AI 个人档案

> 一份让 AI 在 30 秒内读懂我的「自我说明书」。
> DeepSeek / ChatGPT / Claude / Gemini / Kimi……任何 AI 助手，在回答我之前请先读 [ai-profile.md](ai-profile.md)。

## 这是什么

`ai-profile.md` 写清楚了：

- 我是谁、我在做什么
- 我的技能与知识盲区
- **我使用 agent 的习惯与要求**（方案确认制、输出风格、学习模式——本档案核心）
- 我的雷区（AI 请勿踩）

放在 GitHub 上的三个好处：

1. **一个永久可分享的链接**：raw 链接发过去，支持联网读网页的 AI 可直接读取；
2. **版本管理**：人会变，档案随时更新。git 记录每一次变化，链接不变、内容常新；
3. **一生的编年史**：每次修改都记进 [CHANGELOG.md](CHANGELOG.md)，几十年后回看，它记录的不只是档案，还有你走过的路。

## 怎么把档案喂给 AI

- **直接粘贴**（最通用，任何工具都行）：新对话开场白 →「请先阅读以下个人档案，之后按档案要求与我协作：（粘贴 ai-profile.md 全文）」
- **发 Raw 链接**（最优雅）：「请先读取这个链接里的个人档案，再回答我后续的问题：<下方链接>」
- **设为自定义指令**（一劳永逸）：ChatGPT 的 Custom Instructions / Claude 的 Projects / 各工具的「系统提示词 · 关于我 · 记忆」设置里粘贴档案全文

> 大陆网络访问 raw 链接不稳时，可用 jsDelivr 镜像：`https://cdn.jsdelivr.net/gh/SGC888/ai-profile@main/ai-profile.md`（缓存有几小时延迟）

## 目录结构

| 文件 | 说明 |
| --- | --- |
| `ai-profile.md` | 档案正文（核心文件） |
| `CHANGELOG.md` | 档案更新日志（一生的编年史） |
| `.github/workflows/` | 每年自动提醒回顾档案的 Action |
| `.gitignore` | 忽略系统杂项文件 |

## Raw 链接

```text
https://raw.githubusercontent.com/SGC888/ai-profile/main/ai-profile.md
```

## 隐私提醒

⚠️ 仓库公开，档案里**不要**写：手机号、住址、证件号、密码、公司机密。
写到「职业方向 + 兴趣」这个粒度，就足够 AI 了解你了。
