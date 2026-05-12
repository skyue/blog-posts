---
title: "中文排版最佳实践"
date: 2024-03-10
description: "从字体选择到间距调整，打造优雅的中文阅读体验。"
categories: ["设计", "排版"]
tags: ["中文", "typography", "阅读体验"]
draft: false
---

中文排版与西文排版有许多不同之处。本文分享一些实用的中文排版技巧。

## 字体栈

推荐使用系统字体栈，避免加载外部字体文件：

```css
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, "Noto Sans SC", "PingFang SC", "Microsoft YaHei",
    sans-serif;
}
```

## 行高与间距

中文正文推荐行高在 1.6 到 1.8 之间，段落间距适当加大，让阅读更加舒适。
