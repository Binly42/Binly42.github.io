---
layout: post
title: 第八次作业
date: 2018-06-08
categories: 日志
tags: 博客
---


第八次作业 (对应 *lesson13.html*)

---

###### 说明

这个博客模板的 Markdown 渲染好像有点问题 ... 好像还不如 [Github 的渲染结果](https://github.com/Binly42/Binly42.github.io/blob/master/_posts/2018-06-08-System-Analysis-And-Design-Homework.08.md) ...

---

### 描述软件架构与框架之间的区别与联系

按照 `lesson13.html` 课件上的说法:
- 软件架构就是把系统分解为一些部件，描述这些部件的职责及它们之间的协作行为。
- 框架是特定语言和技术的架构应用解决方案。

而且,
* 框架是具体语言和技术相关的
* 框架是一种或多种架构的组合的实现
* 框架是集成了你的代码和多种第三方解决方案的工具，让你聚焦 **业务逻辑代码** 而 **不是技术实现**

大致来说,
- **架构(模式)** 是 做法, 策略, 思想, 组织方式 一样的东西 ;
- 而 **框架** 则是其 具体表现, 也可以作为 工具或元素 辅助 架构搭建的工作 ;


---

### 以你的项目为案例

#### 绘制三层架构模型图，细致到分区

*注: 我不确定 **三层架构模型图** 的具体要求, 所以参考 [我们小组的逻辑视图](https://github.com/Chun-Ge/documents/blob/master/docs/model-docs/logical-view/uml-package.png) 又画了一个 ...*

![三层架构模型图](../media/image/lesson13个人作业-三层架构模型图(Chun-Ge树洞).png)


#### 结合你程序的结构，从程序员角度说明三层架构给开发者带来的便利

- 关注点分离, 开发的时候可以减少各部分之间的互相影响和耦合, 明确焦点和分工, 利于并行开发, 也更便于设计, 复用, 迭代, 管理, 等等 ;


---

### 研究 VUE 与 Flux 状态管理的异同

就 状态管理 而言, Flux 和 Vue 的关系类同于 架构 和 框架 的关系 ;

*注: (这里讨论的只是原始而普通的 Flux架构)*

- 若是针对 Vuex, 那么大致上 [Vuex 其实是一个针对 Vue 特化的 Flux](https://www.zhihu.com/question/38546875/answer/76970954), 因而两者之间基本没有什么本质上的不同 ;
- 若是针对 Vue 作为一个 MVVM 的框架, 那么大致上 两者的异同便又可以归结为 Flux 和 (传统)MVC 的异同, 也即 单向数据流 和 中心化的 dispatcher 等特性所引发的异同, 这个在课件上给出的链接里也有提到 ;



---

这里的文章除了特别说明为 [转载] 之外，均为本人原创，转载请说明出处。

