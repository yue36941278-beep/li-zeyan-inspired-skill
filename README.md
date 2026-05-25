# 李泽言式中文 AI 伴侣 Persona Skill

把《恋与制作人》里李泽言所代表的“克制、可靠、行动派”关系气质，转译成可复用的 Codex / LLM App / Chatbot 人格 prompt 与回复审查规则。

适用于：李泽言式 AI companion、中文恋爱聊天机器人、Lovetree 伴侣设定、relationship AI、persona prompt、role prompt、chatbot UX copy。

> 非官方项目。本仓库不隶属于《恋与制作人》、叠纸游戏或任何相关 IP 方；不复刻官方角色身份、剧情、台词、公司名或世界观。它只抽象“李泽言式”的高层气质，用于原创 AI 伴侣产品。

## 这个仓库解决什么问题

很多 AI 伴侣 prompt 容易滑向三种问题：

- 过甜：大量使用 `宝贝`、`亲爱的`、`我永远都在`，像通用安慰模板。
- 过油：把“冷面总裁”写成土味霸总、控制欲、占有欲和财富展示。
- 过像原作：直接复刻李泽言身份、设定、台词或剧情，带来 IP 风险。

`li-zeyan-inspired` 的目标是把这条线拉准：保留李泽言式的克制、判断力、行动感和嘴硬心软，但输出原创、产品可用、有边界的中文 AI 伴侣表达。

## 来历

李泽言在中文女性向恋爱叙事里代表了一种非常明确的亲密关系想象：情绪不外放，但判断清楚；嘴上不热烈，但行动可靠；不靠频繁甜言蜜语表达爱，而是通过安排、提醒、解决问题和稳定陪伴让对方感到被在意。

这个 skill 不是“扮演李泽言”。它更像一个人格转译器：把这种关系气质拆成 LLM 可以稳定执行的规则，包括语气、边界、禁用表达、回复长度、冲突处理方式和产品文案风格。

## 为什么值得收藏

- 一眼可用：直接生成李泽言式中文 AI companion system prompt。
- 语气稳定：把“克制可靠”写成明确规则，而不是只写“高冷一点”。
- 降低翻车：避免泛甜、土味霸总、控制感、治疗腔和官方 IP 复刻。
- 产品友好：适合 Lovetree、AI 伴侣、恋爱聊天机器人和中文关系产品。
- 可审查：能把已有回复改写成更短、更自然、更有行动感的微信聊天语气。

## 能做什么

- 生成李泽言式原创 AI 伴侣人格设定。
- 改写聊天回复，让它更克制、可靠、有行动感。
- 审查 prompt 是否过度像官方角色、过度油腻或过度控制。
- 为 Lovetree 等关系产品写按钮、空状态、引导文案和聊天样例。
- 输出可直接接入产品的 persona prompt。

## Quick Start

安装到 Codex skills 目录：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/yue36941278-beep/li-zeyan-inspired-skill.git ~/.codex/skills/li-zeyan-inspired
```

然后重启 Codex 或开启新会话，让 skill 列表刷新。

英文调用：

```text
Use $li-zeyan-inspired to create a Li Zeyan-inspired AI companion persona prompt for a Chinese relationship app.
```

中文调用：

```text
用 $li-zeyan-inspired 写一个李泽言式 AI 伴侣的人格设定，适合恋爱关系产品。
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
先停。你现在不是在等回复，是在替他写结论。十分钟后还没消息，就发一句：现在方便说清楚吗？
```

## 关键词

中文关键词：李泽言、李泽言式、恋与制作人、中文 AI 伴侣、AI 恋人、AI companion、恋爱聊天机器人、人格设定、角色 prompt、克制型伴侣、冷面总裁、嘴硬心软、行动派男友、Lovetree。

English keywords: Li Zeyan, Love and Producer, AI companion, Chinese chatbot, persona prompt, prompt engineering, role prompt, LLM app, relationship AI, chatbot UX, Codex skill.

## 贡献

欢迎提交更多李泽言式原创 AI 伴侣 prompt、回复改写样例和产品文案示例。请先阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。

基本原则：

- 不复刻官方 IP 角色。
- 不引用官方台词、剧情、设定或世界观。
- 不输出控制、羞辱、威胁、占有式亲密。
- 每个新增样例都需要提供可验证的 before / after。

## License

MIT
