---
title: 博客心得
slug: blog-reflections
description: 东拼西凑的装修记录
date: 2025-06-19
lastmod: 2025-06-19 00:00:00+0000
categories:
    - tech
tags: 
    - Hugo

---

## 标签和分类的用法
因为已经习惯了用其他博客服务提供的分类、标签结构，对于Hugo的此类功能，一开始以为只是在每篇文章的开头部分，所有列在categories和tags里的内容，按照所见即所得的形式生成相应的标签和分类，还思考了很久命名形式、要不要包含多语言；直到终于注意到模板里有一个example-category才开始思考具体的用法。所以其实可以用更简单的形式给分类命名，之后在对应categories/tags文件夹里的_index.md里再去定义title作为显示的名称。

标签也是同理，虽然模板里原本没有自带tags文件夹，但是参照categories的形式自己创建tags文件夹之后，也可以以同样的方法对每个标签创建单独的页面、配置显示名称。