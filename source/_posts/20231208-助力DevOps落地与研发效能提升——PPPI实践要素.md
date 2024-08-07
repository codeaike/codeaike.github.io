---
title: 助力DevOps落地与研发效能提升——PPPI实践要素
tag: "DevOps与研发效能"
date: 2023-12-08
---

今天，我们来聊一聊DevOps与研发效能的实践框架。

DevOps是提升研发效能的重要手段和实践，研发效能与Devops密不可分，提升研发效能的优秀实践，大多可以从DevOps体系中汲取营养和养分。在谈研发效能的实践框架之前，我们先聊一聊DevOps的三大支柱和实践框架。

# 01 DevOps的三大支柱

DevOps有三大支柱，即人（People）、流程（Process）、平台（Platform），这三大支柱之间相互依存、相互促进，两两结合构建起DevOps文化和工具，指明了落地实施DevOps的行动方向。

![image](/img/devops-ppp.png)

**人 + 流程 = 文化**

在具体的流程之下，人就会形成一套行为准则，而这套行为准则会潜移默化地影响需求从设计到交付的方方面面。这些行为准则组合到一起，会构成了企业内部的文化。

**流程 + 平台 = 工具**

企业的流程需要标准化，标准化之后可以通过平台来实现，这样流程就能逐渐自动化，这个过程中就沉淀了许多能够解决实际问题的工具。通过使用DevOps工具，团队成员可以更高效地进行协作和沟通，同时也可以提高软件的质量和可靠性。

**人 + 平台 = 赋能**

通过使用DevOps平台和工具，团队成员可以更好地发挥自己的技能和能力，提高工作效率和质量。平台通过沉淀固化的流程和好的实践，可以指导、赋能团队成员更高效地开展工作。

# 02 DevOps实践的三步工作法和CALMS框架

## DevOps三步工作法

谈到DevOps实践，不得不提大名鼎鼎的DevOps三步工作法，《DevOps实践指南》中定义了流动、反馈、持续学习和实验的DevOps实践三步工作法\[1\]。

**第一步：流动原则，建立从左至右快速的、平滑的、能向客户交付价值的工作流。**核心实践包括工作可视化、限制在制品数、减小批量大小、减少交接（沟通、委派、通知、协调等）次数、持续识别和改善约束点、消除日常工作价值流中的困境和浪费。

**第二步：反馈原则，在从右向左的每个阶段中能够快速、持续地获得工作反馈。**建立快速的反馈机制，对于实现技术价值流中的高质量、可靠性和安全性至关重要。为此，要在问题发生时识别问题、群策群力解决问题并构建新的知识，在源头控制质量，并且不断地为下游同事（如开发的下游是运维）的工作中心做优化。

**第三步：持续学习与实验原则，建立持续学习与实验的文化，通过应用三步工作法，能够持续提升个人技能，进而转化为团队和组织的财富。**技术价值流的核心是建立高度信任的文化，每个人都是持续学习者，必须在日常工作中承担风险、从成功和失败中积累经验教训，所有局部的经验都会快速转化为全局性的改进，帮助整个组织尝试和实践新技术。

持续学习和实验，要求我们建立学习型组织和安全文化。Ron Westrum 博士定义了三种类型的文化，包括：

1、病态型：组织中存在大量恐惧和威胁，由于政治原因，个体为了保全自身利益，通常会隐瞒真相或者歪曲事实。在这种组织中，故障和事故经常被隐瞒。

2、官僚型：组织中规则和流程僵化，所有部门通常都“自扫门前雪”。在这种组织中，通过评判系统处理事故，结果往往恩威兼施。

3、生机型：**生机型组织的特点是积极探索和分享信息，让组织更好地履行使命。在这种组织中，整个价值流中所有的员工共同承担责任，对事故进行积极反思，并进行真正的根因调查。**

