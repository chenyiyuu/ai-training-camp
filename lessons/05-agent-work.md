# Lesson 05 — Agent / Work 实战

- 状态:进行中
- 记录日期:2026-10-13
- 涉及工具:Trae Agent 模式

## 学习目标

- 理解 Agent 模式与单次问答的区别:目标驱动、多步规划、工具调用、自我校验
- 实践「给出目标 → Agent 自主拆解 → 在分支上完成 → 发起 PR」的完整闭环

## 实战计划

- [x] 让 Agent 自行检查仓库现状并设计结构调整
- [x] 由 Agent 在新分支上完成 README、课程目录、课程模板与学习进度说明
- [x] 由 Agent 校验内容一致性并发起 Pull Request
- [ ] 人工 review PR 并合入(本课完成的标志)

## 阶段性收获

- 给 Agent 的指令越接近「目标 + 约束」,越少需要逐步干预
- 「不直接改 main、先分支再 PR」是保证可控性的关键约束
- 本仓库的本次结构化整理,本身就是本课实战的一部分

## 相关链接

- 前序课程:[04-project-weekly-report-skill.md](04-project-weekly-report-skill.md)
- 本课实战 PR:见仓库 Pull Requests 列表

> 本课仍在进行中,合入 PR 后补充完整记录。
