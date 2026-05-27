# Codex 增量入库 Prompt

你现在要在当前仓库 `tomot-ch/tianjin-geo-skill` 中合并一个增量训练包。

## 背景

当前仓库已经是一个天津高考地理推理系统，不是空项目。已有结构包括：

- `SKILL.md`
- `chains/`
- `extracted/`
- `papers/`
- `references/`
- `templates/`
- `prompts/`
- `examples/`

这次不要重建项目，也不要覆盖已有真题蒸馏文件。

## 资料包

我会上传一个 zip：

```text
tianjin_geo_skill_increment_pack.zip
```

请你解压后，将其中内容合并到当前仓库。

## 合并规则

1. 保留原仓库所有文件；
2. 将新文件按目录放入对应位置；
3. 新文件均带有 `core_` 前缀，原则上不会与旧文件冲突；
4. 如出现同名文件，不要覆盖，先报告冲突；
5. 合并后检查 Markdown 链接和目录结构；
6. 更新根目录 `README.md`，新增一节“基础知识体系补强”；
7. 更新根目录 `SKILL.md` 的“推荐读取顺序”或“当前专题链索引”，加入以下文件：
   - `references/core_高中地理核心知识体系.md`
   - `references/core_知识点到答题链映射.md`
   - `chains/core_自然地理基础链.md`
   - `chains/core_人文地理基础链.md`
   - `chains/core_生态环境与国家安全链.md`
   - `templates/core_基础知识调用规则.md`

## README 新增内容建议

请在 README 中新增：

```markdown
## 基础知识体系补强

本仓库新增 `core_` 系列基础知识文件，用于补足真题蒸馏之外的底层知识框架。使用时不直接照搬知识点，而是按照：

材料条件 → 地理含义 → 因果链 → 天津卷答案话术

的方式，把基础知识转化为可得分答案。

新增文件包括：

- `references/core_高中地理核心知识体系.md`
- `references/core_知识点到答题链映射.md`
- `chains/core_自然地理基础链.md`
- `chains/core_人文地理基础链.md`
- `chains/core_生态环境与国家安全链.md`
- `templates/core_基础知识调用规则.md`
- `examples/core_基础知识调用示例.md`
```

## SKILL.md 更新建议

请在 `SKILL.md` 中补充一段：

```markdown
## 基础知识调用规则

当真题链条、母题库或年份蒸馏不足以覆盖题目时，调用 `core_` 系列基础知识文件进行补充。基础知识只作为底层依据，不能直接整段照搬进答案。必须经过：

知识点 → 材料条件 → 地理含义 → 因果链 → 天津卷答案话术

的转化过程。
```

## 输出要求

完成后请输出：

1. 新增文件清单；
2. 修改文件清单；
3. 是否存在冲突；
4. 更新后的推荐读取顺序；
5. 后续如何继续训练这个 skill。
