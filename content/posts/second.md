---
title: 'hugo ananke 主题的应用及配置'
author: 'leiyaqi'
date: '2023-12-12'
draft: false
featured_image: '/images/2.jpg'
---

## 首页背景图

首页背景图通过`_index.md`设置，该文件应该位于`content`目录下。例如：
```markdown

---
title: "测试题图"

description: "描述描述"
# 1. To ensure Netlify triggers a build on our exampleSite instance, we need to change a file in the exampleSite directory.
theme_version: '2.8.2'
cascade:
  featured_image: '/images/2.jpg'
---
Welcome to my blog with some of my work in progress. I've been working on this book idea. You can read some of the chapters below.
```

其中`featured_image`的图片，建议放在`static`目录下的`images`目录中，

## 单个页面的题图

单个页面的题图，通过该页面的front matter中的`featured_image`属性设定，例如：

```
---
title: "新闻稿"
featured_image: "/images/1.jpg"
---
```

  其中`featured_image`的图片，与上面首页题图的设置一致，建议放在`static`目录下的`images`目录中，

