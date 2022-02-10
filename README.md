> 本文潜在的目标人群：
>
> 正在（或希望）从事以下工作的人：技术岗（研发、测试、运维）、运营、市场，其他对开源开放性协作感兴趣的人。
> 
> 欢迎加入[飞书群](https://applink.feishu.cn/client/chat/chatter/add_by_link?link_token=47dm0193-e6c9-43c9-b391-06d5da9f72b7)交流！

## 为什么？

为什么要编写这一份《开源最佳实践》呢？

首先，首次尝试参与开源的人对于如何参与开源，很容易有无从着手的感觉。《开源最佳实践》将从如何选择合适的项目、如何参与贡献等多个角度引导读者。

国内（中国）已经有 Gitee 发起并由众多开源爱好者共同编撰的[《开源指北》](https://gitee.com/gitee-community/opensource-guide)，还有 GitHub 官方提供的[《开源软件指南》](https://opensource.guide/zh-hans/)，那这一份最佳实践和这些有什么区别吗？开源不仅仅是把代码开放出来就好了，更加重要的是一种协作精神的体验，以及具体落地操作。所以《开源最佳实践》更多会从落地实践的角度来讲述。

不管你是一名普通的研发，还是一名非技术人员，参与开源必将使你受益匪浅。万事开头难，希望这一份最佳实践可以帮助到更多有意参与开源的人们。

## 寻找起点

参与开源有很多的形式和途径，对于刚开始接触开源的人而言，非常重要的一点就是——基于已有的经验、技能选择适合的开源社区，并且[坚持较长的一段时间](insist.md)。

开源社区通常会在一些平台托管代码、发布文章或音视频资料，大家可以在这些[常见的平台](platforms.md)中寻找适合自己的社区。

对于一个开源社区来说，通常可能会有多个开源项目。社区的自我发展，也要求不同技能、不同背景的人加入，而为了保证社区以公开、透明、平等的方式得以适当的治理，也会出现多种不同类型的项目。例如：存放社区治理规则的 community 项目，存放与图片设计、logo 相关的 artwork 项目，存放社区文档、网站的 website 项目等等。甚至，在发展过程中还可能会出现“子社区”。

和传统的、自上而下的团队管理不同，在开源社区里，虽然存在着不同的角色、分工，但这些角色既不是任命也不是申请来的。角色或影响力，都只能通过贡献（contribution）获得，任何人没有所谓的特权。如果你已经习惯了按部就班地完成分配好的任务，在开源社区里可能会有无所事事的感觉，进而找不到自己的“位置”。而对于愿意自发地做事情、喜欢拥抱变化、追求变得更好的人而言，则会在开源社区中找到“如鱼得水”的感觉。排除涉及到权限的事情，大部分情况下都是不需要“等拿到授权后”再行动。例如：代码（或其他类型的 Pull Request）的 review 并不是 maintainer 独有的权力，每个走过路过的人都是可以针对自己熟悉的领域给出观点、评价。

接下来，会从不同的角色、角度来阐述如何更好地参与到开源社区中。

## 贡献者

对于贡献者（contributor）来说，熟悉[通用的贡献指南](how-to-contribute.md)可以在参与贡献的过程中少走弯路、获得更多帮助。

## 维护者

项目的维护者（maintainer），通常指的是有合并（Pull Request）权限的贡献者。在不同的社区中可能会有不同的叫法，例如：committer、[PMC](https://www.apache.org/dev/pmc.html)(Project Management Committee)、owner 等等。维护者更多的会考虑如何促进项目、社区的健康发展，以及 review 相关仓库的 PR。

### 关注贡献者

项目维护者，一般情况下是愿意花更多精力、时间到某个项目上的人。如果是纯个人项目，或者并没有期望有很多贡献者协同参与的话，并不需要特意关注贡献者，只做自己喜欢做的事情即可。反之，维护者更多应该做的事情是去关注贡献者，帮助愿意参与项目的人贡献他们的聪明才智，也就是所谓的发挥“杠杆作用”。换个角度考虑，对于“能力很强”但对上述事情没有兴趣的话，其实是没有必要赋予“维护者”的权限。

那么，对贡献者的关注包含哪些方面呢？

* 定期查看新提交的 issue、PR，通过打标签（label）等方式进行分类，根据情况 ping 相应的团队（或者贡献者）
* 时间允许的情况下，选择自己熟悉领域的 issue、PR 做尽可能详尽的回复。切忌随意回复，随意对自己和其他贡献者都是不负责的一种行为，同时也是对时间的浪费
* 邀请贡献者参加社区的各类活动，例如：社区例会、Meetup 等。鼓励贡献者深度参与社区。
* 熟知成员的贡献，在相应的社区角色、奖励（ambassador、top contributor 等）给与提名
* 发现、挖掘潜在的项目维护者

### Review

在 PR 的 review 过程中，通常会涉及到三个角色的人：作者、维护者、其他。

首先，我们要想明白一个问题——为什么要进行 review ？不管 PR 中提交的是代码、文档还是其他类型的文件，进行 review 的都有着非常重要的意义。

而不管是对项目维护者，还是贡献者而言，了解如何 review 以及在 review 过程中[有哪些需要注意的地方](review.md)，都是很重要的一件事情。

## 社区治理

随着社区规模的变大，社区治理的重要性会日益凸显，可能遇到的以下问题：

* 如何帮助新人快速地熟悉、适应社区的氛围、玩法
* 如何利用适当的社媒、多媒体平台宣传社区理念、技术，吸引有相似兴趣的人加入
* 如何结合社区成员自身的特点、发展诉求，通过复盘、再组织等方法，适时地调整社区结构
* 如何从合规（许可证选用、商标、专利等）层面确保社区的利益
* 如何维护社区基础设施
* 如何设置沟通、交流底线（或规则，code-of-conduct），避免不好的行为、言论

对于社区（Community）这个词，不同的人有着不同的理解。本文的社区专指：开源社区（Open Source Community）。

在社区运营过程中，有很多好的实践和方法，例如：Technical Oversight Committee (TOC)、SIG、Meetup、Workshop（工作坊）、社交媒体推广等。下面，给出部分组织形式的最佳实践指导。

### TOC

TODO

### SIG

[Special Interest Group，特别兴趣小组](sig.md)，简称 SIG。在大中型开源社区中，这是一种便于社区成员在特定领域交流、讨论，更加聚焦地解决相关问题的组织形式。

开源社区中，可以根据不同的领域设立相应的 SIG。每个 SIG 往往会有一名或多名 lead（领队），以及多名活跃的社区成员作为 SIG 的成员（member）。在不同的社区中，领队可能会有不同的叫法，例如：co-chair、co-lead 等。值得注意的是，这里所使用的表述是——“领队”，而不是领导、经理（manager）、管理员（admin）、负责人；领队的重要意义在于维护 SIG 的积极、活跃，而不是特权。

### 活动

TODO

## 参考

* [Google Engineering Practices Documentation](https://github.com/google/eng-practices)
* [开源相关音视频](audios-and-videos.md)
* [开源相关书籍](books.md)
* [开源商业公司融资情况](financing.md)
* [杂项](others.md)

## 采用该实践的项目

* [Halo](https://github.com/halo-dev/halo)