持续学习和实验还**要求组织将日常工作的改进制度化和标准化、善于把局部发现转化为全局优化和沉淀知识库、在日常工作中注入张力**，比如在技术价值流中缩短前置时间，预演大规模故障等验证系统的可靠性是否达到了预期。领导层也要强化学习文化，必须强调解决问题的能力和学习的价值。为团队创造条件，让团队能在日常工作中感受到价值和卓越，这需要领导者和员工们共同的努力，每个人都相互依存，缺一不可。

## CALMS框架

CALMS 框架可用于评估公司采用 DevOps 流程的能力，同时也是在 DevOps 转型期间衡量是否成功的一种方法。该首字母缩写词由《DevOps 实践指南》的合著者 Jez Humble 提出，且分别代表文化 (Culture)、自动化 (Automation)、精益 (Lean)、测量 (Measurement) 和分享 (Sharing)\[2\]。

**文化**

DevOps 不仅是一个流程或另一种开发方法，而是一种文化变革。DevOps鼓励团队建立生机型文化，DevOps 文化的一个重要组成部分包括：协作、以用户为中心、知识共享、风险共担、无指责的回顾等等\[3\]。2023加速DevOps现状报告中指出，拥有生机型文化的团队的组织效能高出 30%，以用户为中心的团队组织效能高出 40%\[4\]。

**自动化**

DevOps 的一个重要实践是尽可能实现软件开发生命周期的自动化，让开发人员能够专注于写代码和开发新功能。自动化是 CI/CD 流水线的关键要素，有助于减少人为错误并提高团队的生产力。通过自动化流程，团队可以在较短的迭代周期内持续改进，从而快速响应客户反馈。

**精益**

在软件环境中，精益意味着消除低价值的活动和快速流动，也就是变得朝气蓬勃且工作敏捷。精益意味着接受失败是不可避免的。不要试图阻止或惩罚失败，你应该把它当作一个学习的机会。与 DevOps 更为相关的是持续改进和接受失败的概念，这为实验性思维奠定了基础。

**测量**

我们需要数据指导和洞察我们的迭代是否有效，是否真正达到了预期的效果。组织效能、团队效能、软件交付效能等各方面都要度量。加速DevOps现状报告中使用的四大指标，包括：变更前置时间、部署频率、变更失败率、故障恢复时间，覆盖效率和质量两方面，是衡量软件交付效能的业界公认指标。然而，组织效能、团队效能的测量则更加困难，与各组织团队所处的环境、阶段以及目标息息相关，需要更加灵活地进行指标设计和测量。

**分享**

DevOps 转型需要实践、文化理念和工具的融合。打破开发和运维孤岛的诸多好处非常值得尝试转型：提升信任度、加速软件发布、更可靠的部署以及团队和客户之间更好的反馈回路。实施 DevOps 并非易事。但是，只要有正确的思路、努力和工具，组织就可以进行 DevOps 转型，从而带来显著收益，分担责任和共享成功对弥合分歧大有助益。这催生了“谁构建，谁运行”的理念，开发人员更熟悉软件本身，也提倡承担测试、部署等更多任务。

## DevOps实践的其他原则

除了DevOps三步工作法和CALMS框架，关于DevOps实践，还有一些重要的原则，包括：**以客户为中心、以目标为导向等。**DevOps 团队与客户和最终用户之间使用短程反馈回路，从而能围绕用户需求快速开发产品和服务。DevOps 团队不应该脱离实际，基于对消费者会如何使用软件的臆测来开发产品，应真正理解用户需求，并创造出能解决实际问题的产品或服务。**定义DevOps实践要实现的目标至关重要，不仅是软件工程和交付效能的目标，更需要定义产品和业务目标。**

# 03 平台工程

平台工程是什么？平台工程是设计和构建工具链和工作流的学科，为云原生时代的软件工程组织提供自助服务能力。平台工程师提供了一个集成的产品，通常被称为“内部开发人员平台”，涵盖了应用程序整个生命周期的操作需求\[5\]。

