---
title: DevOps是什么？为何能风靡全球（一） -- DevOps的诞生和发展历程
tag: "DevOps与研发效能"
date: 2023-11-01
---

你好，我是程序员Aike。今天，我们来聊一聊DevOps。

相信不少人听说过DevOps这个词，甚至对DevOps如雷贯耳，但是你真的了解DevOps吗？DevOps是指CI/CD吗？DevOps又是如何诞生的呢？DevOps究竟要解决的是什么问题？DevOps又是提供什么样的方法去解决这些问题呢？DevOps能风靡全球的秘密到底是什么呢？我将尝试带你去找到这些问题的答案，开启一场DevOps的探索与发现之旅。

本篇是系列文章的第一篇，今天我们主要聊下DevOps的诞生和发展历程，后续再进一步拆解以上问题，敬请期待！

# 01 DevOps的诞生

## 瀑布式开发模式

在正式谈DevOps之前，我们可以先聊一聊早期的软件开发模式——瀑布式开发。瀑布式开发，又称“瀑布（Waterfall）模型”，是软件开发中最早出现的模型之一。整个软件开发流程严格遵循需求、设计、开发、测试、部署、维护几个阶段。在这个流程中，需要等上 一个阶段工作完成后，才会进行下个阶段的工作。例如：开发工程师会把需求的代码全部开发好，才给到测试人员进行验证，最后交给运维工程师部署上线。在这种模式下，项目开发的进程由是从一个阶段“流动”到下一个阶段，如同瀑布流水一般，因此被称为瀑布模型（Waterfall Model）。如下图所示：

![image.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/jP2lRmeNXPpAO8g5/img/285ef412-bfa4-45c9-810f-54338cec3bba.png)

（图片来自网络）

瀑布式开发模式流行于20世纪70年代，是由软件开发大师温斯顿·罗伊斯（Winston Royce）最初提出的软件开发模型，作为最早出现的软件开发模型，它在软件工程中占有重要的地位。

瀑布模型基于工程学的理念将整个过程分成不同的阶段，提供了软件开发的基本框架，便于人员间的分工协作。同时，也可以对不同阶段的质量和成本进行严格把控。强调文档，前一个阶段的输出就是下一个阶段的输入，文档是各阶段衔接的唯一信息。但在这种模式下也存在着一些缺陷，产品迭代的频率经常是以月为单位来进行，更甚者可达半年到一年时间，这导致的风险就是需求无法得到快速验证。

随着软件行业和互联网的快速发展，软件开发在企业中的地位变得愈加重要，软件不再仅仅是为业务提供支持，而是成为业务本身不可或缺的组成部分。与此同时，针对市场的快速变化和响应成为了新的目标。

在这种场景下，有可能团队花费数月开发的东西早已经不符合市场的需要，这不仅仅是对人力资源的浪费，也会严重影响企业的发展进程。渐渐地，大家开始发现这种笨重的模式难以适应业务的需要，我们得有一种新的模式来满足需求。

于是，敏捷开发（Agile）开始登上舞台。

## 敏捷开发模式

基于这种问题，敏捷的思潮开始兴起。2001年，Kent Beck，Martin Fowler 等17位著名的软件专家联合发起一场聚会，共同讨论当前的问题并尝试找出解决方案。这次聚会的成果就是著名的《敏捷宣言》\[1\]。

敏捷宣言的内容如下图所示：

![image.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/jP2lRmeNXPpAO8g5/img/f94992cf-c240-4d5e-b026-101eda04aa29.png)

敏捷宣言遵循的十二条原则\[2\]如下：

1、我们最重要的目标，是通过持续不断地及早交付有价值的软件使客户满意。

2、欣然面对需求变化，即使在开发后期也一样。为了客户的竞争优势，敏捷过程掌控变化。

3、经常地交付可工作的软件，相隔几星期或一两个月，倾向于采取较短的周期。

4、业务人员和开发人员必须相互合作，项目中的每一天都不例外。

5、激发个体的斗志，以他们为核心搭建项目。提供所需的环境和支援，辅以信任，从而达成目标。

6、不论团队内外，传递信息效果最好效率也最高的方式是面对面的交谈。

7、可工作的软件是进度的首要度量标准。

