---
title: 使用二级域名和多个仓库配置Github Pages+Hexo
date: 2023-07-29 09:05:05
updated: 2023-08-04 10:05:12
description: 主仓库作首页，另一个仓库部署博客，再加一条域名解析就能用二级域名访问博客。
---

这个网站托管在Github Pages上，我把主要仓库作为首页，另外的一个仓库来部署博客。在首页加入跳转就可以到博客站了。

例如你的地址yourname.github.io，想要跳转到你新加的仓库名，比如blog，那么地址就是yourname.github.io/blog。如果想用blog.example.com 访问到yourname.github.io/blog，很简单，加一条解析就可以了。

以下是详细步骤

P.S. 我使用的解析是Cloudflare。

## 安装hexo
