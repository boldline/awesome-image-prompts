# 🤝 贡献指南

感谢你对 AI 作图 Prompt 库的贡献！请阅读以下指南确保一致性。

---

## 📋 贡献流程

1. **Fork** 本仓库
2. **创建分支**: `git checkout -b add/category-name-prompt`
3. **编写 Prompt** 并遵循模板格式（见 [TEMPLATES.md](TEMPLATES.md)）
4. **提交**: `git commit -m "add: [分类] prompt描述"`
5. **Push** 并创建 Pull Request

---

## ✅ Prompt 质量标准

每条 Prompt 必须满足：

- [ ] **经过实际测试** - 在至少一个 AI 模型上验证效果
- [ ] **包含示例图** - 附带生成的示例效果图
- [ ] **参数完整** - 注明推荐尺寸、风格、模型
- [ ] **英文撰写** - Prompt 文本使用英文
- [ ] **描述清晰** - 中文说明和使用建议完整

---

## 📁 文件组织规则

### 添加新 Prompt 到已有子分类

直接在对应 `.md` 文件末尾追加，遵循已有格式。

### 添加新子分类

1. 在对应分类文件夹中创建 `.md` 文件
2. 更新该分类的 `README.md` 子分类表格
3. 更新根目录 `README.md` 的 Prompt 数量

### 添加新顶级分类

请先开 Issue 讨论，获得同意后：

1. 创建 `{编号}-{英文名}/` 文件夹
2. 创建 `README.md` 和 `images/` 子目录
3. 创建子分类文件
4. 更新根目录 `README.md`

---

## 🖼️ 图片规范

- **格式**: PNG（优先）或 WebP
- **宽度**: 800-1200px
- **文件大小**: 单张 < 500KB
- **命名**: `{子分类}-{编号}.png`
- **存放位置**: 各分类文件夹的 `images/` 目录

---

## 💬 Commit Message 规范

```
add: [分类] 新增xxx prompt
fix: [分类] 修正xxx prompt的参数
docs: 更新README导航
style: 统一格式
```

---

## 🚫 请勿提交

- 含有版权争议的图片
- 未经测试的 Prompt
- NSFW 内容
- 大于 1MB 的单个文件

---

感谢你的贡献！🎉