平台工程的提出得到了开发者的支持，我认为一个重要的原因是平台工程更**关注开发者体验**，而不只是说：开发人员应该能够部署和运行他们的应用程序和服务端到端，“你构建它，你运行它”。平台工程团队将所有技术和工具结合在一起，为开发人员铺平黄金之路，平台工程团队要打造一款内部开发人员使用的产品，这款产品拥有自服务、自助式工作流等特点，开发人员只需要简单的操作，而不用关心背后的细节。

平台工程的核心目标是提升一致性和效率，提升工具和配置的可重用性。平台工程团队要通过一遍又一遍地解决共同的问题来防止内部的其他团队重新发明轮子，要警惕个性化需求，这对能否建设好平台工程很重要。如果平台不够聚焦通用问题，或者承接过多个性化需求，平台工程可能很难建设好，也不能达成提升研发一致性和效率的目标。

平台工程是软件工程中最大的趋势之一，PlatformCon 2022——有史以来的第一个平台工程大会——吸引了超过6000名参与者。平台工程也有利于提高研发效率\[6\]。Gartner 在近几年的技术趋势报告中，也均包含了平台工程的相关内容\[7\]。

# 04 研发效能

研发效能这几年的热度直线飙升，这离不开国内研发效能专家的贡献和持续输出。国内的研发效能取得了丰硕的成果，国内专家联合并起草了“研发效能宣言”\[8\]，主要内容如下：

![image.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/8K4nyar7vKo3nLbj/img/71bb6bbe-4271-4826-a1f7-5a5a9dbdf9e4.png)

在《软件研发效能权威指南》一书中，茹炳晟和张乐老师也详细阐述了研发效能的实践框架——研发效能的“黄金三角” 和 研发效能平台的“双流”模型，为研发效能的建设和实践之路指明了方向\[9\]。

书中也对研发效能给出了清晰完整的定义：**研发效能就是更高效、更高质量、更可靠、可持续地交付更优的业务价值的能力。**“更高效”指的是效率，“更高质量、更可靠、更优的业务价值”指的是有效性，也要关注“可持续”，期望研发效能可以让我们保持持续的有效性和高效性。

DevOps与研发效能的关系是什么？我的理解是，DevOps是提升研发效能的重要手段和实践，DevOps是实践、是运动、是一场探索之旅，研发效能是目标。

# 05 DevOps与研发效能实践落地难

DevOps与研发效能的落地不是一件容易的事，特别是国内企业，虽然DevOps普及率越来越高，但是中国信息通信研究院发布的《中国DevOps现状调查报告（2023）》，企业实践成熟度为优秀级及以上的比例为18.68%，六成企业达到DevOps成熟度全面级。

不少国外的优秀实践在国内落地时，出现水土不服的情况，当前的DevOps理论和时间框架也在持续发展，尚未完全成熟，组织不清楚DevOps的路线图。管理层看不到DevOps的价值投入较少，即使投入也很难把DevOps转型或研发效能作为战略长期投入，这让需要持续投入才能取得更好效果的DevOps和研发效能工作难以实施。根据《中国DevOps现状调查报告（2023）》，阻碍国内企业DevOps转型的主要因素包括行业限制、组织不清楚DevOps路线图、无从下手、缺少管理层支持等原因，详见下图：

![image.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/8K4nyar7vKo3nLbj/img/8ddc6809-dee2-4390-8339-345363c31bb6.png)

当然，这里存在一个前提条件，就是定义DevOps实践成功的标准，根据《中国DevOps现状调查报告（2023）》，多数企业把DevOps实践成功的标准聚焦在按时交付、研发和交付效率的提升、业务成功、客户/用户满意度等四个方面。详见下图所示：

![image.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/8K4nyar7vKo3nLbj/img/69648e6a-f9bb-4788-81b0-f3a2c59461db.png)

