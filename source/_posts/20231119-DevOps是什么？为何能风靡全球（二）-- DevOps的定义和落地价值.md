---
title: DevOps是什么？为何能风靡全球（二）-- DevOps的定义和落地价值
tag: "DevOps与研发效能"
date: 2023-11-19
---

上次我们聊到DevOps的诞生背景和发展历程，不熟悉的小伙伴请查看上一篇文章。今天我们主要介绍下DevOps的定义，实施并落地DevOps究竟能带来怎样的价值。

# 01 DevOps定义

首先我们看一下维基百科对DevOps的定义：

DevOps（Development和Operations的混成词）是一种重视“软件开发人员（Dev）”和“IT运维技术人员（Ops）”之间沟通合作的文化、运动或惯例。通过自动化“软件交付”和“架构变更”的流程，来使得构建、测试、发布软件能够更加地快捷、频繁和可靠\[1\]。

可能这个定义有些让人云里雾里，没关系，我们再看一下一些国内外知名企业对DevOps的定义，可能就会有更多的体会。

**微软对DevOps的定义如下：**

DevOps 是开发 (Dev) 和运营 (Ops) 的复合词，它将人、流程和技术结合起来，不断地为客户提供价值\[2\]。

**Atlassian对DevOps的描述如下：**

DevOps 是一套实践、工具和文化理念，可以实现软件开发团队和 IT 团队之间的流程自动化和集成。它强调团队赋能、跨团队沟通和协作以及技术自动化\[3\]。

**Gitlab对DevOps的定义如下：**

DevOps is a combination of software development (dev) and operations (ops). It is defined as a software engineering methodology which aims to integrate the work of development teams and operations teams by facilitating a culture of collaboration and shared responsibility\[4\].

直译下：

DevOps是软件开发 (Dev) 和运维 (Ops) 的组合。它被定义为一种软件工程方法，旨在通过促进协作和分担责任的文化来整合开发团队和运维团队的工作。

**华为对DevOps的描述如下：**

DevOps，即Development and Operations，是一组过程、方法与系统的统称，用于促进软件开发、运维和质量保障部门之间的沟通、协作与整合。DevOps的出现是由于软件行业日益清晰地认识到：为了按时交付软件产品和服务，开发和运维工作必须紧密合作。DevOps可看作开发、运维和质量保障（QA）三者的交集\[5\]。

除了以上网站中对DevOps给出明确的定义外，国内外一些专家也给出了自己的定义。

**Oleg Skrynnik在《DevOps精要：业务视角》\[6\]一书中对DevOps给出以下的定义：**

DevOps是对敏捷软件开发与精益生产思想的演进，应用于IT端到端的价值链中，使得业务基于现代信息技术，并通过文化、组织与技术变革来获得更大的成功。

**石雪峰老师在极客时间《DevOps实战笔记》专栏\[7\]中，也给出了自己的DevOps定义：**

DevOps 是通过平台（Platform）、流程（Process）和人（People）的有机整合，以 C（协作）A（自动化）L（精益）M（度量）S（共享）文化为指引，旨在建立一种可以快速交付价值并且具有持续改进能力的现代化 IT 组织。

一些更多关于DevOps的定义或描述，我们无法在此处穷尽，但是读到这里，我相信大家对DevOps的定义可能已经有了自己的初步认识和理解。**这些定义或描述中提到最多的关键字包括：软件开发、运维、文化、协作、技术、价值，DevOps的核心也正在于此。**

需要指出的是，在近两年的Dora《加速DevOps现状报告》\[8\]中，文化都被赋予了极其重要的地位，拥有生机型文化的团队组织效能高出 30%。与文化息息相关的是员工的幸福感，DevOps倡导通过构建高度信任的、无问责的文化，通过减少重复工作、职业倦怠等来提升员工的幸福感。Dora 的 Core Model对于我们理解DevOps是什么有着重大帮助，Core Model也是Dora数十年研究的重要成果，如下图所示：

![image.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/pLdn5gwZB48BOo83/img/c954890e-40ca-4a65-aec3-96c864bdf50e.png)

从以上分析中，我们可以知道：DevOps的核心之一是文化，文化需要流程和工具支撑，需要重视员工的满意度，实施DevOps的目的是提升软件交付效能、提升团队效能、提升组织效能。为此，结合自己的实践经历，我给出自己对DevOps的理解如下：

**DevOps是一套本身也在持续改进中的方法论，它致力于提升软件交付效能，改善软件从业人员的工作和生存环境，帮助提升组织效能。DevOps运用先进的技术、工程和文化手段，实现平台、流程、人的有机结合，注重持续改进，通过持续提升软件交付效能和员工幸福感，不断为客户创造价值，也帮助公司提升团队效能和组织效能。**

# 02 DevOps能带来什么价值

我们身处在一个充满变动、不确定、复杂、模糊的 VUCA（Volatility、Uncertainty、Complexity、Ambiguity）时代，需要更加快速地应对各种各样的变化，在商业竞争中，先发优势特别明显，适应市场需求，快速投放产品能更大概率地获得客户和消费者的青睐。

这里面其实隐含了三层含义：

1、适应市场需求，这可能需要我们快速试错才能找到真正的需求价值点；

2、快速交付，有一个产品或功能想法产生后，DevOps能够帮助产品快速落地；

