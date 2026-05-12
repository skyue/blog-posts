---
title: "Tailwind CSS 与深色模式"
date: 2024-02-20
description: "探索如何使用 Tailwind CSS 构建支持深色模式的现代化界面。"
categories: ["前端", "设计"]
tags: ["tailwindcss", "深色模式", "css"]
draft: false
---

深色模式已经成为现代网站的标配。本文将介绍如何在 Tailwind CSS 中优雅地实现深色模式。

## class 策略

Tailwind 支持多种深色模式策略，其中 `class` 策略最为灵活：

```js
// tailwind.config.mjs
export default {
  darkMode: 'class',
  // ...
};
```

## 实际应用

通过在根元素上切换 `dark` 类，我们可以实现无闪烁的深色模式切换。
