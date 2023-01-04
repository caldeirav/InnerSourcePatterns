## Title

问题追踪器使用案例

## Patlet

内源东道主团队不仅没有使计划和进展，而且也没有将变化背景信息变透明。这可以通过增加项目问题跟踪器的使用案例来解决，它也可以为头脑风暴、实施讨论和功能设计服务。

## 问题

一个团队开发了组织中许多团队都依赖的组件。
它使用一个标准的问题跟踪器来跟踪开放的错误报告和功能请求。
然而，每个条目的上下文是非常有限的。因此，潜在的贡献者没有办法知道每个问题到底是在谈论什么变化。

## 上下文

内源项目的工具都已经设置好了。然而，一般的项目问题跟踪器主要用于分享项目进度。
在内源项目中，问题跟踪器则可以用于更多的用例追踪，使远程、异步的沟通更容易。

## 约束

- 贡献者希望了解他们所需的功能是否已经安排在路线图上。但由于问题中缺少大量的上下文，因此不可能决定现有问题是否符合贡献者的需求。
- 因此，很多重复的问题被打开，核心维护团队不得不处理。
- 由于开放问题中的上下文是如此有限，贡献者无法通过实施一些已经开放的更容易的问题来帮助核心维护团队。因此，大量的工作仍然在东道主团队的手中。
- 由于强烈关注口头交流，在几个月或几年后，不可能辨别出为什么某个功能会被选中实施。因此，重构，特别是简化组件的工作，就成了项目考古学和寻找谁还记得讨论过什么的脑力练习。

## 解决方案

拥抱 "书面胜于口头 "的理念，不仅是在纯粹的软件开发中，而且在新功能的规划阶段也是如此。

- 对于bug，计划中的功能以及功能想法都会产生单独的问题描述。在每一个问题中包括尽可能多的信息，以便潜在的外部贡献者能够理解其背景。理想情况下，特别是对于比较容易的变化，包括足够的信息，以便外部贡献者通过实现相关的功能来支持东道主团队。
- 尽可能使用问题跟踪器作为提问的渠道。如果你缺乏其他的沟通渠道来解决用户的问题，这尤其有帮助。
- 利用标签和类别，以区分用于不同目的的问题。
- 对于异步开始的头脑风暴会议，打开一个问题来收集想法。当讨论开始平静下来时，在一个单独的文件中总结这个问题中已经确定的要点。在相关的拉动请求（代码实现）发布出来，以深入研究仍然需要澄清的个别要点，以供代码评审使用。由此产生的文件可以用来在其他适当的渠道发布结果，并供未来参考。
- 大多数问题跟踪器的实现都提供了问题模板。利用这些模板，不仅可以收集bug报告的常用信息，还可以包括其他使用类型所需的信息提示。

## 结果

- 更多地利用项目的问题跟踪器进行交流，使外部贡献者能够跟上，并对贡献什么内容做出更好的。
- 注重结构化的书面交流使东道主团队成员能够远程参与。
- 始终以书面形式进行沟通意味着关于项目决策的被动文件会作为副产品积累起来，而不是需要增加关注。
- 始终如一地使用公共交流渠道，导致更多的人关注讨论。这意味着有更多知识渊博的人可以回答问题，在开放的问题上插话，或者指出计划中的功能的缺陷，否则这些缺陷会在很久以后才被发现。
- 将讨论转移到公共讨论媒介上，为未来的潜在贡献者创造了一个机会，让他们在第一次需要参与之前就能聆听、跟随、适应和了解项目的运作方式。

## 已知实例

* Europace AG - 请看博文 [Issue Use Cases](https://tech.europace.de/post/using-issues-for-asking-questions-and-tracking-work/)

## 作者

Isabel Drost-Fromm

## 状态

结构化

## 翻译校对

* **2022-12-06** 翻译[姜宁](https://github.com/willemjiang)
* **2022-12-09** 校对[龙文选](https://github.com/hncslwx)