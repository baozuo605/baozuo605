# 🚀 My Tech Blog

[![License](https://img.shields.io/github/license/baozuo605/baozuo605)](https://github.com/baozuo605/baozuo605/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/baozuo605/baozuo605)](https://github.com/baozuo605/baozuo605/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/baozuo605/baozuo605)](https://github.com/baozuo605/baozuo605/issues)
[![Build Status](https://img.shields.io/github/actions/workflow/status/baozuo605/baozuo605/deploy.yml)](https://github.com/baozuo605/baozuo605/actions)

> 记录技术成长 | 分享开发经验 | 构建知识体系

## ✨ 核心特性
- 🚀 基于 [Hugo](https://gohugo.io/) 静态网站生成器
- 📱 响应式设计，完美适配移动端
- ✍️ GitHub Flavored Markdown 支持
- 📑 自动生成文章目录
- 🌈 Prism 代码高亮
- 🌍 多语言支持（中/英）
- ⚡ GitHub Actions 自动部署
- 📡 RSS/Atom 订阅支持
- 🔍 SEO 优化
- 🔒 隐私保护 (GDPR 合规)

## 🚀 快速开始
### 本地开发
```bash
# 克隆仓库
git clone https://github.com/baozuo605/baozuo605.git
cd baozuo605

# 安装依赖 (可选)
npm install

# 启动开发服务器
hugo server -D --bind=0.0.0.0 --baseURL=http://localhost:1313
```

### 生产构建
```bash
hugo --minify
```

## 📂 项目结构
```
.
├── archetypes/       # 文章模板
├── assets/           # 静态资源
├── content/          # 文章内容
├── data/             # 数据文件
├── layouts/          # 布局文件
├── public/           # 构建输出
├── static/           # 静态文件
├── themes/           # 主题目录
└── config.toml       # 配置文件
```

## 🤝 贡献指南
欢迎提交 Pull Request 或报告 Issues。请确保:
1. 遵循现有代码风格
2. 提交清晰的提交信息
3. 更新相关文档

## 📜 许可证
本项目采用 [MIT License](LICENSE) 开源协议