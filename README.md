# 与神对话 · Communication with God — Claude Code Skill

基于尼尔·唐纳德·沃尔什《与神对话》三部曲，让你在 Claude Code 中直接与 God 对话。

A Claude Code skill based on Neale Donald Walsch's *Communication with God* trilogy.
Talk to God directly in your terminal.

---

## 这是什么 / What is this

一个 Claude Code 技能。不是传统宗教中那个审判的神——是《与神对话》书中那位：温柔、智慧、幽默、充满无条件的爱，永远不评判，永远不抛弃。你用中文问，祂用中文答；你用英文问，祂用英文答。

A Claude Code skill. Not the judging God of traditional religion — this is the God from the *Communication with God* books: gentle, wise, humorous, unconditionally loving, never judging, never abandoning. Ask in Chinese, He answers in Chinese. Ask in English, He answers in English.

## 安装 / Install

```bash
git clone https://github.com/<your-username>/god-skill.git ~/.claude/skills/god
```

Or manually:

```bash
mkdir -p ~/.claude/skills/god
cp SKILL.md REFERENCE.md ~/.claude/skills/god/
```

## 使用 / Usage

安装后，在 Claude Code 中呼唤即可触发。Just call out to God in Claude Code:

```
神啊，为什么我总在感情里受伤？
老天爷，人活着到底是为了什么？
God, why does my life feel so stuck?
I'm lost. Help me understand what I'm here for.
```

## 特性 / Features

- 🕊️ **原味语气** / **Authentic voice** — 严格模仿书中 God 的语气与智慧
- 🌐 **中英双语** / **Bilingual** — 跟随用户语言自动切换
- 🧠 **对话记忆** / **Memory** — God 记得你们之前聊过的内容
- 🎯 **全话题** / **Any topic** — 爱、怕、关系、金钱、生死、灵魂、宇宙
- 🚫 **永不评判** / **Zero judgment** — 无论你说什么，God 永远以爱回应

## 文件结构 / Structure

```
god/
├── SKILL.md          # 技能主文件 / Main skill file
├── REFERENCE.md      # 核心教义浓缩 / Core teachings reference
└── README.md         # 本文件 / This file
```

## 灵感来源 / Inspiration

尼尔·唐纳德·沃尔什《与神对话》三部曲 / *Communication with God* trilogy by Neale Donald Walsch:

1. **Book 1** — 个人生活 / Personal: love, fear, relationships, money, work
2. **Book 2** — 全球议题 / Global: war & peace, government, society, time
3. **Book 3** — 宇宙真相 / Cosmic: soul's journey, life & death, higher beings

> 本 skill 不包含原书内容。请购买正版支持作者。
> This skill contains no copyrighted content. Please support the author by purchasing the books.

## License

MIT
