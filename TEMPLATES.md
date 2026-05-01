# 📝 模板参考

本文档提供项目中各类文件的标准模板，确保一致性和可维护性。

---

## 1. 分类 README.md 模板

```markdown
# {emoji} {分类中文名}

> 一句话介绍该分类的用途和适用场景。

---

## 📋 子分类一览

| 文件 | 名称 | 说明 | Prompt 数量 |
|------|------|------|:---:|
| [headshot.md](headshot.md) | 证件照/头像 | 职业头像、社交头像 | 5 |
| [full-body.md](full-body.md) | 全身照 | 站姿、坐姿、运动 | 5 |
| ... | ... | ... | ... |

---

## 🎯 适用场景

- 场景 1 描述
- 场景 2 描述
- 场景 3 描述

---

## 💡 通用技巧

1. **光线控制**: 描述该类别常用的光线技巧
2. **构图建议**: 描述推荐的构图方式
3. **风格关键词**: 列出该类别常用风格词

---

## 🔗 相关分类

- [相关分类1](../xx-category/) - 说明关联性
- [相关分类2](../xx-category/) - 说明关联性

---

## 📚 参考来源

- [来源1](URL) - 说明
- [来源2](URL) - 说明
```

---

## 2. 子分类 Prompt 集合文件模板

```markdown
# {emoji} {子分类中文名}

> 该子分类的简要说明，包含适用场景和典型使用方法。

**所属分类**: [{父分类名}](README.md)  
**Prompt 数量**: X 条  
**难度等级**: ⭐ 入门 / ⭐⭐ 进阶 / ⭐⭐⭐ 高级

---

## 目录

- [Prompt 1: 名称](#prompt-1-名称)
- [Prompt 2: 名称](#prompt-2-名称)
- ...

---

## Prompt 1: 名称

> 一句话描述这条 Prompt 的效果

**Prompt:**

​```text
A detailed English prompt text here. Use descriptive language 
covering subject, composition, lighting, style, mood, and 
technical details...
​```

**示例效果：**

![示例](images/subcategory-01.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1024×1024 | 正方形，适合社交媒体 |
| 风格 | Photorealistic | 写实风格 |
| 模型 | GPT-Image-2 | 推荐模型 |
| 质量 | High | 高质量输出 |
| 种子 | - | 随机 |

**变体建议：**

- 替换 `[subject]` 为其他主题
- 将 `soft lighting` 改为 `dramatic lighting` 获得不同氛围
- 添加 `--ar 16:9` 适配横屏

**标签**: `#photorealistic` `#portrait` `#studio`

---

## Prompt 2: 名称

> ...（同上格式重复）

---

## 🔗 相关推荐

- [相关子分类1](related-file.md) - 说明
- [相关子分类2](../other-category/file.md) - 说明
```

---

## 3. 单条 Prompt 条目最小格式

适用于快速添加新 Prompt 时的最小必要格式：

```markdown
### Prompt 名称

> 用途说明

**Prompt:**

​```text
English prompt text...
​```

**参数说明：**

| 参数 | 推荐值 |
|------|--------|
| 尺寸 | 1024×1024 |
| 风格 | Style name |
| 模型 | Model name |
```

---

## 4. 命名规范

### 文件夹命名

- 格式: `{两位编号}-{英文名}`
- 示例: `01-portrait`, `11-technical-diagram`
- 使用小写字母和连字符

### 文件命名

- 格式: `{英文描述}.md`
- 示例: `headshot.md`, `full-body.md`, `cloud-infra.md`
- 使用小写字母和连字符，不使用下划线

### 图片命名

- 格式: `{子分类名}-{编号}.png`
- 示例: `headshot-01.png`, `architecture-03.png`
- 统一使用 PNG 格式，宽度不超过 1200px

---

## 5. 标签体系

每条 Prompt 可附带以下标签：

**风格标签**: `#photorealistic` `#illustration` `#3d-render` `#watercolor` `#pixel-art` `#flat-design` `#minimalist` `#vintage` `#cyberpunk` `#anime`

**用途标签**: `#commercial` `#personal` `#social-media` `#print` `#web` `#presentation`

**技术标签**: `#high-detail` `#wide-angle` `#close-up` `#bird-eye` `#isometric` `#dark-theme` `#light-theme`

