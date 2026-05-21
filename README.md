# digouyouu.github.io

个人博客和作品展示网站，使用 GitHub Pages + Jekyll 布局继承实现文章模板复用

## 访问

👉 [https://digouyouu.github.io](https://digouyouu.github.io)

## 特性

- 🌙 **暗黑模式** - 内置深色主题，自动保存用户偏好
- 📱 **响应式设计** - 完美适配桌面、平板和手机
- 📝 **技术博客** - 分享开发经验和技术知识
- 🧩 **Jekyll 布局** - 文章页使用公共模板继承，减少重复代码
- 🎯 **快速返回** - 一键返回页面顶部
- ✨ **现代UI** - 简洁优雅的界面设计

## 项目结构

```
├── index.html           # 根目录重定向
├── _layouts/
│   └── post.html        # 文章公共布局
└── blog/
    ├── index.html       # 主页
    ├── list.html        # 博客列表
    ├── post1.html       # 博文：Python Web开发
    ├── post2.html       # 博文：前端性能优化
    └── post3.html       # 博文：Git最佳实践
```

## 技术栈

- HTML5 & CSS3
- Vanilla JavaScript
- Jekyll Layouts
- Google Fonts
- Font Awesome Icons

## 新增博客

1. 复制一份现有文章，比如 `blog/post3.html`。
2. 修改文件顶部的 front matter，更新 `title`、`description`、`date`、`tags` 等信息。
3. 保留 `layout: post`，正文只写文章内容，不再重复整套页面结构。
4. 在 `blog/index.html` 的“最新博客”区和 `blog/list.html` 里添加新文章链接。
5. 如果要调整统一样式，只改 `_layouts/post.html`，所有文章都会一起生效。

## 文章模板

```html
---
layout: post
title: "你的文章标题"
description: "一句话简介"
date: 2026-05-21
author: digouyou
reading_time: "5 分钟阅读"
tags:
    - 标签1
    - 标签2
---

<div class="article-header">
        <h1 class="article-title">你的文章标题</h1>
        ...
</div>

<div class="article-content">
        <p>这里写正文。</p>
</div>
```

## 许可证

MIT License
