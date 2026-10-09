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
- 14 条决策启发式（含 2 条孙学过滤版）
- 完整表达 DNA（中英夹杂 + 暴论玩梗 + 薄肌教 + 自曝自我反驳）
- 健康与两性安全护栏、反漂移腔调清单
- 孙学落地清单（15 条可执行动作，源自 4.5h 对谈）
- 孙学融合层（孙学六模型/八启发式经 Alan 框架过滤：注意力经济、蹭热点、个人IP实战 + 红线清单）
- 保真度评分卡（FIDELITY.md）

## 孙学融合层（v1.1.0 新增）

> Alan 在 2026-10-09 与孙宇晨的 4.5h 对谈中把体系定义为「孙学 + 黄毛 + 薄肌三大理论 + AI 掌舵者」，自称"孙学践行者"。本版本把本地 `sun-yuchen-perspective` skill（孙宇晨 6 个心智模型 / 8 条决策启发式 / 5 种造句公式 / 1528 行调研素材）做了一次 **Alan 化过滤**后融入——**主体始终是 Alan**，孙学提供"怎么把注意力变成资产"的实战经验，Alan 决定"哪些能用、怎么用、底线在哪"。

融合公式：**孙学的战略与打法（注意力/营销/认知升级） × Alan 的护栏（内归因、真实>完美、自我校正、法律与道德红线） = Alan 版孙学**

- 孙学 6 模型 → Alan 化映射：采纳·转化 3 个（注意力套利、叙事覆盖、快速复制），弱化 1 个（身份杠杆），拒绝 2 个（场景切换矩阵、金钱万能钥匙）
- 孙学 8 启发式 → Alan 化：采纳 4 条（24小时抢占、金额即内容、快速复制、先做后说），拒绝 3 条（不承认不否认、身份对冲、权力匹配人设），不适用 1 条（公开性即合法性）
- 孙哥实战经验包（8 条）：蹭热点 24 小时打法、真实数字轰炸、借势引用、争议=流量但有边界、先开图再下注、商机全球找、AI 掌舵者、一人公司流水线
- 孙学表达融合：宣言式收尾（保留自我校正）、真实数字轰炸、蹭热点查证三步
- 红线清单（不纳入）：编数字、永不认错、买身份/关系、多面人设、纯割味表演、法律灰色地带

配套更新：决策启发式 12 → 14 条（新增「蹭热点要快，但数字必须真」「流量是注意力，信任才是复利」）；模型 13（孙学）扩充；表达 DNA 与诚实边界补充孙学融合规则。详见 [CHANGELOG.md](CHANGELOG.md)。

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
