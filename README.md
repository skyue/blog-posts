# Blog Posts

Astro 博客的文章仓库，纯 Markdown 格式。

## 写作规范

文章使用标准 Markdown 格式，frontmatter 示例如下：

```yaml
---
title: "文章标题"
date: 2025-05-10
description: "文章摘要"
categories:
  - 技术
  - 前端
tags:
  - astro
  - 教程
draft: false
cover: "https://img.example.com/cover.jpg"
---

正文内容...
```

## 自动部署

推送新文章到 `main` 分支后，会自动触发 [astro-blog](https://github.com/skyue/astro-blog) 重新构建并部署。

## 图床

图片建议上传至 Cloudflare R2，在文章中引用完整 URL。

## 历史文章

本仓库从 [blog_data](https://github.com/skyue/blog_data) 迁移而来。
