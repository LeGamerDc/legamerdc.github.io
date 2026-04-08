# legamerdc.github.io

LeGamerDc 的个人技术博客，使用 [Jekyll](https://jekyllrb.com) 搭建，托管于 [GitHub Pages](https://pages.github.com)。

## 目录结构

```
.
├── _blog/           # 博客文章（Markdown 格式）
├── _resource/       # 静态资源（图片、音频、视频）
│   ├── images/      #   图片
│   ├── audio/       #   音频
│   └── video/       #   视频
├── _layouts/        # Jekyll HTML 模板
│   ├── default.html #   基础页面模板
│   └── post.html    #   博客文章模板
├── assets/
│   └── css/
│       └── main.css # 全局样式
├── index.html       # 首页
├── blog.html        # 博客列表页（/blog/）
└── _config.yml      # Jekyll 配置
```

## 写作指南

在 `_blog/` 中新建一个 Markdown 文件即可发布新文章，文件需包含 Front Matter：

```markdown
---
title: "文章标题"
date: 2026-01-01
tags: [标签1, 标签2]
---

正文内容……
```

引用 `_resource/` 中的资源：

```markdown
![图片描述](/resource/images/example.png)
```

## 本地预览

```bash
bundle exec jekyll serve
# 访问 http://localhost:4000
```
