# CHANGELOG

## 2026-05-27 真实讲题记录双线蒸馏机制

### 新增

- 新增真实讲题记录双线蒸馏机制，区分“讲题风格 / 口语化”和“知识点 / 题型积累”两条线。
- 新增个人口语讲题风格库 `references/my_oral_style_summary.md`。
- 新增口语话术库 `references/my_oral_phrase_bank.md`。
- 新增口语转书面语模板 `templates/oral_to_written_template.md`。
- 新增真实讲题案例目录说明 `examples/my_teaching_cases/README.md`。
- 新增知识点积累中转库 `references/case_knowledge_accumulation.md`。
- 新增双线蒸馏 prompt `prompts/distill_chat_records_dual_line.md`。
- 新增真实讲题案例索引 `examples/my_teaching_cases/case_index.md`。
- 新增四个初始案例：能源结构、巴伦支海热量收支、AMOC、陕西韭园水土流失。

### 修改

- 更新 `SKILL.md`，加入真实讲题材料双线蒸馏说明和输出模式要求。
- 更新 `README.md`，加入真实聊天记录双线蒸馏工作流。

### 注意

- 四个初始案例为整理后的训练样例，不保存未经匿名化的聊天原文。
- 已落实“韭园是陕西，不是尼泊尔”，相关内容按黄土高原水土流失分析。

## 2026-05-27 个人口语讲题风格层

### 新增

- 新增 `references/my_oral_style_summary.md`，用于沉淀老师个人读题、拆材料、串因果链、纠错和天津卷提醒方式。
- 新增 `references/my_oral_phrase_bank.md`，用于整理服务讲题的开头、过渡、纠错、提醒和总结话术。
- 新增 `templates/oral_teaching_template.md`，用于生成“设问—材料—地理含义—因果链—易错点—标准答案”的口语讲题稿。
- 新增 `templates/oral_to_written_template.md`，用于把口语解释转换成天津卷规范表达。
- 新增 `examples/my_teaching_cases/README.md`，说明真实讲题案例如何匿名化入库。
- 新增 `prompts/distill_chat_records.md`，用于后续蒸馏真实聊天记录和语音转文字。
- 新增 `prompts/generate_oral_explanation.md`，用于根据题目生成老师风格口语讲题稿。

### 修改

- 更新 `SKILL.md`，加入 `standard_written_answer` 与 `oral_teaching_explanation` 两种输出模式。
- 更新 `skills/teaching_style.md`，加入个人口语风格调用规则，强调模仿教学动作而非口头禅。
- 更新 `templates/student_explanation_template.md`，加入个人口语版输出要求和“考试里写成……”落答案规则。
- 更新 `README.md`，补充个人口语风格层说明、使用示例和隐私处理要求。

### 注意

- 当前个人口语内容仅做结构补强和示例占位，尚未接入真实聊天记录。
- 后续真实聊天记录必须匿名化，只保留讲题流程、常用话术、纠错逻辑和口语转书面语规则。

## 2026-05-26 本地功能补全

### 新增

- 新增 `references/knowledge_framework.md`，整理天津卷题型入口、能力分层、专题框架和答案生成规则。
- 新增 `references/answer_templates.md`，汇总原因、影响、措施、意义、区位、图表、分主体等模板。
- 新增 `references/tianjin_answer_style.md`，沉淀天津卷答案句式、可迁移表达和失分表达替换。
- 新增 `prompts/` 目录，包含单题分析、材料蒸馏、学生答案诊断、天津答案生成和仓库迭代 prompt。
- 新增 `extracted/ecology_questions.md`，补齐生态题型母题入口。

### 修改

- 更新 `README.md`，补充 prompts 目录说明、本轮结构补强说明和母题库入口。
- 更新 `SKILL.md`，补充 references、prompts、extracted 索引和入库分层规则。
- 补全 `extracted/` 下农业、城市、气候、综合、地貌、工业、港口交通等母题归纳。
- 补全 `chains/` 下农业、城市、气候、生态、地貌、工业、港口交通等基础因果链。
- 补全 `examples/choice_question_case.md`、`examples/big_question_case.md`、`examples/student_answer_diagnosis_case.md`。

### 未完成

- 未执行远端 pull/push：当前网络无法连接 `github.com:443`，且本地目录未配置 `origin`。
- 2025 年内容仍标记为扫描版初步蒸馏，后续需要高清解析卷复核。
- `papers/2016` 至 `papers/2019` 暂未按 2020 年后格式完成蒸馏，旧年份仅适合作低权重参考。

### 下一轮建议

- 先恢复 GitHub 连接并与 `https://github.com/tomot-ch/tianjin-geo-skill.git` 对齐。
- 选择一个高权重专题继续细化，例如生态补偿、城市更新、地球运动或能源安全。
- 用高清 2025 解析卷复核题干、图中文字、选项和答案细节。
- 若需要处理旧年份，优先从 2019 年开始，且不要让旧题规则覆盖 2023 年后的风格。
