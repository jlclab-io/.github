# JLCLAB · GitHub Organization Profile

This repository contains the GitHub organization profile and related static assets for **[JLCLAB](https://github.com/jlclab-io)**.

本仓库用于维护 **JLCLAB GitHub 组织主页**及其静态资源，统一管理主页介绍、图片、动图和图标等内容。

## 📁 Directory Structure

```text
.github/
├── README.md                  # 仓库说明文档
└── profile/
    ├── README.md              # GitHub 组织主页
    └── assets/
        ├── gifs/              # GIF 动画、功能演示
        ├── icons/             # SVG 图标
        └── images/            # 图片、Banner、Logo
```

### 文件说明

| 路径 | 用途 |
|---|---|
| `README.md` | 仓库用途、目录结构及维护规范 |
| `profile/README.md` | GitHub 组织 Overview 页面展示内容 |
| `profile/assets/gifs/` | 产品演示、功能展示等 GIF 动画 |
| `profile/assets/icons/` | SVG 图标及其他小型矢量资源 |
| `profile/assets/images/` | 品牌 Logo、Banner、产品图片及其他静态图片 |

## 📦 Asset Guidelines

### 1. 资源存放

- 所有用于组织主页的静态资源统一存放在 `profile/assets/` 下。
- 按照资源类型分别存放到 `gifs/`、`icons/` 和 `images/` 目录。
- 本仓库不存放项目源码、构建产物或与组织主页无关的文件。
- 各开源项目专属的文档和资源原则上存放在对应项目仓库中。

### 2. 文件命名

统一使用小写英文字母、数字和连字符（`kebab-case`），文件名应清晰表达资源用途。

推荐示例：

```text
jlclab-banner.png
jlclab-logo.svg
candis-board.png
candis-demo.gif
github-icon.svg
```

避免使用空格、中文、无意义编号或临时文件名。

### 3. 文件格式

| 类型 | 推荐格式 | 说明 |
|---|---|---|
| Logo / Icon | SVG、PNG | 优先使用 SVG |
| Banner / 图片 | PNG、WebP、JPG | 根据图片内容选择 |
| 动画演示 | GIF | 上传前适当压缩 |
| 产品展示 | WebP、PNG、JPG | 保证清晰度并控制体积 |

优先使用经过压缩的资源，避免过大的文件影响主页加载速度。

### 4. 资源引用

在 `profile/README.md` 中，优先通过相对路径引用本仓库资源。

Markdown 示例：

```markdown
![JLCLAB Banner](./assets/images/jlclab-banner.png)

![Candis Demo](./assets/gifs/candis-demo.gif)
```

HTML 示例：

```html
<p align="center">
  <img src="./assets/images/jlclab-banner.png" width="100%" alt="JLCLAB">
</p>
```

尽量避免依赖不稳定的第三方图片托管服务。

## 🛠 Maintenance Guidelines

- **主页内容**：统一编辑 `profile/README.md`。
- **静态资源**：根据类型上传到 `profile/assets/` 对应目录。
- **资源更新**：替换资源时注意检查所有引用路径。
- **资源清理**：定期移除不再使用的图片和动图。
- **内容提交**：提交信息应清楚描述本次修改。

推荐 Commit Message：

```text
docs: update organization profile
assets: add candis product images
assets: optimize banner image
chore: remove unused assets
```

## 🔗 Related Links

- [JLCLAB Organization](https://github.com/jlclab-io)
- [Community](https://github.com/jlclab-io/community)
- [GitHub Documentation – Customizing your organization's profile](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)

---

Maintained by **JLC LAB**.
