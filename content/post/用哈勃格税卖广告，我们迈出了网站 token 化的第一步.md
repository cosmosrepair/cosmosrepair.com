---
title: 用哈勃格税卖广告，我们迈出了网站 token 化的第一步
date: 2019-06-27
author: 吴尼克
tags: ["经济学", "区块链"]
---

一次有趣的社会实验。

<!--more-->

![](https://cosmosrepair-1257028016.cos.ap-beijing.myqcloud.com/2019-06-27-1821561608486_.pic_hd.jpg)

**引言**  说起来神奇，“一块广告牌” 是我一个多月前分叉美国某经济实验类区块链项目的一个 idea。以开源形式开始运行后，遇到了 Mable 和 Nick 出于兴趣自然形成了团队，激发出了种种新的想法，并一步步变成了现实。在这个过程中，所有的参与者，贡献者，海外经济学家，工程师的讨论者，都是自发地参与到这个开源项目中来的。所以，接下来我们不仅会把它当做一个经济实验，也会同时作为线上组织建立和治理，融资形式等多维度的社会实验。毕竟，预测未来的最好方式，就是去创造它。 --  Jade

- - - - - 

去年 4 月，以太坊创始人 V 神( Vitalik Buterin ) 在个人博客中深度探讨了一个叫做“哈伯格税（ Harberger taxes ）”的经济理论。

**他认为该理论“是对政治经济学的另一种新奇又有趣的解读”，并且可以和区块链的通证设计有着很好的结合。**

那么哈勃格税究竟是什么？这个税的核心规则有两点：
- 为私人拥有的财产公开一个标价，并每年提交根据该估价某个百分比的税；
- 市场上的任何人都可以按该公开标价从你手中购买该财产。

其核心的制衡因素在于：**标价开高了，交税要交更多；开低了，别人可以轻易买走你的财产。**

这两点迫使每个理性人（假设你不想多交税，假设你不想被人轻易买走）趋向合理范围估价。

**听起来似乎简单，在实践中会有价值无法直观体现等重重困难。但这一概念激起了很大范围的讨论，也有人开始进行各种各样的实践。**

## 01 

去年 9 月，V 神和哈佛大学 Zoë Hitzig 及《 Radical Markets 》一书作者 Glen Weyl 共同撰写了论文**《自由激进主义:社会基于社群中立的正式规则》**，进一步探讨哈伯格税的应用。

今年 3 月，南非数字艺术家 Simon de la Rouviere 基于哈勃格税的理念和以太坊，以 ERC 721 的形式做了一个数字艺术品，意在探索哈勃格税在艺术领域的应用。

![](https://cosmosrepair-1257028016.cos.ap-beijing.myqcloud.com/2019-06-27-640%20-%202019-06-27T135307.905.jpeg)

网址：<https://thisartworkisalwaysonsale.com/>

该艺术品目前的价格已经升至 240 以太坊（约 50 万元人民币）。

这个月初，[BES区块链实验室](http://beslab.xyz)分叉了该项目，将 Harberger 税应用到“线上广告”这一资产类别上，并在经济机制，应用场景，社区治理形式上做了进一步的创新，**项目名为“一块广告牌”**。

“一块广告牌”上线后，短短几天时间里，就被换手多次，内容大多是对某个人的祝福。被祝福的人包括 BES 创始人 Jade、DappReview 创始人 Vincent、链圈斯嘉丽等等，很是温馨和逗趣。

![](https://cosmosrepair-1257028016.cos.ap-beijing.myqcloud.com/2019-06-27-640%20-%202019-06-27T135434.618.jpeg)
 
## 02 

“一块广告牌”这个有趣的 DApp （去中心化应用）对我来说犹如一股清流，在浮躁的币圈不断的带来小温馨小快乐。

《 Radical Markets 》作者 Glen、数字艺术家 Simon 等海外学者，也在持续的关注这个有趣的小实验。

![](https://cosmosrepair-1257028016.cos.ap-beijing.myqcloud.com/2019-06-27-640%20-%202019-06-27T135531.521.jpeg)
![](https://cosmosrepair-1257028016.cos.ap-beijing.myqcloud.com/2019-06-27-0%20-3-.jpeg)

广告牌用于个人情感的表达固然颇有行为艺术的感觉，这也同时这也启发我去思考物权、使用权与社会关系的影响。
- 基于哈勃格税的广告牌设计有没有可能被用于商业项目？
- 网站的广告位该如何定价？
- 目前一对一商务接洽售卖的方式是否最有效率？
- 有没有可能借助哈伯格税以一种全新的方式售卖或出租网站广告位？
- 网站价值该如何评估？是否可以被 token 化？

想了很久，我发现这些问题光靠想是想不明白的。

**山不过来，我就过去。
既然没有人去实践，那我们就自己来。**

## 03 

我们买下了这块广告牌的所有权，并通过我们 DOGIgames.com 的网站给这个广告牌赋予价值：

![](https://cosmosrepair-1257028016.cos.ap-beijing.myqcloud.com/2019-06-27-0%20-4-.jpeg)

具体玩法如下：

1、我们把网站左侧的展示空间留给“一块广告牌”网站，如下图。

![](https://cosmosrepair-1257028016.cos.ap-beijing.myqcloud.com/2019-06-27-640%20-%202019-06-27T135739.009.jpeg) 

手机上看是这样的：

![](https://cosmosrepair-1257028016.cos.ap-beijing.myqcloud.com/2019-06-27-640%20-%202019-06-27T135755.715.jpeg) 

2、在“一块广告牌”网站上购买该广告牌的玩家，可以获得在 DOGIgames.com 网站首页广告展示的服务，广告展示至 2019 年 7 月 31 日。

点击阅读原文或访问以下网站，均可到达访问网站：<http://anadvertisementboard.com/>

3、购买该广告牌后，你可以随意将该广告牌以任何价格进行出售或转让，但转让后广告展示时间不变。

4、请购得广告牌的广告主联系我们，以更新在 DOGIgames.com 网站上展示框的内容，刊登内容需符合相关国家的法律法规。

5、广告牌的初始价格为 2.5 ETH，购买后可以随意修改价格。

6、如需帮助请随时联系我们。

**在文章发出前我们得到了一个意外惊喜，在我们推出这个玩法之后，《 Radical Markets 》作者 Glen 在 Twitter 上做了回复：**

![](https://cosmosrepair-1257028016.cos.ap-beijing.myqcloud.com/2019-06-27-0%20-2-.jpeg)

很高兴能参与到这样一场关于哈勃格税的社会实验，并与我们 DOGIgame.com 的自身媒体属性找到了一个很好的契合点，未来这场实验将会如何推进，我们会进行持续的跟踪和报导，请继续关注。

- - - - - 

文章里涉及的一些参考资料及其他与哈勃格税相关的资料：

1. 论文链接：<https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3243656>

2. V 神 medium 发文： <https://medium.com/@VitalikButerin/liberation-through-radical-decentralization-22fc4bedc2ac>

3. 橙皮书上亦有中文翻译和很多很好的讨论 <https://orange.xyz/tag/5>

4. 一块广告牌网站地址：<http://anadvertisementboard.com/>

5. GitHub：<https://github.com/anadvertisementboard/anadvertisementboard>

6. 微信文章：[Mable 2019 <一块广告牌——二十一世纪的共享广播站？>](https://mp.weixin.qq.com/s/NCjncWZAMEn-lljXKRMM6w)

7. Harberger Tax 卖艺术品：<https://thisartworkisalwaysonsale.com/>

8. 卖艺术品的 medium：<https://medium.com/@simondlr/this-artwork-is-always-on-sale-92a7d0c67f43>

9. 卖艺术品的 GitHub：<https://github.com/simondlr/thisartworkisalwaysonsale>

10. 橙皮书相关文章：<https://orange.xyz/tag/5>

11. Vitalik Buterin 关于 Radical Markets 和 Harberger taxes 的介绍：[Vitalik  2018, ‘On Radical Markets’  Vitalik Buterin's website,](https://vitalik.ca/general/2018/04/20/rad ical_markets .html)

12. Harberger Tax 和 Radical Markets 的书：[Eric A. Posner & E. Glen Weyl 2018, <Radical Markets: Uprooting Capitalism and Democracy for a Just Society>, Princeton University Press](https://www.amazon.com/Radical-Markets-Uprooting-Capitalism-Democracy/dp/0691177503)