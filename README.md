# 经济学实证论文协作 Skill

把经济学实证论文拆成可验收的阶段：用小样本预研筛选选题，用证据包交接研究，用独立审阅检查稿件。适合课程论文、参赛稿和实证研究项目，没有固定计量方法或模型供应商要求。

- [SKILL.md](SKILL.md)：Codex 入口与任务分流。
- [研究](references/research.md)：项目启动、选题、预研、聚焦文献、冻结设计与复算。
- [交接与返修](references/handoff.md)：写作者交接、证据审核、意见分流。
- [审阅与定稿](references/review-and-release.md)：绘图、盲审、中文表达、合稿及提交准备。
- [真实 Prompt 脱敏原文](references/real-prompt-examples.md)：给各子对话的实际派发指令，供参考与选择。

各步骤有可复制的 Prompt，`{{字段｜填写说明}}` 和 `{{字段}}` 换成当前项目的实际信息。流程文档里的「改编示例」和通用模板与另附的历史原文分开。历史样例仅收录实际派给子对话的指令，标明接收方与脱敏位置，不用用户原话或待转交草稿补位。首次调用新项目，Skill 会问后续是否重点参考这些样例；不选也能直接用模板。第三方项目在对应步骤首次出现处附链接，仓库不分发它们的代码或原文，也不会自动安装。

## 在 Codex 中使用

把本仓库整个文件夹放到项目的 `.agents/skills/economics-paper-workflow-skill/`，保持目录结构。打开 Codex，选择或输入 `$economics-paper-workflow-skill`，再说明当前任务。也可以直接在网页阅读各步参考文件。参见 [Codex 官方技能加载说明](https://learn.chatgpt.com/docs/build-skills#where-codex-loads-local-skills)。

试用指令：

> 用 $economics-paper-workflow-skill 帮我筛选三个劳动经济学题目。我的数据附件只有地区月度汇总，暂时没有个体记录；请明确哪些题能支持、先跑哪张表、什么结果会让我放弃选题。

维护：[@GarryKin824](https://github.com/GarryKin824)。