8、敏捷过程倡导可持续开发。责任人、开发人员和用户要能够共同维持其步调稳定延续。

9、坚持不懈地追求技术卓越和良好设计，敏捷能力由此增强。

10、以简洁为本，它是极力减少不必要工作量的艺术。

11、最好的架构、需求和设计出自自组织团队。

12、团队定期地反思如何能提高成效，并依次调整自身的举止表现。

敏捷开发开始逐步走到了历史舞台的中央，敏捷意味着效率的提升，相比于传统的瀑布开发，敏捷开发实行的是一种更加快捷的做法。敏捷的核心理念是：将一个大的目标不断拆解，把它变成一个个可交付的小目标，然后通过不断迭代，以小步快跑的方式持续开发。敏捷之所以更快，根本原因在于持续迭代和验证节省了大量不必要的浪费和返工。具体如下图所示：

![image.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/jP2lRmeNXPpAO8g5/img/401f5ae0-e417-48e5-88f5-250121566e38.png)

（图片来自网络）

可以说，满足敏捷宣言和十二条原则的实践都属于敏捷开发的实践，著名的实践有Scrum\[3\]、极限编程\[4\]和看板方法\[5\]等。这些方法的优秀实践影响深远，极限编程就是要把编程的实践推向极限，激励着每一位开发者前行。

敏捷开发可以更快地发现问题，从而进行更快的响应。可以说，敏捷开发方法是传统瀑布式开发方法的合理补充，是应对未来市场或需求多变场景的良好实践。尽管敏捷开发（Agile Development）提升了开发的效率，但它的范围仅限于开发和测试阶段，并没有覆盖到部署、运维，因此运维部门并没有在这其中得到受益，运维与开发还是会出现互相指责的情况。为化解这个矛盾，就出现了DevOps。

## DevOps

DevOps应该算是目前各大技术社区最火的概念之一了。我们先用一张图直观地展示下DevOps下软件开发模式相比瀑布式开发和敏捷开发的异同。如下图所示：

![image](/img/devops-01.png)

从上图中可以直观地看到，DevOps与敏捷开发最大的不同点就在于，对软件进行多次、频繁的部署来避免软件部署难的问题。DevOps的提出，最开始也确实是为了打破开发和运维之间的对立和隔阂。

DevOps完善了敏捷开发存在的短板，实现了真正的软件交付全流程闭环。在 DevOps 的模式下，开发和运维都不再是“孤立”的团队，两者会在软件的整个生命周期内相互协作，并在工作中得到紧密地配合。而由此带来的效益，则是更加高效的服务交付和质量。DevOps流程如下图所示：

![image.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/8K4nyar7vKo3nLbj/img/5dfc2696-cbe2-4637-b699-9faf24ff0946.png)

（图片来自网络）

# 02 DevOps发展历程

那么，DevOps究竟是如何发展到今天的火热程度的呢？我们来扒一扒DevOps这些年走过的发展历程。

2009年召开的第二届Velocity会议上，会议上最大的亮点是一个题为 _10+ Deploys Per Day: Dev and Ops Cooperation at Flickr_ 的演讲\[6\]，这个演讲的内容可以被视为DevOps萌芽的标志，在这个演讲中提出了以业务敏捷为中心，构建适应快速发布软件的工具和文化的论点。

同年10月，Patrick Debois 在比利时召开了第一届DevOpsDays大会，大会获取了巨大的成功，会议结束后大家在Twitter上持续讨论，去掉了Days，只保留了DevOps，于是DevOps这个称谓正式诞生了。

2010年，《持续交付：发布可靠软件的系统方法》的作者 Jez Humble 参加了第二届DevOpsDays会议\[7\]并做了关于“持续交付”的演讲，也可以解决开发和运维的问题。关于什么是DevOps，一直众说纷纭，The Agile Admin上，也发布了一篇名为“What is DevOps”的文章\[8\]，得到了大家的广泛认可。文中给出了详细的DevOps的定义，并构建了DevOps的一系列价值观、原则、方法、实践，以及对应的工具。该文也梳理了DevOps的历史并对DevOps的一些误解进行了澄清。

之后，DevOps的影响持续扩大，当前早已不再只是开发和运维的范畴。一些主要的发展历程摘要如下：

