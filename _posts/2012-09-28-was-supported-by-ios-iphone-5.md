---
author: Yonsm
comments: true
date: 2012-09-28 11:40:25+00:00
layout: post
slug: was-supported-by-ios-iphone-5
title: 让iOS程序支持iPhone 5
wordpress_id: 773
categories:
- 文档
---

觉得苹果真的很聪明，也很实际，实用主义，比如用开源这点就可以看出。最近iPhone5的支持又实用了一次（如果是微软，肯定不会这么实用主义，肯定是在某个注册表，或者哪里，弄一个重量级的声明，或者什么架构，什么的……）：

不用写任何代码，直接添加一张 640x1136 尺寸的 Default-568h@2x.png 图片到 IPA 中，就能支持 iPhone 5，而不再是两边黑框——前提是以前的代码写的好，高度方向没写死的话——大部分的程序都应该要能支持，除非那种游戏和高度方向无法灵活调整的程序，和蹩脚程序员写的程序。<!-- more -->

CeleDial我没写死，所以除了添加了一张图片之外，没有做任何改动就支持iPhone 5了，瞬间重新提交就行了。