幸运的是，当前开源和商业领域已积累足够多的DevOps平台、工具和产品，可以基于此快速搭建满足企业需求和现状的DevOps平台和落地实践体系，这可以帮助企业快速地构建CI/CD的基础能力，帮助企业提升软件交付能力，这是开启DevOps之旅的重要一步。不过需要意识到，这只是企业实施DevOps和提升研发效能的起点，企业要持续提升自身的组织效能和团队效能，构建匹配企业发展的生机型文化，**不断挑战更高的DevOps转型目标，持续提升组织效能和客户满意度。DevOps实践落地不仅是建设平台工具，更是构建文化，DevOps和研发效能的持续改进之路没有终点**。

## 06 助力DevOps落地与研发效能提升——PPPI实践要素

在长期从事研发效能工作的过程中，我对在企业中落地DevOps和研发效能提升沉淀了自己的理解和深度思考，基于以上DevOps实践的三大支柱和实践原则，我提炼出个人认为最关键的几点，即平台（Platform）、流程（Process）、人（People）和持续改进（Improvement），组成DevOps落地与研发效能提升的PPPI实践要素（以下简称PPPI）。我认为该框架更有利于帮助企业落地实践DevOps和提升研发效能，特别是中小企业，能直接投入DevOps与研发效能工作的资源有限，该框架能够帮助企业快速构建好的DevOps基础体系，通过持续改进循序落地DevOps，提升研发效能。

企业需要打造适合组织和团队的生机型文化，通过提升员工工作满意度激发团队活力与创造力，构建适合企业现状和特点的有特色的研发流程。通过标准化覆盖软件研发全生命周期的流程和实践，并固化到研发平台中，赋能所有团队成员高效开展工作。在充满生机的文化中，团队成员会主动沟通并持续改进研发流程和平台工具，形成人、流程、平台的持续学习与改进的正向循环，持续提升公司组织效能、团队效能和研发效能水平，助力公司达成商业目标。这也是 PPPI 实践要素的核心出发点、立足点。

**PPPI 由平台（Platform）、流程（Process）、人（People）和改进（Improvement）的英文首字母组成，人、流程、平台构成持续改进的正向循环。PPPI简单来说就是，建平台、定流程、重人性、持续改进。平台为核心，承载团队标准化流程和集体的智慧，赋能并兜底约束团队成员的日常工作和行为，提升工作一致性，提高质量和效率，降低沟通、不必要的工具建设等成本。人使用平台减少人为失误，提高日常研发工作效率，并从成功和失败中持续总结经验改进并完善流程。流程不断完善后，成为公司开展此项工作的唯一标准，当然也需要保障一定的灵活性，有了标准就可以指导平台落地，集体智慧的结晶持续沉淀到平台。通过平台又可以赋能、兜底约束更多的人按照标准执行，这样就形成了人、流程、平台的持续学习与改进的正向循环。**PPPI 实践框架具体如下图所示：

![image.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/8K4nyar7vKo3nLbj/img/1e63d095-5b98-461b-9ab4-914c9f5a902c.png)

## 平台

平台是公司好的流程、好的标准、好的研发实践的载体，公司的研发效能实践以研发和交付效率的提升、业务成功、客户/用户满意度为目标，平台是核心，平台承载优秀流程实践，提升软件研发工作的一致性，兜底避免基础错误。平台赋能团队成员，尤其是新员工，保障工作质量的下限，兜底约束研发人员的日常行为，牵引日常工作高效开展。为了让开发、测试、运维人员可以专注自己的工作，我们需要建设高效的内部开发协同平台，完善的内部研发平台需具备以下特征：

1、自助化使用：内置自服务工作流程。产品、研发、测试、运维人员可以方便的从平台上获取自己想要的服务或资源，谨记“不要阻塞研发”这一核心原则，能够提升团队成员的工作满意度。

2、沉淀集体智慧：平台是公司积累的集体智慧的结晶，沉淀了标准化的先进研发和日常工作流程，能够不断提升团队水平，也帮助新成员快速上手工作。

