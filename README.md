## 关于迁移学习的一些资料

关于机器学习和行为识别的资料，请见我的下面两个仓库：

- [行为识别](https://github.com/jindongwang/activityrecognition)
- [机器学习](https://github.com/jindongwang/MachineLearning)

_ _ _

目录

* [迁移学习简介](#1迁移学习简介)
* [迁移学习的综述文章](#2迁移学习的综述文章)
* [Matlab和Python代码](#3代码)
* [迁移学习代表性研究学者](#4迁移学习代表性研究学者)
* [迁移学习相关的硕博士论文](#5迁移学习相关的硕博士论文)
* [Domain adaptation相关的文章](https://github.com/jindongwang/transferlearning/blob/master/doc/domain_adaptation.md)
* [迁移学习用于行为识别的文章总结](https://github.com/jindongwang/activityrecognition/blob/master/notes/%E8%BF%81%E7%A7%BB%E5%AD%A6%E4%B9%A0%E7%94%A8%E4%BA%8E%E8%A1%8C%E4%B8%BA%E8%AF%86%E5%88%AB.md)
* [常用数据集](https://github.com/jindongwang/transferlearning/blob/master/doc/dataset.md)
* [Contributing]()

- - -

### 1.迁移学习简介

[文档](https://github.com/jindongwang/transferlearning/blob/master/doc/%E8%BF%81%E7%A7%BB%E5%AD%A6%E4%B9%A0%E7%AE%80%E4%BB%8B.md)   ||   [PPT(英文)](http://jd92.wang/assets/files/l03_transferlearning.pdf)   ||  [PPT(中文)](http://jd92.wang/assets/files/l08_tl_zh.pdf)

台湾大学李宏毅的视频讲解，非常不错：https://www.youtube.com/watch?v=qD6iD4TFsdQ

- - -

### 2.迁移学习的综述文章

[一些迁移学习的综述文章](https://mega.nz/#F!sb4ChYoa!37LU6HGJ6LhQC1OYYBglIw)，中文英文都有。

- 其中，最具代表性的综述是[A survey on transfer learning](https://mega.nz/#!hapCXZjQ!p9PpMK0VYWy6Li7QBZ3eVDgaHYUc1MewRFMcjfXAA7s)，对迁移学习进行了比较权威的定义。

- 最新的综述是[A survey of transfer learning](https://mega.nz/#!RfwwiBYS!7mM4juZY-oslxNtG_mv1XhV4zJknzpDM4QkD14S91_s)，写于2015-2016年。其中交代了一些比较经典的如同构、异构等学习方法代表性文章。包括了很多方法介绍，值得一看。

- 此外，还包括[迁移学习应用于行为识别](https://mega.nz/#!RfwwiBYS!7mM4juZY-oslxNtG_mv1XhV4zJknzpDM4QkD14S91_s)、[迁移学习与增强学习](https://mega.nz/#!RDpiRDCL!LSMgyjV69YEiFE2D0quKkrr_t7bEOYtsnx8BkTxniKo)结合等。
- 关于[多个源域进行迁移的综述](https://mega.nz/#!UPRTBIAS!HcjUwI_yGe3IrWCFfBxHF9nd8CFt0GTzjIyMMxdUuv0)、[视觉domain adaptation综述](https://mega.nz/#!hWQ3HLhJ!GTCIUTVDcmnn3f7-Ulhjs_MxGv6xnFyp1nayemt9Nis)也十分有用。
- 中文方面，[迁移学习研究进展](https://mega.nz/#!xPBB2CrZ!QXfJAbmM3DgURIIqB22kgzTARxXIr3TThILgGWXOmPE)是一篇不错的中文综述。
- 关于迁移学习的理论方面，有三篇连贯式的理论分析文章连续发表在NIPS和Machine Learning上：[理论分析](https://mega.nz/#F!ULoGFYDK!O3TQRZwrNeqTncNMIfXNTg)

_ _ _

### 3.代码

#### - [香港科技大学总结的一些迁移学习方法工具包](http://www.cse.ust.hk/TL/)

#### - Matlab：[domain adaptation toolbox](https://github.com/viggin/domain-adaptation-toolbox)

这是一份用matlab写的domain adaptation工具包，内包含了以下的9种迁移学习方法。

![Matlab](https://raw.githubusercontent.com/jindongwang/transferlearning/master/png/matlab.png)

#### - Python：[我写的工具包](https://github.com/jindongwang/transferlearning/tree/master/code/python)

**我写的python版本工具包，目前刚完成了transfer component analysis （TCA）方法。也请有意愿的同学来一起加入这个项目。**

_ _ _

### 4.迁移学习代表性研究学者

- [Qiang Yang](http://www.cs.ust.hk/~qyang/)：中文名杨强。香港科技大学计算机系主任，教授，大数据中心主任。迁移学习领域世界性专家。IEEE/AAAI/IAPR/AAAS fellow。[[Google scholar](https://scholar.google.com/citations?user=1LxWZLQAAAAJ&hl=zh-CN)]
- [Sinno Jialin Pan](http://www.ntu.edu.sg/home/sinnopan/)：杨强的学生，香港科技大学博士，现任新加坡南阳理工大学助理教授。迁移学习领域代表性综述A survey on transfer learning的第一作者（Qiang Yang是二作）。[[Google scholar](https://scholar.google.com/citations?user=P6WcnfkAAAAJ&hl=zh-CN)]
- [Wenyuan Dai](https://scholar.google.com.sg/citations?user=AGR9pP0AAAAJ&hl=zh-CN)：中文名戴文渊，上海交通大学硕士，现任第四范式人工智能创业公司CEO。迁移学习领域著名的牛人，每篇论文引用量巨大，在顶级会议上发表多篇高水平文章。
- [Fuzhen Zhuang](http://www.intsci.ac.cn/users/zhuangfuzhen/)：中文名庄福振，中科院计算所博士，现任中科院计算所副研究员。[[Google scholar](https://scholar.google.com/citations?user=klJBYrAAAAAJ&hl=zh-CN&oi=ao)]
- [Mingsheng Long](http://ise.thss.tsinghua.edu.cn/~mlong/)：中文名龙明盛，清华大学博士，现任清华大学助理研究员。[[Google scholar](https://scholar.google.com/citations?view_op=search_authors&mauthors=mingsheng+long&hl=zh-CN&oi=ao)]
- [Lixin Duan](http://www.lxduan.info/)：中文名段立新，新加坡南阳理工大学博士，现就职于亚马逊。
_ _ _

### 5.迁移学习相关的硕博士论文

硕博士论文可以让我们很快地对迁移学习的相关领域做一些了解，同时，也能很快地了解概括相关研究者的工作。包括了中英文的一些迁移学习相关的硕博士论文。其中，诸如杨强的学生，像

- [Sinno Jialin Pan](https://mega.nz/#!xCwBALCb!exNKlFh6Mi_bvzmclBd6rWOeIwqUuwR7thYIsFK1J5U)
- [Hao Hu](https://mega.nz/#!IaQzlIAY!HpvK6YYv37EngofqZDgdRpMLErSPAmgz8Ln9hWPAJSw)
- [Wenchen Zheng](https://mega.nz/#!QDJFUA4Z!3lBYHH1YzmWI9nTecvaSsR65aWSUmTiUN6Wmjk8y-vc)

等的博士论文都是关于迁移学习的。中文方面，

- 中科院计算所[赵中堂](https://mega.nz/#!cKowSJSD!NLPQ01oSBYXughH9F1toFqdFoYY7JsPQMZlIYtn2-LA)
- 清华大学[龙明盛](https://mega.nz/#!kDBTjDQZ!VZMu4f57N0GBKVcaJs1WNxNkA1JOmp4NcYiVDoDqIJM)
- 以及上海交通大学的[戴文渊](https://mega.nz/#!UehghTCK!9KPD4FwWpHoZmYCmweF0y67Sft7KzTi8F_ZIUA15-QE)是比较代表性的文章。

其他的文章，请见[完整版](https://mega.nz/#F!YHIFxJAL!Ts413E2dbEc_2az4dhb_Jg)。

- - -

### 6.Domain adaptation相关的文章

Domain adaptation是迁移学习领域比较热的研究方向，在这里整理了一些经典的文章和说明：[Domain adaptation](https://github.com/jindongwang/transferlearning/blob/master/doc/domain_adaptation.md)

_ _ _

### [记与迁移学习大牛杨强教授的第二次会面](https://zhuanlan.zhihu.com/p/26260083)

_ _ _

### [迁移学习用于行为识别的文章总结](https://github.com/jindongwang/activityrecognition/blob/master/notes/%E8%BF%81%E7%A7%BB%E5%AD%A6%E4%B9%A0%E7%94%A8%E4%BA%8E%E8%A1%8C%E4%B8%BA%E8%AF%86%E5%88%AB.md)

我写的迁移学习应用于行为识别领域的文章小总结。目前不知道为什么markdown表格的格式错乱，未来会修正。

_ _ _

### 未来计划：

迁移学习、transfer learning、domain adaptation相关的我看过的一些论文:

- 深度迁移学习
- 迁移学习用于行为识别
- 多源迁移学习

以及我已经写好的一些总结


- - -


### Contributing

如果你感兴趣，非常欢迎你加入这个项目！如果需要有超链接指向文件，请不要直接上传到项目中，否则会造成git版本库过大；正确的做法是先把它的超链接（如paper会有自己的主页）放上来，然后我会根据链接把文章放到云端硬盘上。

Welcome!

> ***[文章版权声明]这篇文档是我开源到github上的，可以遵守相关的开源协议进行使用，如果使用时能加上我的名字就更好了。这个仓库中包含有很多研究者的论文、硕博士论文等，都来源于在网上的下载。我对其中一些文章都写了自己的浅见，希望能很好地帮助理解。这些文章的版权属于相应的出版社。如果作者或出版社有异议，请联系我进行删除（本来应该只放文章链接的，但是由于时间关系来不及）。一切都是为了更好地学术！***
