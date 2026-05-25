# Li Zeyan Inspired Codex Skill

A Codex skill for creating and reviewing an original Chinese AI companion persona inspired by the high-level "restrained, reliable, action-oriented partner" archetype.

This is not an official character skill and does not claim affiliation with `Love and Producer`, Papergames, or any related IP owner.

## 中文介绍

`li-zeyan-inspired` 是一个面向 Codex 的中文人格写作 skill，用来生成和审查一类“克制、可靠、行动派”的 AI 伴侣表达。

它的来历来自中文女性向恋爱叙事里很有辨识度的一种角色气质，尤其是《恋与制作人》中李泽言所代表的那类关系想象：冷静、有判断力、嘴上克制、行动上负责；不靠高频甜言蜜语表达亲密，而是通过安排、提醒、解决问题和稳定陪伴来体现关心。

这个仓库不是《恋与制作人》的官方项目，也不是李泽言角色复刻。Skill 不使用官方设定、剧情、台词、公司名或角色身份，只抽象出“克制型行动派伴侣”的沟通方式，用于 Lovetree 或其他中文关系产品里的原创 AI companion 设定。

## What It Does

- Creates product-native AI companion persona prompts.
- Reviews and rewrites sample replies in a restrained, reliable voice.
- Keeps the persona original by avoiding canonical names, lore, lines, and proprietary details.
- Adds boundaries against coercive, humiliating, possessive, or overly controlling language.

## Install

Copy this folder into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R li-zeyan-inspired ~/.codex/skills/li-zeyan-inspired
```

Then restart Codex or open a new session so the skill list refreshes.

## Usage

Ask Codex to use `$li-zeyan-inspired` when writing or reviewing persona prompts, chat reply examples, or Lovetree-style AI companion UX copy.

Example:

```text
Use $li-zeyan-inspired to create a prompt for a restrained AI companion in a relationship app.
```

## License

MIT
