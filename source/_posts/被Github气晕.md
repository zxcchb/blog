---
title: 被Github气晕
date: 2023-11-02 16:15:25
updated: 2023-11-02 16:19:56
description: 网站莫名其妙变成Cloudflare 526界面的排查记录。
---

最近打开才发现莫名其妙变成cloudflare 526界面，查了下资料感觉是DNS解析问题。故把验证域名那些重新操作了一遍，还重新生成了SSL证书，网站才正常了。

但是不清楚是什么原因，因为二级域名的blog.oshinoko.cn反倒是正常的，不知道是不是跟GitHub的域名验证莫名其妙消失有关。
