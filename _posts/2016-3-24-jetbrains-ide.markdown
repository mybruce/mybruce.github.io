---
layout:     post
title:      高效使用IntelliJ IDEA
date:       2016-03-24 10:15:17
summary:    提升编码效率有妙招
categories: ide editor efficiency
---

在介绍妙招前，先给大家说说JetBrains这家公司的产品结构（重度用户，所以打个广告）。

JetBrains公司的IDE产品非常的齐全，主流的编程语言基本上都囊括了，有Python、Ruby、C/C++、Objective-c/Swift、Javascript、PHP、Java。虽然每门语言的IDE都是独立的，但是得益于她的整体架构，每个IDE的基础设施都是一致的，唯一的差别就是编程语言本身和该语言的生态。比如Webstorm(Javascript IDE)就支持Typescript、CoffeeScript、ES6、Dart等Javascript的超集语言，也支持JQuery、AngularJS、NodeJS、React等一系列的框架。只要你掌握了一款JetBrains公司的IDE后，就能零成本的使用该公司的其他IDE。并且可把之前IDE的各种配置导入到新的IDE中，强大至极。


**妙招一：**

*游走于键帽间的极致体验——ideavim插件*

ideavim是Jetbrains公司自制的一个IDE插件，可以安装在任何该公司的IDE中。该插件主要的功能就是把VIM的操作模式映射到IDE中来。在我用过有vim插件的编辑器中（Atom、VsCode、Sublime等），只有ideavim的还原度是最高的。不知VIM为何物者请看：[VIM](https://www.zhihu.com/topic/19570193/hot){:target="_blank"}。

**妙招二：**

*优雅的完成工作——重构功能*

在说重构功能之前，说说他们家的导航功能，导航功能不仅可以跳转到类、文件、指定行和符号上。还可以通过文件结构功能在一个文件内自由的翱翔，畅快淋漓。

至于重构功能，就拿我使用的WebStorm来举例：你可以给类,方法,类变化和局部变量重命名、还可以重写父类的方法、实现接口的方法（属性不行）、生成get和set属性。等等等。

我比较懒，因为重构菜单下有好多的功能，所以大家还是自己慢慢研究一下哈。

正所谓：工欲善其事，必先利其器。又所谓：砍柴不误磨刀功。努力向前吧！少年。


