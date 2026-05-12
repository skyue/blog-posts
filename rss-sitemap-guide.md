---
title: "RSS 与站点地图配置指南"
date: 2024-04-05
description: "为你的 Astro 博客添加 RSS 订阅源和 XML 站点地图。"
categories: ["技术", "SEO"]
tags: ["rss", "sitemap", "seo", "astro"]
draft: false
---

RSS 和站点地图是博客的重要基础设施。本文介绍如何在 Astro 中配置它们。

## RSS 订阅

使用 `@astrojs/rss` 包可以快速生成 RSS 订阅源：

```js
import rss from '@astrojs/rss';
```

## 站点地图

`@astrojs/sitemap` 集成会自动为所有页面生成 XML 站点地图文件。