1、2013年，《The Phoenix Project》书籍出版，是世界上最畅销的DevOps相关的书籍；

2、2014年，Dora 开始持续发布《加速：DevOps现状报告》（2020年因疫情等原因未发布）\[9\]，这份报告是DevOps的最珍贵学习资源之一，也对DevOps普及起到了关键的推动作用；

3、2016年，《DevOps Handbook》出版，详细阐述了著名的DevOps实践三步法；

4、2017年，国内举办了首届DevOpsDays大会，DevOps 正式在国内驶入了发展的快车道；

5、2018年，中国DevOps社区正式成立，积极推动DevOps在国内的发展；

6、2019年，中国信息通信研究院牵头《中国DevOps现状调查》，致力于推进国内DevOps发展。

在发展过程中，DevOps 也成为一种文化，一种运动，一种实践，凡是有益于软件交付的思想和方法，好像都可以被DevOps吸收，DevOps不再只是敏捷开发的延伸，而是以C（文化）、A（自动化）、L（精益）、M（度量）、S（共享）为原则，旨在提高软件交付效能、团队效能，改善组织效能的重要方法和实践。

中国信通院也起草了《研发运营一体化（DevOps）成熟度模型》\[10\]，标准中对DevOps的总体架构描述如下图所示：

![image.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/jP2lRmeNXPpAO8g5/img/c1152dee-18ab-4655-84b4-aac600a96789.png)

标准中，把DevOps过程分为敏捷开发、持续交付、技术运营三大模块，覆盖软件交付的方方面面，这也很好地证明了当前DevOps覆盖范围相当全面和广泛。

# 03 总结

本篇我们主要介绍了DevOps的诞生和发展历程，在敏捷开发、精益等思想盛行之后，运维侧进行软件部署的压力更大了，这就迫切需要一种新的软件交付模式解决开发与运维之间的隔阂和对立，DevOps因此应运而生。

瀑布式开发构建了软件工程发展的基础，敏捷开发则指导我们更快更好地开发软件，也极大地促进业务人员与开发人员之间问题的解决，DevOps则覆盖了软件交付的最后一公里——软件部署和运维。国内外众多软件开发和运维专家，为DevOps发展作出了卓越的贡献，也推动着DevOps不断前行，本文中也介绍了DevOps的起源和发展历程。

DevOps是集大成者，覆盖了软件交付的全流程链路，囊括了敏捷开发、持续交付、技术运营等领域，注重软件产品端到端的价值交付。不仅如此，DevOps还倡导一种协作、共享的文化，关注并注重人的感受，倡导建设生机型文化。也正是因为DevOps覆盖广，业界对DevOps的比喻往往用“盲人摸象”来形容，直至今天，也没有一个确切的所有人都认可接受的DevOps定义。

后续我们就再聊下DevOps的定义、DevOps能给企业带来什么样的价值和DevOps的落地实践路径，敬请期待！

参考：

\[1\] [https://agilemanifesto.org/iso/zhchs/manifesto.html](https://agilemanifesto.org/iso/zhchs/manifesto.html)

\[2\] [https://agilemanifesto.org/iso/zhchs/principles.html](https://agilemanifesto.org/iso/zhchs/principles.html)

\[3\] [https://book.douban.com/subject/5334585/](https://book.douban.com/subject/5334585/)

\[4\] [https://book.douban.com/subject/6828074/](https://book.douban.com/subject/6828074/)

\[5\] [https://book.douban.com/subject/25788807/](https://book.douban.com/subject/25788807/)

\[6\] [https://www.slideshare.net/jallspaw/10-deploys-per-day-dev-and-ops-cooperation-at-flickr](https://www.slideshare.net/jallspaw/10-deploys-per-day-dev-and-ops-cooperation-at-flickr)

\[7\] [https://devopsdays.org/](https://devopsdays.org/)

\[8\] [https://theagileadmin.com/what-is-devops/](https://theagileadmin.com/what-is-devops/)

\[9\] [https://dora.dev/research/](https://dora.dev/research/)

\[10\] [https://std.samr.gov.cn/hb/search/stdHBDetailed?id=C362B3DB6202A067E05397BE0A0A1ED8](https://std.samr.gov.cn/hb/search/stdHBDetailed?id=C362B3DB6202A067E05397BE0A0A1ED8)