3、保证质量，当前各类产品呈现饱和趋势，互联网产品之间更是展开了存量竞争，C端产品都在争夺用户的时间，导致的问题就是用户对产品的要求越来越高，除了产品功能实用以外，体验、质量问题也不容忽视，软件产品一个长时间的宕机可能会给用户造成巨大损失，也可能使公司流失大量的用户，因此质量问题绝不能忽视。

**DevOps正是要保障产品又快又好的交付，既能快速响应市场变化，又能交付高质量产品。**主要表现为：

1、**快：产品交付快。**首先，DevOps基于精益产品的理念，提倡快速交付对用户有价值的产品，投放市场验证，这需要我们基于不断迭代、演进的思想去做产品规划。其次，DevOps吸收了敏捷开发的优秀理念，并立足端到端的价值流打通软件交付全流程，消除开发与运维之间的隔阂，运用持续集成、持续交付等先进工程思想提高交付效率。最后，DevOps提倡协作，不仅是开发与运维之间消除隔阂，DevOps提倡软件交付的各个角色之间都建立良好的协作关系，共筑分享、协作的生机型文化。

2、**好：产品有价值、质量好。**DevOps倡导以客户为中心打造产品，产品有价值，对客户、对用户有益，这样才能更被市场认可，才是真正有价值的产品。团队全员需要贯彻以客户为中心，不仅仅是说说而已。其次，DevOps的质量好也不是说能够完全地消除故障，而是通过内建质量等手段保障不出现重大产品缺陷或故障，内建质量要求团队全部成员对质量负责、质量问题尽量早发现早解决。除了事先控制质量事故，DevOps也提倡通过一切纳入版本控制、快速回滚等手段，做到故障快速回复。DevOps的核心指标——变更失败率、故障恢复时长等，正是DevOps质量相关的关键度量指标。

**DevOps除了能帮助企业又快又好地交付产品，提升团队的软件交付效能，也能更好地激发团队创造力和工作热情。**DevOps不仅注重流程、工具的建设，更重视文化建设，DevOps倡导生机型文化，致力于打造高度协作、风险共担、无问责、持续改进的学习型组织。在这种文化机制下，能激发员工更好的业绩表现，不仅是物质激励，能激发员工创造力的往往更多是精神激励。正如华为任正非先生所说的那样：“如何留住优秀人才？我认为，物质激励不是最主要的，第一点应该是他能找到自己热爱的岗位，当他热爱时，就会踏实工作。”\[9\] 

DevOps本身也包含提升员工幸福感的理念，认为组织或团队应该采用有益于员工的策略，包含减少职业倦怠感，促成满意的工作经历和提高人们创造有价值产出的能力（即生产力）\[10\]。软件生产的灵活性和复杂性之高，很大程度上只能依赖人的能力，实施并践行DevOps文化，对于提升团队效能和组织效能大有裨益。

# 03 总结

今天我们主要聊了DevOps的定义和能带来的价值。当前DevOps在持续发展中，尚未建立业界统一认可的定义，笔者基于当前知名的DevOps定义，结合自己的理解，尝试给出了自己对DevOps的定义：

**DevOps是一套本身也在持续改进中的方法论，它致力于提升软件交付效能，改善软件从业人员的工作和生存环境，帮助提升组织效能。DevOps运用先进的技术、工程和文化手段，实现平台、流程、人的有机结合，注重持续改进，通过持续提升软件交付效能和员工幸福感，不断为客户创造价值，也帮助公司提升团队效能和组织效能。**

实施DevOps对企业来说已经不是一个选择题，大部分企业都在拥抱DevOps或者践行DevOps相关实践。**DevOps能保障产品又快又好的交付，既能快速响应市场变化，又能交付高质量产品。DevOps除了能帮助企业又快又好地交付产品，提升团队的软件交付效能，也能更好地激发团队创造力和工作热情。**实施DevOps大有裨益。

接下来我们会聊下如何实践DevOps的原则和具体实践方法，敬请期待！

参考：

\[1\] [https://zh.wikipedia.org/wiki/DevOps](https://zh.wikipedia.org/wiki/DevOps)

\[2\] [https://azure.microsoft.com/zh-cn/resources/cloud-computing-dictionary/what-is-devops](https://azure.microsoft.com/zh-cn/resources/cloud-computing-dictionary/what-is-devops)

\[3\] [https://www.atlassian.com/zh/devops](https://www.atlassian.com/zh/devops)

\[4\] [https://about.gitlab.com/topics/devops/](https://about.gitlab.com/topics/devops/)

\[5\] [https://support.huaweicloud.com/reference-devcloud/devcloud\_reference\_040101.html](https://support.huaweicloud.com/reference-devcloud/devcloud_reference_040101.html)

\[6\] [https://book.douban.com/subject/35103584/](https://book.douban.com/subject/35103584/)

\[7\] [https://time.geekbang.org/column/article/144204](https://time.geekbang.org/column/article/144204)

\[8\] [https://dora.dev/research/](https://dora.dev/research/)

\[9\] [https://finance.sina.cn/chanjing/gsxw/2023-09-04/detail-imzkpswe2465965.d.html](https://finance.sina.cn/chanjing/gsxw/2023-09-04/detail-imzkpswe2465965.d.html)

\[10\] [https://dora.dev/research/2023/](https://dora.dev/research/2023/)