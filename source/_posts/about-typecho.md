title: Typecho使用初感受
tags: [技术,wordpress,Typecho,Internet]
categories: technology
date: 2014-03-09 15:05:00

---

**名称的来历**

> Typecho是由type和echo两个词合成的，来自于开发团队的头脑风暴。
>
>   Type，有打字的意思，博客这个东西，正是一个让我们通过打字，在网络上表达自己的平台。Echo，意思是回声、反馈、共鸣，也是PHP里最常见、最重要的函数，相信大部分PHP爱好者都是从echo 'Hello,world!'; 开始自己的PHP编程之路的。
>
>   名称就表明 Typecho 是一款博客程序，它在 GPL version 2 许可证下发行，基于 PHP (需要 PHP5以上版本)构建,可以运行在各种平台上，支持多种数据库(Mysql, PostgreSQL, SQLite)。

使用Typecho已经有十几天了，越来越觉得十分顺手，赏心悦目。但由于毕竟还是新手，对Typecho的了解也还不够深入，还无法客观而全面地总结出这个博客程序的特点。好在昨天偶然读到了[羽中](http://www.jzwalk.com)在2010年的一篇介绍Typecho的文章－[《Typecho，让你的博客字字有声》](http://www.jzwalk.com/archives/net/powered-by-typecho)，让我感到真是写出了我的心声，实在忍不住大段引用其中的部分内容了：

> …………typecho是一套追求精简到极致的php博客代码。安装体验过的朋友一定会为默认主题和后台风格感动吧~但个性鲜明的UI设计下精悍的代码构架才是typecho的精髓所在。
>
>   就大家最熟悉的Wordpress程序来比较，typecho把最小的劣势变为最大的优势：PHP5静态技术从头到尾让代码运行效率和服务器负担爽到轻飘飘~虽然没有了Wordpress那样琳琅满目的扩展钩子，但就像变网状交织为树形直达——整整少了一个运行层级，让typecho更加自如轻便。
>
>   当你打开一个Wordpress搭建的博客，会调用至少20多个函数钩子进行查询，错综交互，插件越多运行越慢；而typecho整站只需几个接口，通过静态继承快速传递参数，插件越多功能只会越强大，对速度影响却微乎其微。
>
>   typecho精简的是代码架构和运行效率，在功能扩展性和安全性方面丝毫没有打折扣。健全的日志编辑和发布功能，自带评论嵌套和分页，强大的标签管理，支持自定义页面和永久链接，多用户权限管理，自如的主题和插件扩展……各种主流博客交互技术从RSS,ATOM到TRACKBACK,XMLRPC一应俱全，更多想象中的功能放任插件作者自由发挥；typecho问世的两年间数千用户参与测试使用，至今还未发现任何安全瑕疵。
>
>   如此优秀的一款国产开源博客程序在业内却有着极不相称的低调作风，不得不让用户好奇和猜测其作者和运作团队的背景来历。论坛上常神龙见首不见尾的70是typecho的幕后主刀，三年前我初次接触国内外各种博客程序时偶然试用了他当时自写的Magike，立马被其泛着墨绿色光芒的ajax后台晃晕~(typecho沿用了这一风格)，但后来因为找不到可视化编辑器就投奔了BSP = =(typecho同样沿用不带可视编辑器...) 不过因为提了个小建议就被拉进QQ群也让我着实感受到了70对待开源作品严谨的态度。 果不其然，70竟然在Magike发展正当时决定将一切推倒重来！重新写一个更加小型、灵活真正适合博客需求的轻量级程序，这正是typecho的开发理念。这回70组建了一支分工明确的团队一起在杭州用各自的业余时间维护这个开源项目。动力用70自己的话说就是以开源受益者的身份来回报开源——typecho也是至今国内外少数几个丝毫不带任何商业色彩的免费博客程序。…………
>
>   <!--more-->

似乎所有人钟情于此都是看中了它的轻量高效，简洁友好；也正是Wordpress日益臃肿的界面，复杂的功能让我在偶然间发现了Typecho后就如此迫不及待地转入了它的阵营。问世7年了，这个优秀的国产博客程序才更新到0.9正式版，但已经足够完善以满足用户的各种需求。撰写文章时自带的Markdown编辑器让我觉得在这里输入是一件十分惬意的事情，正如它的介绍所说：

<center>**轻敲键盘，静候回音。**</center>

<center>![Typecho官网]({{BASE_PATH}}/images/df3b3c48885932658e38db367c60598e00fc175e.png)</center>
