---
layout: post
title: 'Emerald SDK 介绍；ETCDev为ETC建设的项目'
date: 2018-10-26
subtitle: 'Emerald SDK 究竟是什么？ETCDev团队在ETC的生态上建设了什么项目？'
cover: 'https://preview.ibb.co/cBaNLq/SDK.jpg'
tags: NEWS
---


![](https://image.ibb.co/h9VWJA/image.jpg)

<font face="微软雅黑"><center>ETC技术</center></font>

**<font face="微软雅黑">1.Emerald SDK 介绍</font>**

![](https://image.ibb.co/i4fgfq/2.jpg)


&emsp;&emsp;<font face="微软雅黑">翡翠软件开发工具包（The Emerald SDK）为在以太经典上搭建去中心化应用程序（DApps）的开发者提供了一系列的开发工具。</font>

&emsp;&emsp;**<font face="微软雅黑">我们将从三个方面向大家详细介绍Emerald SDK：</font>**
- <font face="微软雅黑">DApp的开发环境； </font>
- <font face="微软雅黑">DApp 工具箱概览；</font>
- <font face="微软雅黑">Emerald SDK工具包概述。 </font>

<br>

**<font face="微软雅黑">1.1DApp的开发环境</font>**

&emsp;&emsp;<font face="微软雅黑">在软件开发中，所有的程序在部署生产版本之前都会先在测试环境中试行。在测试环境中，开发者会对程序进行设计审查、安全性测试，可用性测试等评估工作。同样的，在构建DApps时整体开发流程也是如此严谨，或者说它会更加严谨，因为去中心化的区块链具有不可篡改的性质。</font>

&emsp;&emsp;<font face="微软雅黑">如果传统应用程序存在严重的Bug, 管理员（或者黑客）可以完全删除/下架该程序，直到另行通知。然而，在一个去中心化的区块链平台中，错误是不可能魔术般消失，它是不可抹灭的。这就是为什么DApp开发人员需要部署测试网络以及迫切期待主网上能够有一套完善的开发工具，以在测试网中发现修正存在问题，为在主网上的亮相做好准备。那么，DApp开发人员需要什么样的工具来进行端对端的开发呢?</font>


**<font face="微软雅黑">1.2DApp 工具箱概览</font>**

- <font face="微软雅黑">界面：前端用户与DApp交互</font>

- <font face="微软雅黑">测试网：ETC私人测试网，用于开发调试区块链中常见的问题：块，哈希，账户信息等等</font>

- <font face="微软雅黑">钱包：在DApp上创建和签署交易的钱包</font>

- <font face="微软雅黑">区块浏览器：用于在测试网上浏览区块的相关信息</font>

- <font face="微软雅黑">智能合约的测试和部署：用于在制定网络上进行编译、测试和部署DApp的工具</font>

&emsp;&emsp;<font face="微软雅黑">目前，市场中有许多工具供开发人员使用，例如可以使用ReMix编译智能合约，通过MetaMask测试智能合约。但是，这些工具不能够同时运行，而DApp的开发工序复杂繁琐，工具频繁切换加重了整个开发流程工作。现在，Emerald SDK把这一个开发流程封装起来，为开发人员提供了完备的工具，使得DApp的开发工作更加轻松。</font>

**<font face="微软雅黑">1.3 Emerald SDK工具包概述</font>**


- <font face="微软雅黑">Emerald-JS-UI & Emerald-JS：Emerald-JS-UI是一个高度可重用且可自定义的UI组件库。通过Emerald-JS RPC API工具，Emerald-JS-UI组件库可以连接到区块链上（主网/测试网）</font>

- <font face="微软雅黑">Emerald TestRPC: 轻量级测试网（基于SputnikVM-Dev虚拟机）；和主网一样支持所有的操作码；为开发人员提供在主网上进行开发时所需要的信息，如区块信息、账户信息</font>

- <font face="微软雅黑">Emerald Wallet: ETC钱包；能够在不同的网络节点之间切换（主网/测试网）。开发人员可以在他们开发的DApp上签署和发送交易</font>

- <font face="微软雅黑">Emerald Explorer: 可以在不同的网络之间切换的区块链浏览器。开发人员可以通过这个浏览器研究交易相关信息</font>

- <font face="微软雅黑">Emerald-CLI: 被称为Emerald SDK里的“瑞士军刀”。它整合了翡翠平台的整套工具，包括testRPC、钱包、浏览器以及新项目，用于智能合约的测试和部署</font>



*<font face="微软雅黑">原文链接：https://docs.etcdevteam.com/emerald-sdk</font>*

<br>

**<font face="微软雅黑">2.ETCDev为ETC建设的项目</font>**

&emsp;&emsp;<font face="微软雅黑">ETCDev团队目前为以太经典ETC的生态建设开发了下列项目:</font>

![](https://preview.ibb.co/b08dRV/3.jpg)

- **<font face="微软雅黑">翡翠项目（Emerald） </font>**<font face="微软雅黑">：Emerald SDK、Emerald钱包、Emerald浏览器、Emerald-JS&RS工具、Emerald JS UI组件库、Emerald-Vault工具以及Emerald -CLI。</font>


- **<font face="微软雅黑">SputnikVM虚拟机 </font>**<font face="微软雅黑">:SputnikVM虚拟机与基于以太坊虚拟机不同，它可以独立于区块链运行，旨在成为一个运行高效、支持插件化的虚拟机，适用于基于以太坊平台的不同区块链。SputnikVM-Dev是基于SputnikVM开发的以太坊开发虚拟机。</font>

![](https://image.ibb.co/nCCitA/4.jpg)

<font face="微软雅黑">更多内容请点击:</font>[https://github.com/ETCDEVTeam/sputnikvm](https://github.com/ETCDEVTeam/sputnikvm)


- **<font face="微软雅黑">Orbita（待发布）</font>**<font face="微软雅黑">：ETC侧链系统，它能够为ETC二层提供扩容而不影响底层运作。详细内容将会在我们构建组件时宣布。</font>

![](https://image.ibb.co/bYJOtA/5.jpg)

<font face="微软雅黑">更多内容请点击:</font>[https://youtu.be/N6LqgG10_dI](https://youtu.be/N6LqgG10_dI)

- **<font face="微软雅黑">Classic Geth客户端</font>**<font face="微软雅黑">：用Go语言编写，是以太坊协议的原始实现。 Geth客户端是一个团队项目，ETCDev团队是最大的贡献者之一。</font>

<font face="微软雅黑">更多内容请点击：</font>[https://github.com/ethereumproject/go-ethereum](https://github.com/ethereumproject/go-ethereum)


*<font face="微软雅黑">以上配图来源网络，如有侵权请联系小编删除</font>*



***
<font face="微软雅黑"><center>欢迎大家从以下社区平台加入我们</center></font>


<font face="微软雅黑"><center>我们的电报群：https://t.me/etcgo</center></font>
![](https://image.ibb.co/dDg5iA/image.jpg)

<font face="微软雅黑"><center>添加运营小编微信进群：Goedel_Labs</center></font>

![](https://preview.ibb.co/hnL6OA/G.jpg)
![](https://preview.ibb.co/bZ4pbV/Yan.jpg)


<font face="微软雅黑"><center>QQ群：628840867</center></font>

![](https://image.ibb.co/fTYFGV/QQ.jpg)

<font face="微软雅黑"><center>微博：以太经典＿ETC</center></font>
![](https://preview.ibb.co/f2cWqq/weibo.jpg)

<font face="微软雅黑"><center>翻译文章观点不代表本公众号立场</center></font>

<font face="微软雅黑"><center>转载请注明：以太经典中文网</center></font>

![](https://image.ibb.co/mGe2Qq/image.jpg)

[![](https://image.ibb.co/miAkrp/01.jpg)](http://goedel.ai)
