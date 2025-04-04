# 🚀 My Tech Blog

[![License](https://img.shields.io/github/license/baozuo605/baozuo605?style=flat-square)](https://github.com/baozuo605/baozuo605/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/baozuo605/baozuo605?style=flat-square)](https://github.com/baozuo605/baozuo605/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/baozuo605/baozuo605?style=flat-square)](https://github.com/baozuo605/baozuo605/issues)
[![Build Status](https://img.shields.io/github/actions/workflow/status/baozuo605/baozuo605/deploy.yml?branch=main&style=flat-square)](https://github.com/baozuo605/baozuo605/actions/workflows/deploy.yml)
[![Hugo Version](https://img.shields.io/badge/Hugo-0.110.0-blue?style=flat-square&logo=hugo)](https://gohugo.io)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Code Style](https://img.shields.io/badge/code%20style-prettier-ff69b4.svg?style=flat-square)](https://prettier.io)

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
- 🛡️ CSP 安全策略
- 📈 性能监控 (Lighthouse CI)
- 🧹 自动格式化 (Prettier + Markdownlint)

## 🚀 快速开始
### 系统要求
- Hugo Extended (v0.110.0+)
- Node.js (v18+ LTS)
- Git 2.30+
- pnpm 7.0+

### 本地开发
```bash
# 克隆仓库 (推荐使用SSH)
git clone git@github.com:baozuo605/baozuo605.git && cd baozuo605

# 安装依赖 (推荐使用pnpm)
pnpm install --frozen-lockfile

# 启动开发服务器 (带热重载)
hugo server \
  -D \
  --bind=0.0.0.0 \
  --baseURL=http://localhost:1313 \
  --disableFastRender \
  --enableGitInfo
```

### 生产构建
```bash
hugo \
  --minify \
  --gc \
  --cleanDestinationDir \
  --enableGitInfo \
  --templateMetrics \
  --templateMetricsHints
```

## 📂 项目结构