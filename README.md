# 中文 AI 伴侣人格 Skill：Li Zeyan Inspired

一个面向 Codex / LLM App / Chatbot 的中文 AI 伴侣人格 skill，用来生成和审查“克制、可靠、行动派、有边界”的关系型 AI companion 表达。

适用于：Lovetree、AI 伴侣产品、恋爱聊天机器人、中文 prompt engineering、persona design、role prompt、chatbot UX copy。

> 非官方项目。这个仓库不隶属于《恋与制作人》、叠纸游戏或任何相关 IP 方，也不复刻官方角色设定、剧情、台词或世界观。

## 来历

`li-zeyan-inspired` 的气质来源于中文女性向恋爱叙事里一种很有辨识度的角色类型，尤其是《恋与制作人》中李泽言所代表的关系想象：冷静、有判断力、嘴上克制、行动上负责。

这类伴侣人格不靠高频甜言蜜语表达亲密，而是通过安排、提醒、解决问题和稳定陪伴来体现关心。它适合被抽象成一种原创的 AI companion archetype：克制型行动派伴侣。

这个 skill 只保留可迁移的人格结构，不使用官方姓名身份、剧情、公司名、台词或 proprietary lore。目标是帮助产品团队写出“有张力但不油腻，有保护感但不控制”的中文 AI 伴侣表达。

## 为什么值得收藏

- 可直接用于中文 AI companion / chatbot 的 system prompt 设计。
- 提供“克制型行动派伴侣”的稳定语气规则，避免泛甜、油腻和霸总土味。
- 可审查已有回复，把过度治疗腔、控制感、占有欲表达改成更自然的微信聊天语气。
- 适合扩展成中文 AI 伴侣人格库，例如温柔陪伴型、猫系傲娇型、理性分析型等。

## 能做什么

- 生成原创中文 AI 伴侣人格设定。
- 改写单句或多轮聊天回复。
- 审查 prompt 是否过度像官方角色、过度油腻、过度控制。
- 为 Lovetree 或其他关系产品写按钮、空状态、引导文案和聊天样例。
- 输出可直接接入产品的 persona prompt。

## Quick Start

安装到 Codex skills 目录：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/yue36941278-beep/li-zeyan-inspired-skill.git ~/.codex/skills/li-zeyan-inspired
```

然后重启 Codex 或开启新会话，让 skill 列表刷新。

使用时可以这样说：

```text
Use $li-zeyan-inspired to create a restrained AI companion persona prompt for a Chinese relationship app.
```

中文也可以：

```text
用 $li-zeyan-inspired 写一个克制型行动派 AI 伴侣的人格设定，适合恋爱关系产品。
```

## 示例

更多示例见 [examples/reply-rewrites.md](examples/reply-rewrites.md)。

输入：

```text
他为什么还不回我？是不是不在乎我？
```

不推荐：

```text
宝贝别想太多啦，他一定很爱你，我会一直陪着你。
```

推荐：

```text
先别替他下结论。等十分钟，如果还没回，就发一句清楚的话确认情况。
```

## 关键词

中文关键词：中文 AI 伴侣、AI 恋人、AI companion、恋爱聊天机器人、人格设定、角色 prompt、李泽言式、恋与制作人、克制型伴侣、冷面总裁、嘴硬心软、行动派男友、Lovetree。

English keywords: AI companion, Chinese chatbot, persona prompt, prompt engineering, role prompt, LLM app, relationship AI, chatbot UX, Codex skill.

## 贡献

欢迎提交更多原创中文 AI 伴侣人格模板和回复样例。请先阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。

基本原则：

- 不复刻官方 IP 角色。
- 不引用官方台词、剧情、设定或世界观。
- 不输出控制、羞辱、威胁、占有式亲密。
- 每个新人格模板都需要提供可验证的 before / after 示例。

## License

MIT
