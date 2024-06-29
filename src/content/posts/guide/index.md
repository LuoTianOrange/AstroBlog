---
title: Fuwari简单教程
published: 2024-04-01
description: "如何使用该博客模板."
image: "./cover.jpeg"
tags: ["Fuwari"]
category: Guides
draft: false
---

> 封面图片来源: [链接](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/208fc754-890d-4adb-9753-2c963332675d/width=2048/01651-1456859105-(colour_1.5),girl,_Blue,yellow,green,cyan,purple,red,pink,_best,8k,UHD,masterpiece,male%20focus,%201boy,gloves,%20ponytail,%20long%20hair,.jpeg)

这个博客模板是用 [Astro](https://astro.build/)构建的。 对于本指南中未提到的事项，你可能会在[Astro Docs](https://docs.astro.build/)中找到答案。

## 文章的 Front-matter

```yaml
---
title: 我的第一篇博客文章
published: 2023-09-09
description: 这是我新 Astro 博客的第一篇文章。
image: ./cover.jpg
tags: [Foo, Bar]
category: 前端
draft: false
---
```

| 属性     | 描述                                                                                                                                                                                                 |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `title`       | 文章的标题。                                                                                                                                                                                      |
| `published`   | 文章发布的日期。                                                                                                                                                                            |
| `description` | 文章的简短描述。在索引页面上显示。                                                                                                                                                   |
| `image`       | 文章的封面图片路径。<br/>1. 以 `http://` 或 `https://`开头：使用网络图片<br/>2. 以`/`开头用于 `public` 目录中的图片<br/>3. 没有以上前缀：相对于 markdown 文件的路径 |
| `tags`        | 文章的标签。                                                                                                                                                                                       |
| `category`    | 文章的类别。                                                                                                                                                                                   |
| `draft`        | 如果这篇文章仍然是草稿，那么它将不会被显示。                                                                                                                                                    |

## 如何放置文章文件



你的文章文件应该放在 `src/content/posts/` 目录中。你也可以创建子目录来更好地组织你的文章和资源。



```
src/content/posts/
├── post-1.md
└── post-2/
    ├── cover.png
    └── index.md
```
