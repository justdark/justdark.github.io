---
layout: post
author: DarkScope
title: 新据点
category: 杂项
tag: [博客,模板,搬家]
---


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;已经很久没有在 [csdn](http://blog.csdn.net/dark_scope) 上更新文章了，一个原因是上面干货占比较多，好长一段时间都在学一些跟机器学习算法相关的东西，并且最近一直在忙毕设，所以就疏于维护，想想还是迁移到一个比较简洁的地方，什么东西都写一些

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;这个博客挂在Github Page里面，使用Jekyll生成的，模板是改用知乎上找的一个模板 [soohu](http://soohu.github.io) ，^_^，修改了图标、配色以及一些细节，总的来说还是有些自己的设计在里面。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;最近看了《写给大家看的设计书》，学了一个Keynote设计教程，还在看Photoshop的教程，丰富一下自己的设计武器库，以前一直用画图做，看起来还是不靠谱啊。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;毕业设计 [DVisual](https://github.com/justdark/dvisual) 也基本告一段落，总的来说还是不错，一行一行打出来的代码，能够构成相当复杂和漂亮的图表。对了，挂在Github下还有个好处就是可以直接调用js代码绘图，csdn就不行，像下面这样：
<script type="text/javascript" src="https://raw.githubusercontent.com/justdark/dvisual/master/dvisual.js">
</script>
<div style="width:300px;margin:0 auto;">
<canvas id="myCanvas13" height="300px" width ="300px" margin="0 auto";></canvas>
</div>

<script type="text/javascript">

s13 = new DVisual("myCanvas13");
s13.addElement(new DVAreaPieChart({'X':["ClassA","ClassB","ClassC","ClassD","ClassE","ClassF"],
										'Y':[2,3,4,5,7,9]}))
s13.draw()
</script>

<!-- more -->

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;这里会以记录为主，什么东西可能都会写点，读书感悟啦、又写小玩意啦、玩玩Arduino啦，诸如此类，以后考虑再挂载到一个域名上吧。主要想想写的小玩意还不算少，又有些难登大雅之堂，还是放在这里记录下来以供未来品鉴

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;嗯，就是这样，祝好！^_^

