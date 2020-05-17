# 课程简介

## 内容综述

- 第一章：课程背景介绍
- 第二章：技术预研篇
- 第三章：项目开发篇
- 第四章：性能调优篇
- 第五章：框架、工程化篇

## Node.js 是什么？

**什么是 Node.js？**

官网的话：

- Node.js 是一个基于 **Chrome V8 引擎**的 JavaScript 运行环境。
- Node.js 使用了一个**事件驱动**、**非阻塞式 I/O** 的模型，使其轻量又高效。

在 Node.js 里运行 JavaScript 跟在 Chrome 里运行 JavaScript 有什么不同？

- Chrome 浏览器用的是同样的 JavaScript 引擎和模型

其实，在 Node.js 里写 JS 和在 Chrome 里写 JS，**几乎没有不一样！**

**那不一样在哪里呢？**

- Node.js 没有浏览器 API，即 document，window 等。
- 加了许多 Node.js API。

**所以，对于开发者来说，Node.js：**

- 在 Chrome 里写 JavaScript 控制**浏览器**。
- Node.js 让你用类似的方式，控制**整个计算机**。

> 人生的真谛要用自己一辈子去理解的。

Node.js 的真谛，也需要你在 Node.js 的学习过程中慢慢理解：

- “Node.js 是一个基于 Chrome V8 引擎的 JavaScript 运行环境。”
- “Node.js 使用了一个事件驱动、非阻塞式 I/O 的模型。”

## Node.js 可以用来做什么？

- Web 服务 —— 腾讯视频

  - 搜索引起优化 + 首屏速度优化 = 服务端渲染
  - 服务端渲染 + 前后端同构

- 构建工作流

  Automate and enhance your workflow

  - 构建工具不会永远不出问题
  - 构建工具不会永远满足需求
  - 使用 Node.js 做 JS 构建工具，是最保险的选择。

- 开发工具 —— Visual Studio Code

- 游戏 —— wayward

- 客户端应用 —— twitch.tv

  - 在已有网站的情况下需要新开发客户端应用。
  - 用 Node.js 客户端技术（electron）实现，最大限度复用现在工程。

**可扩展性**

- 大型应用需要给使用者自定义模块的能力
- 使用 Node.js 做复杂本地应用
  - 可以利用 JS 的灵活性提供外部扩展
  - JS 庞大的开发者基数让他们的灵活性得到利用

## 课程实战项目介绍

**Node.js 版极客时间网站**

- 列表页
  - 打通前后台
  - 服务端渲染
- 详情页
  - 网页路由
  - 异步加载
- 播放页
  - API 服务器

