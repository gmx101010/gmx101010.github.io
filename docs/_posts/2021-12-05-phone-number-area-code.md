---
layout: post
title:  "手机号前加区号"
date:   2021-12-05 16:21:05 +0800
categories: code
typora-copy-images-to: ../assets
typora-root-url: ../
---

一天，行政通过邮件群发了一个公司开票信息，上面的电话居然是 010-13910733521，当然这个手机号仅为说明问题，使用的是网红手机号代替的。我直接在群里说这个号码有问题。财务大姐回复到：新搬家，暂时没有固话，先使用行政个人手机号代替了。还没有等我搭腔，另一同事回复到，他重点不是用手机号代替的问题，是手机号前绝不可能加固定电话的区号，这是一个错误的组合。

通过这个可以了解到，不仅新招的刚毕业的行政小姐姐不懂，原来财务大姐也不懂，但这个错误在程序员眼里的低级程度，简直是令人发指。如果这个号码给外从看到可丢人丢到家了。

这个知识点我再来复述一下。我们一起来看一下这个树状图，这里是树根，树枝，树叶。也就是说一个完整的号码，国际代码、城市区号、号码。

还是结合到我们的生活中，国际代码或者叫国际区号，中国+86，美国+1，中国香港+852，日本是+81。我们平常打电话几乎不会去加拨+86，因为我人本身在中国境内，不需要再加+86了；类似的现象是我们在同一个城市也不需要加城市区号。

哪些情况需要加这些“前缀号码”呢？我经常收到深圳做外贸推广邮件，那里面的号码就是带+86的，因为面向的群体不同。做外贸是面向的国外客户，需要写国际代码。

在郑州同样有市政、报警、消防、个人固定电话。我就说一个比较有趣的例子，我是在北京开了一个郑州号牌的车，有一些关于车的手续需要联系郑州车管所。郑州车管所网站上公布的电话号码不带区号0371，我在北京直接拨打，接电话的是一个老头，听到我问“你好”就回复说“打错了，加区号加区号，这是我北京家里的电话”。两个错，官网公布号码居然不带区号，我在异地拨打时居然没有加当地区号。两个原因一个是现在是车主全国跑的状态，地方政务官网公布号码时加上当地区号，特别是跟车相关的部门，因为车的流动性更大。看老头如此熟练回复标准话语，看来是被打错很多次了。心疼他三秒钟。

这是固话，手机号就不同了，他没有城市区号。那你该问了，手机号明明有归属地，那我只能说，准确的讲没有前缀式的城市区号。这就是我对电话号码的讲解。

| ![有帮助的截图](/assets/tel_phone.png) |
| :----------------------------------------: |
|          *电话号码组成树状图*          |


<iframe width="100%" height="100vh" src="https://www.youtube.com/embed/9i3Gk9r3VDY?rel=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