3、标准化工作流：协同各角色高效工作，通过内置规则兜底约束行为、同时必须兼顾灵活性与人的个性。

（1）能够协同各种角色高效工作，减少不必要的沟通等产生的浪费。在这个平台中每个人有自己的任务管理和提醒帮助，可以高效完成自己的事情。各个角色无需关心自己进行软件工作所使用的基础设施，工作流是按照平台内置的规则流动的。业务开发人员每天拿到需求进行开发，使用的服务

（2）按照一套通用的标准提升软件研发过程的一致性，保障质量和效率，当然也要兼顾灵活性，比如不同团队遵守不同的标准、不同的角色适用不同的标准、不同的个体也需要允许个性，这需要权衡，既能保障底线，又不对团队形成太强的约束，让标准更好地服务于日常工作。还有一点，能够通过平台内置规则兜底约束不规范的行为，这些规范是团队从成功和失败的工作中逐步沉淀的，平台能够减少人为因素导致的意外错误。

4、工程卓越：一站式、一体化的内部研发平台，通过产品化、场景化、生态化满足公司不同团队角色、不同场景的需求，如对开发人员可以提供服务脚手架串联起整个研发交付流程。一站式的平台也能够帮助团队进行数据度量，一站式的平台已用于统一数据口径，收集数据，计算数据，自动化核心流程保障数据正确性，从而帮助团队有效实施效能度量，指引团队不断弥补短板并持续改进。需要重点指出的是，做平台也不是什么功能都要做，要打造通用平台，减少各团队重复建设，覆盖基础的、核心的流程，打造生态，利用插件化等技术手段打造开放的平台能力，集成优秀的研发效能工具为我所用。平台实施应该有专门的团队负责，这样有利于平台的可持续发展。

说到这里，你可能会说，这门槛太高了，这很难实践下去，的确，建设完善的平台的成本很高，从需求到交付，再到监控运营的链路很长，一年半载都很难建设成功。这就需要我们分阶段进行，我们要清楚地知道我们的目的地在哪里，向着平台工程的方向迈进，但是可以先快速迭代搭建满足需求的产品。平台工程实现可大致分为三个层次：

第一个层次是：只对软件交付的部分流程负责，比如使用开源工具建成一个CI/CD平台或工具，业界好的开源产品很多，如Gitlab-CI、Argo等，可自行选取；

第二个层次是：对软件交付的全生命周期和交付效能负责，打造一站式、自助化平台工程；

第三个层次是：不仅对软件交付效能负责，也能洞察业务价值，对各个产品和需求的业务价值全方面评估和监控，可进行商业数据分析和洞察等。

如果我们的目标是提高交付效率，那实现第一个层次的平台，并不会花费太多资源和时间，实施的关键是平台要承载契合公司现状和特点的流程。

## 流程

DevOps贯穿软件研发的全生命周期，包括需求计划、编码、构建、测试、打包、部署、运营、监控的整个流程，如下图所示：

![image.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/8K4nyar7vKo3nLbj/img/5dfc2696-cbe2-4637-b699-9faf24ff0946.png)

（图片来自网络）

研发效能的流程建设需要覆盖软件研发的方方面面，软件研发的活动尽管大多是脑力劳动，但是也有基本的流程可循。企业可以基于业界优秀实践，结合团队现状打造公司特色的高质量流程，将这些流程持续迭代后进行标准化，形成公司研发标准流程规范，有了这些流程规范也方便指导平台落地。举个例子，需求管理中好的实践包括看板方法、Scrum等，好的工具包括Jira等，基于Jira也有一系列优秀的需求管理方法和实践，但是这些哪些是适合团队的，这跟公司所处的阶段、高层的认识、团队的接受度、人员水平等多种因素相关，业界优秀方法往往不能拿来主义，必须结合团队现状持续改进优化，才能起到更好的效果。

研发流程的建设要遵守以下几个原则：

