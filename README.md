# Agent Skills

个人维护的 [Agent Skills](https://agentskills.io/) 集合。每个技能独立存放在 `skills/` 下，可通过 [skills CLI](https://github.com/vercel-labs/skills) 按需安装。

## 可用技能

| 技能 | 用途 |
| --- | --- |
| [中英双语写作与语感指南](skills/chinese-english-bilingual-writing-style-guide/SKILL.md) | 生成、改写和润色中文或英文文本，遵循各自语言的句法与节奏，减少空泛表达和术语堆砌。 |
| [多语言句法与语感基准](skills/syntactic-guide/SKILL.md) | 覆盖中文、英文、日文、文言文、法文和德文，描述施事、结构、修饰、事实边界与话题焦点的句法机制。 |

## 安装

从仓库安装技能：

```bash
npx skills@latest add MuZhou233/skills
```

安装指定技能：

```bash
npx skills@latest add MuZhou233/skills --skill chinese-english-bilingual-writing-style-guide
```

仅查看可安装的技能：

```bash
npx skills@latest add MuZhou233/skills --list
```

各技能的适用场景和具体规则见对应的 `SKILL.md`。

## 许可证

本项目使用 [MIT License](LICENSE)。
