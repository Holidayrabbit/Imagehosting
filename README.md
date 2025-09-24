# 📸 图床仓库 (Image Hosting Repository)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/Holidayrabbit/Imagehosting.svg)](https://github.com/Holidayrabbit/Imagehosting/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Holidayrabbit/Imagehosting.svg)](https://github.com/Holidayrabbit/Imagehosting/network)

> 🌟 一个基于 GitHub 的免费图床解决方案，使用 PicGo 进行图片上传和管理

## 📋 项目简介

这是一个用于托管博客和网站图片的 GitHub 仓库。通过与 PicGo 工具配合使用，可以快速上传图片并获得稳定的图片链接，为博客写作和内容创作提供便利的图片存储服务。

## 🎯 主要特性

- ✅ **免费可靠** - 基于 GitHub 的稳定存储服务
- ✅ **自动上传** - 配合 PicGo 实现一键上传
- ✅ **CDN 加速** - 支持 jsDelivr 等 CDN 服务加速访问
- ✅ **版本控制** - 完整的图片版本历史记录
- ✅ **批量管理** - 方便的图片批量操作和管理
- ✅ **多格式支持** - 支持 PNG、JPG、GIF 等多种图片格式

## 📁 目录结构

```
Imagehosting/
├── BlogImg/          # 博客图片存储目录
│   ├── 202409*.png   # 按时间戳命名的图片文件
│   ├── 202409*.jpg   # 支持多种格式
│   └── ...
├── LICENSE           # MIT 开源协议
└── README.md         # 项目说明文档
```

## 🚀 使用方法

### 1. PicGo 配置

1. 下载并安装 [PicGo](https://github.com/Molunerfinn/PicGo)
2. 配置 GitHub 图床：
   - 仓库名：`Holidayrabbit/Imagehosting`
   - 分支名：`main`
   - Token：GitHub Personal Access Token
   - 存储路径：`BlogImg/`
   - 自定义域名：`https://cdn.jsdelivr.net/gh/Holidayrabbit/Imagehosting@main`

### 2. 图片访问链接格式

上传成功后，图片可通过以下格式访问：

**GitHub 原始链接：**
```
https://raw.githubusercontent.com/Holidayrabbit/Imagehosting/main/BlogImg/[图片名称]
```

**CDN 加速链接（推荐）：**
```
https://cdn.jsdelivr.net/gh/Holidayrabbit/Imagehosting@main/BlogImg/[图片名称]
```

### 3. 在 Markdown 中使用

```markdown
![图片描述](https://cdn.jsdelivr.net/gh/Holidayrabbit/Imagehosting@main/BlogImg/202409031759722.png)
```

## 📊 统计信息

- 📸 **图片总数**：50+ 张
- 📅 **创建时间**：2024年9月
- 🔄 **最近更新**：持续更新中
- 📦 **文件大小**：根据需要动态增长

## ⚙️ 配置建议

### PicGo 插件推荐

- **picgo-plugin-github-plus** - 增强的 GitHub 上传插件
- **picgo-plugin-compress** - 图片压缩插件
- **picgo-plugin-watermark** - 图片水印插件

### CDN 替代方案

如果 jsDelivr 访问较慢，可以尝试以下 CDN：

```
# Staticaly CDN
https://cdn.staticaly.com/gh/Holidayrabbit/Imagehosting/main/BlogImg/[图片名称]

# GitHub 代理
https://ghproxy.com/https://raw.githubusercontent.com/Holidayrabbit/Imagehosting/main/BlogImg/[图片名称]
```

## 🔒 注意事项

1. **容量限制**：单个仓库建议不超过 1GB
2. **文件大小**：单个文件不超过 100MB
3. **访问频率**：避免恶意刷量，合理使用
4. **内容审核**：请确保上传内容符合相关法律法规
5. **备份建议**：重要图片请做好本地备份

## 🤝 贡献指南

如果您有任何建议或发现问题，欢迎：

1. 提交 [Issue](https://github.com/Holidayrabbit/Imagehosting/issues)
2. 发起 [Pull Request](https://github.com/Holidayrabbit/Imagehosting/pulls)
3. 分享使用经验和优化建议

## 📜 开源协议

本项目采用 [MIT License](LICENSE) 开源协议，您可以自由使用、修改和分发。

## 🙏 致谢

- 感谢 [PicGo](https://github.com/Molunerfinn/PicGo) 提供优秀的图片上传工具
- 感谢 [jsDelivr](https://www.jsdelivr.com/) 提供免费的 CDN 服务
- 感谢 GitHub 提供稳定的代码托管服务

---

<div align="center">

**⭐ 如果这个项目对您有帮助，请给个 Star 支持一下！**

[🏠 主页](https://github.com/Holidayrabbit/Imagehosting) | [📝 Issues](https://github.com/Holidayrabbit/Imagehosting/issues) | [🔀 Pull Requests](https://github.com/Holidayrabbit/Imagehosting/pulls)

</div>