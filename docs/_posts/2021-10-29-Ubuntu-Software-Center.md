---
layout: post
title:  "Ubuntu的「软件中心」与AppStore一个天一个地"
date:   2021-10-29 11:30:05 +0800
categories: ubuntu
typora-copy-images-to: ../asserts
typora-root-url: ../
---

| ![有帮助的截图](/assets/Selection_385.png) | 
|:--:| 
| *Ubuntu软件中心* |

# 前言

今天在`Ubuntu 18.04`上安装了`腾讯会议`和`zoom`，下载deb包进行安装，安装后者的时候又遇到了安装不成功，直接进度条归0。就想写文章总结一下这个`软件中心`。

# 问题

有没有觉得Ubuntu的[软件中心]比较扯蛋，这些年几乎没有怎么用得爽过。在偶尔大白屏，偶尔装软件缺少库的时候直接无任何提示，进度条直接回到0，再点[安装]仍然如此。只好灰溜溜得用回dpkg命令，可以清楚看到报错信息，安装依赖后就可以正常安装（比如刚才安装了zoom就是这样）。所以「软件中心」存在的意义是什么？这么弱鸡。

我能想起来唯一比较爽的地方就是新装完系统之后，可以在[软件中心]方便地批量卸载不用的软件比如libreoffice, amazon商店等。

# 汇总
1. 新软件(比如`腾讯会议`和`zoom`)搜不到
2. 安装deb包缺少依赖时不会自动安装，直接进度条归0 对新手不友好
3. 新流行的AppImage包不支持
4. 经常白屏

一言以蔽之：**和AppStore差得太远，难用之极**。

# 网友解答
除了1外，其他可能是不肯用新版带来的问题。`Ubuntu`很早以前双击`deb`就会自动试图解决依赖的，只不过是从`apt`仓库里搜索依赖，
而不会自动从本地文件夹里的`deb`里搜索。AppImage这这种`绿色便携版`本来就不是适合软件商店分发管理的。然后`AppStore`不支持自身之外的软件包安装。（deb、AppImage都是`软件商店自身之外的`）。网友结论就是：使用`20.04`，软件商店使用`Snap`。

# 我的结论
用最新版是不可能用最新版的，这辈子不可能最新版的。软件又不会改，就是吐槽这种东西，软件中心出问题可以使用dpkg。群里面个个都是人才，说话又好听，我超喜欢在里面，听他们劝退我。：Ｐ

