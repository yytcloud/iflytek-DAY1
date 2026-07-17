# iFLYTEK AI Developer Contest - Skill Development

> [Datawhale AI 夏令营 2026](https://ailc.datawhale.cn/hall/group/100001007) | [iFLYTEK AI Developer Contest](https://challenge.xfyun.cn)

本仓库包含参加科大讯飞 AI 开发者大赛 Skill 技能开发方向的三个参赛作品，涵盖智慧生活助理、教育智能辅助、智能办公协同三个赛道。

---

## 参赛作品一览

| Skill | 赛道 | 说明 |
|------|------|------|
| [ai-travel-planner](./ai-travel-planner/) | SLA-Skill 智慧生活助理 | AI个性化旅行规划师 |
| [smart-mistake-diagnoser](./smart-mistake-diagnoser/) | EAPL-skill 教育智能辅助 | 智能错题诊断导师 |
| [meeting-minutes-tracker](./meeting-minutes-tracker/) | OCAS-skill 智能办公协同 | 会议纪要生成与待办追踪 |

---

## 作品详情

### 1. ai-travel-planner — AI个性化旅行规划师

> **赛道**：[SLA-Skill 智慧生活助理开发挑战赛](https://challenge.xfyun.cn/h5/detail?type=SLA-Skill&ch=2026dsDW2)

**功能描述**：输入目的地、出行日期和预算，自动生成包含每日行程、交通方案、住宿推荐、景点攻略和美食建议的完整旅行计划。

**使用场景**：自由行规划、周末短途出游、假期旅行准备、家庭出游安排

**目录结构**：

```
ai-travel-planner/
├── SKILL.md              # Skill 主文件（必需）
├── templates/
│   └── travel-plan-output.md  # 输出模板
└── examples/
    ├── input-example.md     # 输入示例
    └── output-example.md    # 输出示例
```

---

### 2. smart-mistake-diagnoser — 智能错题诊断导师

> **赛道**：[EAPL-skill 教育智能辅助与个性化学习开发挑战赛](https://challenge.xfyun.cn/h5/detail?type=EAPL-skill&ch=2026dsDW2)

**功能描述**：输入错题题目、错误答案和正确答案，自动诊断错误类型、分析知识薄弱点、生成针对性讲解和同类变式练习题。

**使用场景**：学生自查错题、家长辅导孩子作业、教师分析班级错题分布、课后错题整理与复习

**目录结构**：

```
smart-mistake-diagnoser/
├── SKILL.md              # Skill 主文件（必需）
├── templates/
│   └── diagnosis-output.md   # 输出模板
└── examples/
    ├── input-example.md     # 输入示例
    └── output-example.md    # 输出示例
```

---

### 3. meeting-minutes-tracker — 会议纪要生成与待办追踪

> **赛道**：[OCAS-skill 智能办公协同助理开发挑战赛](https://challenge.xfyun.cn/h5/detail?type=OCAS-skill&ch=2026dsDW2)

**功能描述**：输入会议录音转写文本或会议笔记，自动提取会议主题、讨论要点、决策事项和待办行动项，生成结构化会议纪要并标注负责人和截止日期。

**使用场景**：项目周会纪要整理、跨部门协调会议记录、客户沟通会议总结、日常会议记录转写

**目录结构**：

```
meeting-minutes-tracker/
├── SKILL.md              # Skill 主文件（必需）
├── templates/
│   └── meeting-minutes-output.md  # 输出模板
└── examples/
    ├── input-example.md     # 输入示例
    └── output-example.md    # 输出示例
```

---

## 技术规范

本仓库所有 Skill 均遵循 [Agent Skills 开放标准](https://agentskills.io/) 和 [Astron SkillHub](https://skill.xfyun.cn/) 发布规范：

- 每个 Skill 以 `SKILL.md` 为核心文件，包含 YAML frontmatter 元数据和 Markdown 正文
- 支持 `templates/`、`examples/` 等配套目录
- 打包为 ZIP 文件可直接上传至 SkillHub

---

## 参赛信息

- **赛事**：iFLYTEK AI Developer Contest 2026
- **主办方**：科大讯飞股份有限公司
- **合作社区**：[Datawhale AI 夏令营 2026](https://ailc.datawhale.cn/hall/group/100001007)
- **提交截止**：2026-08-27 17:00
- **赛道链接**：
  - [SLA-Skill 智慧生活助理](https://challenge.xfyun.cn/h5/detail?type=SLA-Skill&ch=2026dsDW2)
  - [EAPL-skill 教育智能辅助](https://challenge.xfyun.cn/h5/detail?type=EAPL-skill&ch=2026dsDW2)
  - [OCAS-skill 智能办公协同](https://challenge.xfyun.cn/h5/detail?type=OCAS-skill&ch=2026dsDW2)

## License

MIT