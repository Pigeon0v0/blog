---
title: Favicon 趣事一则
date: 2025-07-24 11:18:03
tags: blog
---
早前就给本站添加了 `favicon.png`，且本地测试一切正常，但是上了 Vercel 就一直不好使。

今天仔细研究了一下，发现换成 `favicon.ico` 就好使了...

你知道吗，上了 Vercel 之后，请求 `favicon.png` 是直接 404 的那种，不是浏览器读不读取的问题...