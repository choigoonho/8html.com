---
layout: 8html-posts
title: 不用ASP的理由
author: caiguanhao
category: tech
tags: Obsolete
description: 身处在这个恶劣的中国“局域网”世界里，新的技术自然得不到更新和传播，使用ASP也可以大赚那些不懂市场的人的钱。
---
本文讲的是经典ASP，如果你现在还在用这个破旧烂的语言（不，ASP不是语言，VB才是，ASP应该是一个脚本引擎），你就是跟自己过不去（出问题修改代码各种烦），跟钱作对。当然身处在这个恶劣的中国“局域网”世界里，技术自然得不到更新和传播，破烂的技术也可以大赚那些不懂市场的人的钱。虽然不是讲ASP.NET，不过最好还是少用微软出品的东西（起码.NET这个名字就很差）。

对，应该是ASP带领我学会了网页编程，再之后也学会了些软件编程。因为当时Win98/2000有个PWS的东西，它有些示例网页，你改一下就可以看到结果了，然后慢慢学会了些技巧。当时为了想弄个浏览者计数器就花了很长时间。接着很长时间一直在ASP，几乎到了神级，直到两年前我还用着这个非常非常过时的工具。

因为当时开始流行网址没有扩展名的网页，后来才知道叫伪静态，当然也不知道当时那些人是用URL重写模块完成的。基于落后而且买的空间局限所致，最后还找到了一种通过修改404页面的方法搞成了伪静态。除了这个感觉好点外，就是烦。ASP的编码问题一直不能解决。特别是上传文件会出现很多乱码。前几天就试着回顾之前我的网站，打算用 git 记录，放到我的网站保存，但是很不幸的是，文件不是utf-8编码，放到上去的时候乱码了。将文件转为utf-8之后各种问题，包括数据库的也不是utf-8编码，或许ASP对英文网页好点，在面对中文问题上就要花很多精力。

现在很多人骂PHP去称赞Python等语言，就像很多年前很多人骂ASP去称赞PHP，但起码PHP可以跨平台实现，那些坚守Win平台的人应该没话好说了。或者过多几年，到我这个学语言速度很慢的人再去更其他人说不要用PHP了。
