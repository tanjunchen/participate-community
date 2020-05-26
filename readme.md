# 开源社区

***[借助开源项目，学习软件开发](https://github.com/zhuangbiaowei/learn-with-open-source)***

![opensource](images/opensource.png)

## 介绍

开源社区又称开放源代码社区，一般由拥有共同兴趣爱好的人所组成，根据相应的开源软件许可证协议公布软件源代码的网络平台，同时也为网络成员提供一个自由学习交流的空间。由于开放源码软件主要被散布在全世界的编程者所开发，开源社区就成了他们沟通交流的必要途径，因此开源社区在推动开源软件发展的过程中起着巨大的作用。[百度百科]

在如今的软件设计，架构及开发中，开源扮演着越来越重要的角色。

从 SSM、ROR 到 OpenJDK，Kafka, Tenserflow，甚至就连火遍全球，日行千里的比特币 Bitcoin 也是开源产品。这种开源产品促进了更多的币的出现与链的产生，当然还有习惯到忽视他是开源产品的 Linux。

作为开发工程师，Linux、Mysql、以及各种编程语言和框架的源代码，我们可以随时利用这些开源技术实现自己的业务要求。其中，方便且免费地使用这些技术，当然离不开上述各种技术的开源，当今世界，这是一个开源的时代，所以，我们应该主动拥抱开源，工作之余了解与学习开源社区那些事。

## 开源社区分类

其实，开源社区已经存在许久啦，但是对于我和一些人来说，可能比较新奇，所以本文介绍了一些开源社区的概念、如何参与社区、为什么要参与社区？

[CNCF 基金会](https://www.cncf.io/)

[kubernetes](https://github.com/kubernetes/kubernetes)、[prometheus](https://github.com/prometheus/prometheus)、[Dragonfly](https://github.com/dragonflyoss/Dragonfly) 等。

[Apache 软件基金会](https://www.apache.org/)  [Apache 项目列表](http://www.apache.org/index.html#projects-list)

如 [Kafka](https://github.com/apache/kafka)、[ZooKeeper](https://github.com/apache/zookeeper)、[Hive](https://github.com/apache/hive) 等。

[TensorFlow](http://www.tensorfly.cn/)

...... 等等，开源社区很多，找到适合自己的才是最好的。


## 如何挑选开源社区

这里简单地列出了几个条件：

1. 社区/项目方向是否符合你的期望/兴趣。比如希望更多关注在后端领域，那很多前端方向的开源项目就可以放弃。
1. 社区/项目的技术栈是否与你匹配，匹配的技术栈可以使你以更快的速度熟悉代码。技术栈包括编程语言、采用的框架或者库等。
1. 社区接纳新人的友好程度。这对于初入开源，而且并不以开源为生的新人来说，是非常重要的。对于新人来说，开源的贡献活动并不能带给他们任何短期可见的回报，因此需要友好的社区来给予他们正面的反馈，使得贡献活动进入一个良性循环。友好程度，有很多地方可以反映，比如项目是否有清晰易懂的贡献指南，是否具有完善的 CI/CD 支持，是否有完善的晋升路线（新贡献者 - Reviewer - Commiter - Maintainer 等），是否可以简单直接地直接接触到项目的维护人员，有完善的答疑渠道等方面。不过要注意，友好程度跟项目的受欢迎程度是两回事，受欢迎（Star 多）的项目未必有一个友好的社区。一个额外的小建议，刚开始参与开源时，不要选择公司开源的开源项目进行贡献。公司开源的项目通常会不如社区驱动的开源项目友好。
1. 是否是使用过或者熟悉的开源项目。一个好的贡献者也是一个好的用户。如果之前就有使用过的开源项目，会免去熟悉的过程。

最后，在我看来，选择的优先级是：[1] > [3] > [4] > [2]。因为方向无论如何是最重要的，在确定方向后，社区的友好程度应该是更加值得考虑的，这也是我在接触开源以后才发现的。最后，是技术栈的熟悉程度。个人认为，编程语言等等的选择，相对不是那么重要的。如果是 Java 后端的话，可能 Apache or Eclipse 基金会下那一堆开源项目或者 Spring 等等，会比较合适。

整理于知乎话题 [在校生如何在开源社区中成长？](https://www.zhihu.com/question/336820269/answer/851806875)

## Github 得力助手

在 Github 上有很多的项目，我们应该如何去抉择呢？有很多种方式提高我们的搜索效率。

如：搜索某个用户：

location:china language:java followers:>=1000

![github_developer](images/java/github_developer.jpg)


![user_search](images/user_search.png)

搜索某个项目

awesome:高并发  language:java starts:>=500 forks:200

![github_user](images/java/github_user.jpg)


![user_search](images/user_search.png)


## 如何参与开源社区

这里以 CNCF 为例，举例说明如何参与 CNCF 开源社区。见[<font face="宋体" color=red size=3>如何参与 Kubernetes 开源社区</font>](participate_k8s.md)

[GitHub Trend](https://github.com/trending) 页面总结了每天/每周/每月周期的热门 Repositories 和 Developers，你可以看到在某个周期处于热门状态的开发项目和开发者。而 [GitHub Topic](https://github.com/topics) 展示了最新和最流行的讨论主题，在这里你不仅能够看到开发项目，还能看到更多非开发技术的讨论主题，比如 Job、Chrome 浏览器等。

![opensource](images/java/github_trending.png)


![opensource](images/java/github_topic.png)


## 期待与收获

Kubernetes 目前已经是云时代的操作系统，作为容器编排领域的事实标准和云原生领域的 Boss，学习与了解 Kubernetes 的使用和原理成为云原生时代开发工程师的必备技能。

开源社区如此之多，选择自己感兴趣的或者对自己从事的工作有帮助的是最好不过的啦，开源与工作相结合是比较推崇的，既可以提升平时工作的效率(社区中比较好用的工具应用到工作中)，也可以提升对开源社区的兴趣(比如你对某项开源项目中的某个 topic 或 issue 感兴趣，则可以尝试用自己所掌握的知识去实现它)。从不同的社区中我们能够学习到不同的东西，比如：社区的管理与运作方式、提升某项技能、增强编码能力与编码规范。

在开源社区能够收获什么呢？

1. 提升编码水平与编码规范。
1. 与世界上最优秀的工程师们交流，能够开拓视野，如 k8s 新增一项功能，必须严格遵循 alpha -> beta -> release -> GA 等阶段、e2e 测试、编写完整的文档、代码注释。
1. 可以快速理解项目的实现原理以及工作流程，提升工作效率，提升个人水平。
1. 大厂加分项。
1. ......


## 源码之旅 - 题外话

学习与阅读源码是一门苦差事，参与开源社区也需要耐心与持之以恒的决心。

1. 后端开发者，尤其是 Java Web 从事者，不知是否听说过访问量 3 百万 + 的 [芋道源码](https://github.com/YunaiV)。

1. 前端开发者不知是否知道[司徒正美](https://github.com/RubyLouvre ) JavaScript 专家，开源框架 avalon 创始人。

## 总结

我参与 Kubernetes 社区，从 Kubernetes 社区中不仅学习到了 Go 语言的开发规范、分布式社区的治理方式，还从社区中的很多优秀工程师身上学到了软件设计的一些技巧，与优秀的开发者交流为我增加了很多见识和经验，这些都是在日常工作中很难得到的。可能与我们平时的工作内容相关，毕竟大部分集中于业务开发，框架的使用。优秀的开源社区和项目中真的是遍地黄金，等着我们去挖掘和学习。加入开源社区吧、后浪们！！！

