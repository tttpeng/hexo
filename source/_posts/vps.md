title: 折腾VPS
tags: [技术,Typecho,博客,VPS,Internet]
categories: technology
date: 2015-01-11 23:47:00

---

之前就一直有点想搞个VPS（Virtual Private Server）来折腾，但碍于自己实在没什么技术和背景，一直不敢涉足。昨天心血来潮，突然想自己搭个梯子用用，于是从[搬瓦工](https://bandwagonhost.com)以$5.99/年的价格撸了一个屌丝VPS，[购买链接](https://bandwagonhost.com/cart.php?a=confproduct&amp;i=0)在此。当然一向以廉价著称的搬瓦工还有更白菜价的产品，但貌似从官网上不能直接看到，我是从V2EX里的[这个帖子](http://www.v2ex.com/t/97626)找去的。如果仅仅搭梯子用的话64MB内存的应该就够了，但考虑到我还想把博客也折腾过去，还是选了128MB内存的。(其实有个丧心病狂的家伙在32MB内存的VPS上都成功运行着我们伟大的typecho，见[这里](http://32mb.cn/))

于是我走上了一条探索VPS奥妙的不归路，从头开始，一点一点google，光系统就重装了几十次（不过一次几秒钟就能完成……），最后使用的是32位的debian 6。其实关于各种问题网上都有一大堆教程，但是对于这种小内存的机器很多时候却无法如愿完成，按照教程做着做着就会出错，这就是我为什么要重装重启那么多次，因为弯路走得太多了。幸运的是我的两个主要的问题都是从这位仁兄的博客上找到了解决方案——[TENNFY WU](http://www.tennfy.com/)。

首先是shadowsocks的搭建，用了他提供的[debian下shadowsocks-libev一键安装脚本](http://www.tennfy.com/2136.html)。在成功搭好梯子之后便开始蠢蠢欲动——干脆把博客也搬过来算了。面临的首要问题就是要在VPS上搭建一个LNMP环境（Linux＋Nginx＋MySQL＋PHP），为此我尝试了各种教程未果，最终还是从TENNY WU的博客上得到了解救——[debian中lnmp一键安装脚本完善版](http://www.tennfy.com/2123.html)。完成了LNMP环境的搭建后，再把由typecho驱动的博客从之前的空间迁移过来就不是什么难事了。最终，我的博客暂时离开了优秀的[TECHNETCAL](http://technetcal.com)主机，开始在搬瓦工上苟且偷生了。

最后我按照这篇文章[《小内存VPS优化 – 如何搭建个人网站》](http://keenwon.com/436.html)的指导对VPS后台一些东西进行了优化，但貌似没有感觉到明显的变化；并像之前一样，为了域名权重的集中，把主域名重定向到根域名（[教程](http://www.cmhello.com/lnmp-301.html)）。

下图是搬瓦工后台目前VPS使用状况的截图，我真想不通那个32MB的狂人是怎么做到的……不过对于一个刚刚接触VPS的新手来说，已经颇有成就感了。

<center>![Bandwagonhost]({{BASE_PATH}}/images/96b559b97a2eb77e71c4f792fe23a575915a77f8.png)</center>
