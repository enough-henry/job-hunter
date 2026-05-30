# 🎯 求职全能助手 · Job Hunter

> 一个覆盖求职全流程的 Claude Code Skill —— 从简历分析到薪资谈判，帮你搞定每一次跳槽。

[![MIT License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-blue)](https://claude.ai/code)

---

## 📖 这是什么？

**求职全能助手** 是一个为 [Claude Code](https://claude.ai/code) 设计的 Skill（技能包），覆盖求职全过程：

```
简历优化 → JD 分析 → 公司匹配 → 话术准备 → 面试准备 → Offer 对比 → 薪资谈判
```

它不是那种给鸡汤和建议的"求职顾问"——它会帮你做结构化的分析、给出可操作的建议，甚至是逐轮的面试模拟练习。

## 🚀 快速开始

### 安装

```bash
# 方案一：克隆到 skills 目录（推荐）
git clone https://github.com/enough-henry/job-hunter.git ~/.claude/skills/job-hunter

# 方案二：手动下载
# 下载 zip 包，解压到 ~/.claude/skills/job-hunter/
```

### 使用

在 Claude Code 中直接说：

> "帮我分析一下这份简历"
> "看看这个 JD 合不合适我"
> "模拟一场面试"
> "帮我比较这两个 Offer"

AI 会自动识别你的需求并调用对应的模块。

## 🧩 模块一览

| 模块 | 文件 | 有什么用 |
|------|------|---------|
| 🔧 ATS 优化 | `00-ats-optimization.md` | 投大厂前先过一遍，别让机器筛掉 |
| 📄 简历分析 | `01-resume-analysis.md` | 6 维评分 + STAR 改写 + ATS 检查 |
| 🔍 JD 分析 | `02-jd-analysis.md` | 解码 JD 背后的隐藏信息 |
| 🏢 公司匹配 | `03-company-matching.md` | 找对口的公司在哪投 |
| 💬 求职话术 | `04-messaging.md` | HR 私信、内推请求、面试跟进 |
| 🎤 面试准备 | `05-interview-prep.md` | 公司调研 + 预测问题 + 追问模拟 |
| 📈 技能差距 | `06-skill-gap.md` | 转行/晋升缺什么、怎么学 |
| ⚖️ Offer 对比 | `07-offer-comparison.md` | 加权决策矩阵，理性选 Offer |
| 💰 薪资谈判 | `08-salary-negotiation.md` | 分场景话术，不卑不亢谈薪资 |

## ✨ 特色功能

- **多维简历评分** —— 内容力、成果量化、关键词匹配、职业轨迹、格式规范、ATS 友好度，6 个维度加权评分
- **隐藏信号解码** —— "抗压能力"=加班多？"全栈"=团队小？JD 字面背后的真实含义
- **加权决策矩阵** —— 你定权重，AI 替你算加权分，理性不纠结
- **Mock 面试模式** —— 说一句"模拟面试"，AI 秒变面试官，压力拉满
- **追问预演** —— 不只是问问题，还预判面试官接下来 2-3 轮追问
- **ATS 兼容扫描** —— 专治"简历不错但 HR 就是没看到"的怪病

## 📦 项目结构

```
job-hunter/
├── SKILL.md                      # 入口文件（技能声明 + 模块索引）
├── README.md                     # 本文件
├── LICENSE                       # MIT 协议
├── CONTRIBUTING.md               # 贡献指南
├── .gitignore
│
├── 00-ats-optimization.md        # 模块 0：ATS 简历优化
├── 01-resume-analysis.md         # 模块 1：简历分析
├── 02-jd-analysis.md             # 模块 2：JD 深度分析
├── 03-company-matching.md        # 模块 3：公司匹配
├── 04-messaging.md               # 模块 4：求职话术
├── 05-interview-prep.md          # 模块 5：面试准备
├── 06-skill-gap.md               # 模块 6：技能差距分析
├── 07-offer-comparison.md        # 模块 7：Offer 对比
└── 08-salary-negotiation.md      # 模块 8：薪资谈判
```

## 🤝 如何贡献

欢迎提 Issue 或 PR！详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

简单来说：
- 发现模块不准确？提 Issue
- 有新的求职场景想加？提 Issue or PR
- 想一起完善文档？PR 走起

## 📜 License

[MIT](LICENSE) © enough-henry

## ⭐ Star History

如果这个项目帮到了你，欢迎点个 ⭐，让更多人看到。