1、先全局、再局部，先通用、再具体。首先应该关注的是研发全流程，DevOps实施第一步就是流动，不要忽略全局优化。建设流程时，可先达成通用流程的共识，比如需求管理中怎么收集需求、分析需求、评审需求、需求开发、需求验收等步骤的整体流程，而不是上来就规定需求必须按照用户故事粒度拆分，必须能在一周内开发完成，虽然这也是很好的实践，但是很可能一上来团队不能很好适应。

2、团队对基本流程要达成共识，形成标准流程文档，并定期审查更新文档。基本流程还是比较容易达成共识的，比如开发流程中，编码之前需要先设计技术方案，技术方案包括整体设计、接口设计、数据库设计等要素，开发提交测试前需要自己进行冒烟测试等等。这些基本的流程达成共识后，要形成标准流程文档，并定期审查更新文档保障文档不过时。现在基于大模型的能力，这些文档输入到模型中，能构建出企业的专用研发效能专家，可以大大降低团队的沟通成本。2023加速DevOps现状报告\[4\]中，也指出好的文档能带来25%的组织效能提升，可见文档多么重要。

3、结合业界研发效能实践和公司现状制定研发流程，试点团队落地后再逐步推广。研发流程的建设并不容易，所以我们要保障研发流程的先进性和适应性，为此，我们需要找试点团队落地，验证流程可行后才能大范围推广。

4、重视人性，研发流程要为研发人员服务，不要变成枷锁。流程能指导、规范人的行为，但在研发流程标准化的过程中，一个重要误区就是忽略对人的关注，标准化势必对人产生约束，所以让人认同很重要，认同后流程将不再是约束，将促使团队构建一致的行为准则，形成团队文化，让流程为人服务很重要。

5、保障研发流程改进的通道顺畅。防止流程腐化的一个重要措施是持续改进研发流程，我们需要构建一个研发流程改进的流程，让每个人都能提改进意见，给当前的研发流程持续注入张力，使研发流程充满生机与活力。

## 人

研发效能的重要因素是人，因为软件研发是一场智力活动，产品计划需要人去想去做，开发编码需要开发人员去设计、去思考，测试方案和用例需要测试人员发挥主观能动性去想方设法覆盖更多测试场景，线上运维也需要运维人员慎之又慎去操作才能避免意外的发生。因此如果失去了对人的关注、员工失去了安全感和幸福感，研发效能必然很低。

除此之外，平台和流程也是人去构建的，如果没有人这一切无从谈起。那你可能会问，你还把平台放到第一位？因为针对整个研发效能体系来讲，是需要少部分精英人才去引领大多数人的，平台和流程的建设不是每个人都会真正参与建设的，这样的话，好的平台就能发挥更大的杠杆作用，主要平台做得足够好，大多数人都能很好的在平台上完成自己的工作，那么就相当于精英人才的经验通过平台持续赋能给大多数人了，这样团队和组织效能能达到更大程度的提升。

但是平台不能囊括所有的工作，软件研发工作也不可能变成标准的流水线操作，充分激发人的主观能动性才能得到更大的研发效能。那么如何激发人呢？管理学等学科中有很多好的方法和实践。根据马斯洛的需求层次理论，激发人不仅仅需要物质激励，安全感、归属感等精神激励，对成就感的追求更是相当重要。因此，首先要给予员工足够的信任，给予足够的自由度，不要让流程阻塞研发人员的日常工作，团队要足够开放包容，构建生机型文化非常重要，也要善于让每个人聚焦专注自己感兴趣或擅长的领域，这样能更大程度地激发人的主观能动性，这样就为持续地改进流程、完善平台打下了很好的基础。

## 持续改进

是不是我引入了好的流程、建成了好的平台，每个人工作都有干劲，我就完成了研发效能落地工作，DevOps就成功了呢？当然没有，研发效能的持续改进工作永无止境。我们总能找到一些可以优化的点，去改善工作的现状，助力达成更高的软件交付效能和团队效能，这也是我们持续追求卓越的工程师精神的良好体现。

