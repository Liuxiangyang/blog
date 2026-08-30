---
title: "Hello World：博客搭建完成"
date: 2026-08-30
draft: false
tags: ["博客", "Hugo", "教程"]
categories: ["技术"]
donate: true
---

欢迎来到我的博客！本站基于 **Hugo + PaperMod** 搭建，部署在 Vercel。

## 本站功能

- 全文搜索（Fuse.js，右上角搜索按钮）
- 文章目录（本文右上角 TOC）
- 暗色模式（跟随系统，可手动切换）
- RSS 订阅（`/index.xml`）
- 评论（giscus，GitHub Discussions 驱动）
- 打赏（本文底部已开启，示例区块）

## 写文章时的常用写法

### 代码块（带一键复制按钮）

```python
def hello(name: str) -> str:
    return f"Hello, {name}!"
```

### 中文排版验证

这一段文字用于验证 Hugo 的中文字数统计与阅读时长是否正确。`hasCJKLanguage = true` 已开启，中文按字计数。Emoji 支持已开启：🚀🎉📝

### 引用

> 把生命浪费在美好的事物上。
> —— forecho

## 开始写你的第一篇文章

在 `content/posts/` 下新建 `.md` 文件，头部加上 front matter 即可：

```yaml
---
title: "我的文章标题"
date: 2026-08-30
draft: false
tags: ["标签"]
categories: ["分类"]
---
```

然后推送到 GitHub，Vercel 会自动构建部署。

## 结语

感谢阅读。欢迎使用底部评论区或搜索功能探索本站。

> 2026-08-31 更新：博客已部署上线 🎉
