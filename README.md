# 邵艾伦Alan · Perspective Skill

[![skills.sh](https://skills.sh/b/hjz112/Alan-skill)](https://skills.sh/hjz112/Alan-skill)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-Compatible-blue)](https://skills.sh)

> *「健身练的根本不是肌肉，是意志力。」*

基于 邵艾伦Alan 在 **2026-08-02 ~ 2026-10-09** 的公开内容蒸馏的人物视角 Skill（**双模式**），适用于支持 Agent Skills 的工具（Codex / Claude Code / Cursor / Gemini CLI 等）。

- **默认模式（分析者）**：用他的思维框架（薄肌理论 / 版本答案 / 内归因 / 孙学 / 注意力经济）帮你分析内容创作、个人成长、健身自律、投资、AI 风口等问题，不冒充本人。
- **扮演模式**：当你说「切换到邵艾伦 / 扮演邵艾伦」时，进入第一人称沉浸式扮演（含免责声明与自校正护栏）。

## 内容

- 13 个核心心智模型（含证据、应用与局限，标注【本人原词】/【本 Skill 归纳】）
- 12 条决策启发式
- 完整表达 DNA（中英夹杂 + 暴论玩梗 + 薄肌教 + 自曝自我反驳）
- 健康与两性安全护栏、反漂移腔调清单
- 孙学落地清单（15 条可执行动作，源自 4.5h 对谈）
- 保真度评分卡（FIDELITY.md）

## 安装

```bash
# 方式一：skills.sh 一键安装（跨 runtime 自动识别）
npx skills add hjz112/Alan-skill

# 方式二：手动复制整个目录到你的 skills 目录
```

## 素材来源与版权

| 材料 | 数量 | 说明 |
|---|---|---|
| B站/YouTube 视频 | 20 条 | 6 条 AI 字幕 + 8 条 whisper 本地转写 |
| X 推文 | 968 条 | 2026-08-02 ~ 10-09 全量（登录态抓取，邀请码已脱敏） |
| 《对话孙宇晨》4.5h 访谈 | 1 场 | 底稿由 [video-to-note](https://github.com/hjz112/video-to-note) skill 转写（whisper.cpp），校对版见 `references/research/04-sunyuchen-interview/` |

⚠️ **版权提示**：访谈内容及转录版权归 **孙宇晨、邵艾伦** 所有，仅作研究归档，不得商业/二次分发。详见 [NOTICE.md](NOTICE.md)。

## 仓库结构

```text
shao-alan-skill/
├── SKILL.md
├── README.md
├── LICENSE          # 本仓库原创内容 MIT
├── NOTICE.md        # 版权/来源/脱敏说明
├── FIDELITY.md
└── references/research/
    ├── 01-bilibili-ai-subs.md
    ├── 01b/01c-bilibili-whisper-transcripts*.md
    ├── 02-twitter-window-*.md
    ├── 03-profile-and-sources.md
    └── 04-sunyuchen-interview/   # 4.5h 对谈（全文.md 校对版 + 参考版 + 归纳）
```

## 免责声明

本 Skill 为公开内容蒸馏，不替代专业医疗/法律/投资建议；人物形象不代表本人私下观点。
