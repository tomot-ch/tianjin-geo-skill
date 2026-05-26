# Tianjin Geo Skill

天津高考地理答题 Skill。

用于：

- 天津高考地理大题分析
- 标准答案生成
- 学生失分分析
- 讲题稿生成
- 地理答题模板生成

## 安装

克隆仓库：

```bash
git clone https://github.com/yourname/tianjin-geo-skill.git
```

复制到 Codex Skills：

```bash
mkdir -p ~/.codex/skills
cp -r tianjin-geo-skill ~/.codex/skills/
```

## 使用示例

```text
请使用 tianjin-geo-skill 分析这道天津高考地理大题。
输出：
1. 标准答案
2. 讲题稿
3. 学生失分点
4. 可迁移模板
```

## 当前版本

v0.1

当前版本包含：

- 基础题型框架
- 天津地理答题语言
- 基础案例
- Skill Prompt

## 后续计划

- 增加历年天津真题案例
- 增加判分逻辑
- 增加学生答案诊断
- 增加自动题型识别
- 增加图片解析
