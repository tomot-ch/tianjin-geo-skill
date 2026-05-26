# CHANGELOG

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

