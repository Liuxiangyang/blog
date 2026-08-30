# 我的博客

基于 [Hugo](https://gohugo.io/) + [PaperMod](https://github.com/adityatelange/hugo-PaperMod) 主题搭建的技术博客，部署于 [Vercel](https://vercel.com)。

## 本地开发

```bash
# 安装 Hugo (Extended) 与 Go（Hugo module 下载主题需要）
hugo server -D   # 本地预览 http://localhost:1313
```

## 写文章

在 `content/posts/` 新建 Markdown 文件：

```markdown
---
title: "文章标题"
date: 2026-08-31
draft: false
tags: ["标签"]
categories: ["分类"]
donate: true   # 可选：开启文章底部打赏
---
```

推送到 `main` 分支后 Vercel 自动构建部署。

## 技术栈

- Hugo（Extended，v0.165）+ PaperMod v8（Hugo module 引入）
- 主题通过 `hugo mod vendor` 固化（或构建时由 GO_VERSION 提供 Go 支持）
- 评论：giscus（GitHub Discussions）
- 搜索：Fuse.js（PaperMod 内置）
- 部署：Vercel（`vercel.json` 配置构建，`HUGO_VERSION` / `GO_VERSION` 环境变量）
