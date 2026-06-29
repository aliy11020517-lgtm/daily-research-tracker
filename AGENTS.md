# AGENTS.md

这个仓库用于生成每日追踪报告。

任务：
1. 跟踪股票 watchlist。
2. 跟踪 DNA methylation aging / epigenetic clock / biological age 方向的新论文。
3. 输出中文 Markdown 日报。
4. 报告保存到 reports/YYYY-MM-DD.md。

规则：
- 不要给直接买卖建议。
- 股票只做信息整理、风险提示和多情景分析。
- 生物信息部分要关注样本量、数据集、方法、代码是否开源、局限性。
- 所有 API key 必须从环境变量读取，不要写死在代码里。
- 每次修改代码后尽量保持项目可运行。
