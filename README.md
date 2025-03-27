# 🚀 My Tech Blog

[![License](https://img.shields.io/github/license/baozuo605/baozuo605)](https://github.com/baozuo605/baozuo605/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/baozuo605/baozuo605)](https://github.com/baozuo605/baozuo605/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/baozuo605/baozuo605)](https://github.com/baozuo605/baozuo605/issues)
[![Build Status](https://img.shields.io/github/actions/workflow/status/baozuo605/baozuo605/deploy.yml?branch=main)](https://github.com/baozuo605/baozuo605/actions/workflows/deploy.yml)
[![Hugo Version](https://img.shields.io/badge/Hugo-0.110.0-blue)](https://gohugo.io)

> 记录技术成长 | 分享开发经验 | 构建知识体系

## ✨ 核心特性
- 🚀 基于 [Hugo](https://gohugo.io/) 静态网站生成器 (v0.110.0)
- 📱 响应式设计，完美适配移动端
- ✍️ GitHub Flavored Markdown 支持
- 📑 自动生成文章目录 (支持多级标题)
- 🌈 Prism.js 代码高亮 (支持200+语言)
- 🌍 多语言支持 (中/英) + i18n 国际化
- ⚡ GitHub Actions 自动部署 (每小时自动构建)
- 📡 RSS/Atom/JSON Feed 订阅支持
- 🔍 SEO 优化 (自动生成sitemap.xml)
- 🔒 隐私保护 (GDPR 合规，无追踪)
- 📊 谷歌分析集成 (可选)
- 🔗 自动链接检查 (CI集成)

## 🚀 快速开始
### 系统要求
- Hugo Extended (v0.110.0+)
- Node.js (v16+)
- Git

### 本地开发
```bash
# 克隆仓库 (推荐使用SSH)
git clone git@github.com:baozuo605/baozuo605.git
cd baozuo605

# 安装依赖 (推荐使用pnpm)
pnpm install

# 启动开发服务器 (带热重载)
hugo server -D --bind=0.0.0.0 --baseURL=http://localhost:1313 --disableFastRender
```

### 生产构建
```bash
hugo --minify --gc --cleanDestinationDir
```

## 📂 项目结构
```
.
├── archetypes/       # 文章模板 (支持多种内容类型)
├── assets/           # 静态资源 (SCSS/JS编译)
├── content/          # 文章内容 (多语言支持)
├── data/             # 数据文件 (JSON/YAML/TOML)
├── i18n/             # 国际化文件
├── layouts/          # 布局文件 (覆盖主题)
├── public/           # 构建输出
├── static/           # 静态文件 (直接复制)
├── themes/           # 主题目录 (git submodule)
├── .github/          # GitHub配置
├── netlify.toml      # Netlify配置
├── config.toml       # 主配置文件
└── package.json      # 前端依赖
```

## 🧑‍💻 写作指南
1. 创建新文章:
```bash
hugo new posts/your-post.md
```
2. 使用Front Matter:
```yaml
title: "文章标题"
date: 2023-07-20
draft: false
tags: ["Hugo", "Markdown"]
categories: ["技术"]
toc: true  # 启用目录
```

## 🤝 贡献指南
欢迎贡献！请遵循以下流程:
1. Fork仓库
2. 创建特性分支 (`git checkout -b feature/your-feature`)
3. 提交变更 (`git commit -m 'Add some feature'`)
4. 推送到分支 (`git push origin feature/your-feature`)
5. 创建Pull Request

## 📜 许可证
MIT License © 2023 [baozuo605](https://github.com/baozuo605)