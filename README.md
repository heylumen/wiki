# Qexo Wiki

[![License](https://img.shields.io/github/license/Qexo/Qexo)](https://github.com/Qexo/Qexo/blob/main/LICENSE)
[![VitePress](https://img.shields.io/badge/VitePress-1.6.4-blue)](https://vitepress.dev/)
[![Build Status](https://img.shields.io/github/actions/workflow/status/Qexo/wiki/main.yml)](https://github.com/Qexo/wiki/actions)

[Qexo](https://oplog.cn/qexo/) 文档站点 | Qexo Documentation Site

## 介绍 | Introduction

这是 Qexo 的官方文档站点，使用 VitePress 构建。Qexo 是一个美观、强大的在线静态博客管理器，不只是一个编辑器。

## 特色 | Features

- 📚 完整的中英文文档
- 🎨 基于 VitePress 的现代化文档体验
- 🔍 集成 DocSearch 搜索功能
- 💬 支持评论系统
- 📱 响应式设计

## 快速开始 | Quick Start

### 本地开发

```bash
# 克隆仓库
git clone https://github.com/Qexo/wiki.git
cd wiki

# 安装依赖
npm install
# 或
yarn install

# 启动开发服务器
npm run dev
# 或
yarn dev
```

### 构建部署

```bash
# 构建文档
npm run build
# 或
yarn build

# 预览构建结果
npm run serve
# 或
yarn serve
```

## 文档结构 | Documentation Structure

```
docs/
├── index.md              # 首页
├── start.md              # 快速开始
├── configs/              # 配置文档
│   ├── onepush.md
│   ├── provider.md
│   ├── statistic.md
│   ├── upload.md
│   └── vercel.md
├── exts/                 # 扩展功能
│   ├── custom.md
│   ├── flinks.md
│   ├── statistic.md
│   └── talks.md
├── practice/             # 实践教程
│   ├── abbrlink.md
│   └── smms.md
├── start/                # 入门指南
│   ├── build.md
│   ├── questions.md
│   └── update.md
├── dev/                  # 开发文档
│   ├── api.md
│   └── thanks.md
└── en/                   # English docs
    └── ...
```

## 贡献 | Contributing

欢迎贡献文档内容！如果您发现文档中的问题或想要改进文档，请：

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingDoc`)
3. 提交您的更改 (`git commit -m 'Add some AmazingDoc'`)
4. 推送到分支 (`git push origin feature/AmazingDoc`)
5. 创建一个 Pull Request

## 特别感谢 | Special Thanks

文档由 [洪墨AI](https://ai.zhheo.com/console/login?InviteID=79047483) 提供智能助手服务

## 相关链接 | Links

- [Qexo 主项目](https://github.com/Qexo/Qexo)
- [在线文档](https://oplog.cn/qexo/)
- [问题反馈](https://github.com/Qexo/Qexo/issues)

## 许可证 | License

[GPL 3.0 License](https://github.com/Qexo/Qexo/blob/main/LICENSE)
