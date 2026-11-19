# agent-trials-method

AI Agent 评测数据集（基准测试）的介绍与使用指南。

> 说明：以下条目业界常统称「数据集」，严格说它们是「任务集 + 评测环境 + 打分规则」的组合，用于评测大模型（更准确地说是「AI Agent」）的能力。

## 数据集列表

| 编号 | 数据集 | 一句话简介 | 文档 |
|------|--------|-----------|------|
| 1 | Terminal-Bench | 终端智能体基准：在真实终端沙箱中从头到尾完成复杂工程任务 | [datasets/01-terminal-bench.md](datasets/01-Terminal-Bench.md) |
| 2 | DeepSWE | 编码智能体基准：113 个原创长周期任务，通过行为验证评估真实仓库修改 | [datasets/02-DeepSWE.md](datasets/02-DeepSWE.md) |
| 3 | Agents' Last Exam | 通用计算机使用智能体基准：在真实职业软件环境中完成 GUI 与 CLI 交织的长周期任务 | [datasets/03-Agents-Last-Exam.md](datasets/03-Agents-Last-Exam.md) |
| 4 | AutomationBench | 业务流自动化基准：在 47 个模拟 SaaS 应用中完成跨系统工作流并按终态断言评分 | [datasets/04-AutomationBench.md](datasets/04-AutomationBench.md) |
| 5 | HLE w/Tools | 学术天花板基准的开卷配置：共用 HLE 题库，允许联网搜索与代码执行 | [datasets/05-HLE-w-Tools.md](datasets/05-HLE-w-Tools.md) |
| 6 | GDPVal-AA v2 | 待补充 | - |
