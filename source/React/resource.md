---
title: React 源码解析（1）
date: 2020-10-11 19:23:52
---

## React Dom Render

在React中整个React App是通过reactDom 的render方法 append 进Dom中的。 
所以要想搞清楚React源码 我的方法是从这里入手， 看看ReactDom的render 到底做了些什么；

{% asset_img  render.drawio.png %}