我们可以按照PDCA循环\[11\]持续改进我们的工作，PDCA循环的含义是将质量管理分为四个阶段，即Plan（计划）、Do（执行）、Check（检查）和 Act（处理），更多的资料大家可以自行查阅。

 在持续改进的过程中，我们同样不要为了局部优化而忽略全局优化，价值流图（VSM）\[12\]的梳理和优化是我们开展持续改进工作很好的开始。

我们当然也可以采用研发效能度量来帮助我们进行持续改进工作，我们需要一些数据作为抓手，但是我们需要慎用度量，不能忽略古德哈特定律对度量的影响。同样的，业界也有度量的一些优秀指导\[13\]，此处就不做进一步展开了。

# 07 总结

本篇文章中，我们介绍了DevOps的三大支柱、DevOps实践三步法和CALMS框架，也对平台工程、研发效能的概念做了简单阐述，提出了助力DevOps落地与研发效能提升——**PPPI实践要素，即****平台（Platform）、流程（Process）、人（People）和改进（Improvement），简单来说就是，建平台、定流程、重人性、持续改进。**平台承载优秀流程实践，提升软件研发工作的一致性，兜底避免基础错误；流程持续优化，形成标准化实践，指导平台落地；人作为重要因素，激发主观能动性，持续优化流程，完善平台。平台、流程、人相互促进，形成持续改进良性循环。抓住平台、流程、人、持续改进这四点核心，想清楚企业研发效能落地要达到的目标，小到改善研发提测流程，大到成为研发效能卓越组织，DevOps和研发效能落地不会走偏。

DevOps与研发效能的实践漫漫长路，我们都在积极地探索，每年的加速DevOps报告为我们提供了重要的参考，也是DevOps和研发效能领域极其珍贵的资料，DevOps与AI大模型的结合，是否会重塑研发效能新模式，值得期待！

参考链接：

\[1\] [https://book.douban.com/subject/30186150/](https://book.douban.com/subject/30186150/)

\[2\] [https://www.atlassian.com/zh/devops/frameworks/calms-framework](https://www.atlassian.com/zh/devops/frameworks/calms-framework)

\[3\] [https://dora.dev/devops-capabilities/cultural/generative-organizational-culture/](https://dora.dev/devops-capabilities/cultural/generative-organizational-culture/)

\[4\] [https://dora.dev/research/2023/](https://dora.dev/research/2023/)

\[5\] [https://platformengineering.org/blog/what-is-platform-engineering](https://platformengineering.org/blog/what-is-platform-engineering)

\[6\] [https://www.infoq.cn/article/TbxS2My9fOIL1GMpHjKD](https://www.infoq.cn/article/TbxS2My9fOIL1GMpHjKD)

\[7\] [https://www.gartner.com/en/information-technology/insights/top-technology-trends](https://www.gartner.com/en/information-technology/insights/top-technology-trends)

\[8\] [https://baijiahao.baidu.com/s?id=1723098965257642220](https://baijiahao.baidu.com/s?id=1723098965257642220)

\[9\] [https://book.douban.com/subject/36116375/](https://book.douban.com/subject/36116375/)

\[10\] [https://baike.baidu.com/item/PDCA%E5%BE%AA%E7%8E%AF](https://baike.baidu.com/item/PDCA%E5%BE%AA%E7%8E%AF)

\[11\] [https://baike.baidu.com/item/%E5%8F%A4%E5%BE%B7%E5%93%88%E7%89%B9%E5%AE%9A%E5%BE%8B](https://baike.baidu.com/item/%E5%8F%A4%E5%BE%B7%E5%93%88%E7%89%B9%E5%AE%9A%E5%BE%8B)

\[12\] [https://book.douban.com/subject/36116328/](https://book.douban.com/subject/36116328/)

\[13\] [https://www.infoq.cn/article/jk4hqaprvKcTttYhIlBP](https://www.infoq.cn/article/jk4hqaprvKcTttYhIlBP)
