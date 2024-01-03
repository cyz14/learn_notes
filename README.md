# learn_math
按照方向记录看到过的课程，视频，书等材料。大部分不一定看了。

如何自学纯数-一个完整的指导，来自youtube，被B站用户搬运过多次。从中可以大概知道存在哪些方向，以及入门可以看哪些书。  
B站的视频 [How to self study pure math - a complete guide](https://www.bilibili.com/video/BV1uM4y1F73w)  
Youtube的视频 [Youtube byNaO_zn2fI](https://www.youtube.com/watch?v=byNaO_zn2fI)

中科大数学系学生们整理的[USTC基础数学修课指南](https://www.zhangjy9610.me/USTCdata.html)

## 线性代数 Linear Algebra
线性代数太基础了所以也很重要，应该也适合拿来作为复习或学习的起点。除了后续的数学课程需要基本的线性代数，AI模型相关的文章也都是在矩阵上变来变去。
书：Gilbert Strang 的 Linear Algebra，还有他在 MIT OCW 的公开课程   
[Matrix Methods In Data Analysis, Signal Processing, And Machine Learning](https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/)  
书：Linear Algebra Done Right, By Sheldon Axler  
Gilbert Strang 还写过一篇文章讲离散余弦变换、傅立叶变换和循环矩阵特征向量的关系。  

## 实分析 Real Analysis
实分析很有意思的一个例子是 Karl Weierstrass 展示的一个处处连续但处处都不可导的“病态”函数，跟直觉是相反的。  
这本书里还有一部分我看的内容是傅立叶变换的历史和基础的概念。  
Understanding Analysis, by Stephen Abbott  
Video: [Real Analysis by Francis Su](https://www.youtube.com/watch?v=sqEyWLGvvdw&list=PL0E754696F72137EC)


## 点集拓扑 Point Set Topology
拓扑的一个有意思的应用：[公众号MathSpark: Furstenberg's 关于素数无限的拓扑证明](https://mp.weixin.qq.com/s/jgRjOehxCZBEJiV1Q7i2pA)  
这篇文章让人希望理解拓扑说的开集、闭集是什么。一般都推荐这门课，且有一个很多题目的题库，但一开始不懂所以只看了一点。  
[Toronto Univ. Mat327 Topology](http://www.math.toronto.edu/ivan/mat327/?resources)


## 复分析 Complex Analysis

Complex Analysis, by Serge Lang  
这本书大致看了前面的部分。

Visual Complex Analysis, Tristan Needham  
这本书有齐民友的中译版。作者是诺贝尔物理学奖得主Roger Penrose的学生。看过时间简史的人应该对他有印象，霍金提到过不少次。作者是个很有意思的人，可能比较像Arnold，
认为牺牲一些严谨性但是让更多人感兴趣是值得的，不过内容还是硬核的。感觉很多人都看过。前面几十页复数的历史和基本概念没有什么新意，但是第一个震惊我的地方是对复平面上函数的幂级数和傅立叶级数之间的联系的解释。  

Visual Complex Functions, An introduction with phase portraits, by Elias Wegert  

Video: [Wesleyan University Analysis of a Complex Kind](https://www.youtube.com/playlist?list=PLi7yHjesblV0sSfZzWdSUXGO683n_nJdQ)

一个学习小组里的博后推荐了一个复函数可视化的网页 https://samuelj.li/complex-function-plotter/  
另一个相关的启发了上面这个网页作者的网页是 http://davidbau.com/conformal/  

## 群论 Group Theory

The Abel Theorem in problems, Arnold  
阿诺德和他学生整理的一门给中学生的课程材料，书里包含两部分内容和题解及附录。前两部分内容都是通过基本定义和问题的方式引导学生逐步得出结论，在书的后半部分给出提示、题解和其他附录。第一部分是讲基础的群论，然后引出正十二面体对称群的不可解等价于五次方程无根式解；第二部分介绍复的黎曼面的构造，以及代数方程的解的置换，系数在黎曼面上的置换，给出了阿贝尔定理的几何含义。因为是给中学生的课程的材料，所以比较好理解。  

复平面上多项式根的网页demo: https://duetosymmetry.com/tool/polynomial-roots-toy/  

## 几何

[给未来几何和拓扑学家的阅读建议](https://vitalyr.com/post/%E7%BB%99%E6%9C%AA%E6%9D%A5%E5%87%A0%E4%BD%95%E5%92%8C%E6%8B%93%E6%89%91%E5%AD%A6%E5%AE%B6%E7%9A%84%E9%98%85%E8%AF%BB%E5%BB%BA%E8%AE%AE/)  
这是一位网友写的 Needham 的书 Visual Differential Geometry and Forms 的附录的翻译，他将其视为给未来几何和拓扑学家绝佳的阅读建议。

一位日本老师 Tadashi Tokieda 给南非的一个班上的一门 拓扑与几何 的课程，对基础没有太多要求，讲的感觉很有意思。 这么课用黑板来讲，可以跟着记笔记，能跟着学会怎么画一些图。课程开始就说他希望大家注重图像思维 picture thinking，无论何时做数学时永远画图，以及除了物理现实的物体外还有更多的图像，要学会看到看不见的东西以及在这些图像上推理。  
第一章从基本且重要的流形的分类讲起，然后第二章讲同伦 Isotopy 的概念，第三章引入相交数 intersection number，随后第四章讲不动点理论（Lefschetz Thm 和 Brouwer Fixed Point Thm）及相关应用（包括Nash均衡和Markov链），第五章是向量场的 equilibria，引入了 Tangent Bundle、欧拉示性数 Euler characteristic 和相关的Poincare-Hopf指标定理，第六章作为几何理论的应用证明代数基本定理，d>=1次复多项式，复平面上一定有一点使得该多项式为0。最后作者讲了些故事，比如 Lefschetz 是一个因为事故失去了手的数学家，但他靠把粉笔卡在手上可以做数学以及讲课，还有这些南非的学生跟 Lefschetz 产生了一些联系。  
在 Mathematics Genealogy Project 网站可以从 [Tadashi Tokieda](https://genealogy.math.ndsu.nodak.edu/id.php?id=60734) 一路点 advisor 向上看导师是谁，这样可以一路看到  
Tadashi Tokieda <- William Browder <- John Coleman Moore <- George William Whitehead, Jr. <- Norman Earl Steenrod <- Solomon Lefschetz.  
Youtube上的南非数学科学研究院 [Topology and Geometry, by Dr Tadashi Tokieda in 2014](https://www.youtube.com/watch?v=SXHHvoaSctc&list=PLTBqohhFNBE_09L0i-lf3fYXF5woAbrzJ)  
Tadashi本人的经历也很有意思。小时候很有艺术天赋，后来到法国学语言，写毕业论文时要选一个人的传记，于是在图书馆看到朗道的传记，里面的一个故事是朗道在医院问来看望他的儿子，sin x的不定积分是什么，他的儿子不知道因此他很失望。Tadashi 当时感觉到自己也被批评了，于是开始学数学（同时学了点俄语），后来就转到了数学方向，到 Oxford 学了两年，然后到 Princeton 去读了数学 PhD。  

### 微分几何 Differential Geometry

书：微分几何讲义，陈省身，陈维桓  
这本书自然很经典，比如[给未来几何和拓扑学家的阅读建议](https://vitalyr.com/post/%E7%BB%99%E6%9C%AA%E6%9D%A5%E5%87%A0%E4%BD%95%E5%92%8C%E6%8B%93%E6%89%91%E5%AD%A6%E5%AE%B6%E7%9A%84%E9%98%85%E8%AF%BB%E5%BB%BA%E8%AE%AE/)也说我们应该看这本书：
```
收录这本高级的作品，只有一个原因，也只有一个原因。Chern（陈省身）（这本书是根据他的讲座编写的）是20世纪最伟大的几何学家之一，因此他说的任何东西，我们都应该认真听。
```
实际上这是按照讲义的内容整理的，内容本身不是按照书来准备的，所以没学过的人比如我看起来有点吃力。看看其他书和课程有一定理解后再看其中的部分感觉理解了一些里面在讲什么。

书：An Introduction to Manifolds, Loring W. Tu  
作者是美国台裔数学家杜武亮，这本书写的很好懂。目前只看到第一部分，R^n中的切向量等概念。

书：微分几何入门与广义相对论，梁灿彬
课程：[B站视频](https://www.bilibili.com/video/BV1o4411L72E/)  
很多人推荐梁老师的广义相对论课程，不过视频内容有点长，而且不得不说微分几何入门的部分第一遍很难就完全理解，所以暂时没坚持看下去。

书：Introduction to Smooth Manifolds，John Lee   
伯克利的[Math 214 — Spring 2022](https://docs.google.com/document/d/e/2PACX-1vSvzH9pT6PLoqXY8G5FVkzGxHlaK-oiwkUeb1CppGta0LydvwLuEHVKK5_wODeGuO2oIoEV0fX9ZQd0/pub) 采用这本书作为教材，作为一门本科生课程还可以跟着听几节。  
有人传了疫情期间线上的[21年春季的课程视频](https://www.youtube.com/watch?v=mcC8fvqKZG0&list=PLoWHl5YajIf7NqaCGCCEMvaKfhIHHrsQC)到Youtube。

课程：华东师范大学[2021春-微分几何](https://math.ecnu.edu.cn/~bliu/files/differential%20geometry/diff_geo.html)  
这个课程材料是google搜索时发现的。lecture写的是按照讲课的逻辑，看文字跟看视频差不多，不像一般的教材那么抽象难以看下去。老师给出各种定义有一些常用的“套路”，看起来很合理。

课程：东京工业大学理学院 [幾何学特論B (MTH.B402) （2018年度）](https://www.math.titech.ac.jp/~kotaro/class/2018/geom-b/index-jp.html)  
四个英文的[講義ノート](https://www.math.titech.ac.jp/~kotaro/class/2018/geom-b/lecture-01.pdf) 可以看。好处是内容不多，只有四个讲义，介绍曲面的基本理论，比如第一、第二基本形式。看的不是很仔细。


说到等温坐标，搜索发现一般是在讲极小曲面的时候介绍这个，但似乎已经是比较细的知识。  
[ETH 的极小曲面课程]（https://metaphor.ethz.ch/x/2019/hs/401-3830-69L/）包含了一些参考材料。  
[幾何学特論F (MTH.B502) （2016年度）](https://www.math.titech.ac.jp/~kotaro/class/2016/geom-f/index-jp.html) 的 [lecture03](https://www.math.titech.ac.jp/~kotaro/class/2016/geom-f/lecture-03.pdf) 讲了等温坐标。  
同学也推荐直接看陈省身先生的证明等温坐标的存在性的论文 [An Elementary Proof of the Existence of Isothermal Parameters on a Surface](https://www.ams.org/journals/proc/1955-006-05/S0002-9939-1955-0074856-1/S0002-9939-1955-0074856-1.pdf).  

### 双曲几何 Hyperbolic Geometry
微信公众号集智俱乐部的一篇介绍性文章 [双曲空间漫游指南：一场琳琅满目的跨学科之旅](https://mp.weixin.qq.com/s/k-tMk3tYekvQjmDWxjt-rg)

网上的一些课程材料  
https://personalpages.manchester.ac.uk/staff/charles.walkden/hyperbolic-geometry/hyperbolic_geometry_1920.pdf  
https://homepages.warwick.ac.uk/~masbb/Papers/MA448.pdf  

双曲几何为什么重要？有一篇公众号的文章说 [几乎所有的东西都是双曲的](https://mp.weixin.qq.com/s/9fL0idGhRveuPU7mItKqmw) 这么说可能不严谨，但是可能有一定道理。里面说曲率为0的曲面有torus和克莱因瓶，曲率为1的有球面和射影平面，所有其他表面——有无穷多个——的曲率都是-1。
实际上，在现在的 NLP 里面有着基本重要性的embedding模型，大多是直接用的欧式空间的距离和余弦距离，但不难想到推广到其他空间和对应的距离，已经有人研究双曲空间里的 embedding，比如  
2017年的 [Poincaré Embeddings for Learning Hierarchical Representations
Maximilian Nickel, Douwe Kiela](https://arxiv.org/abs/1705.08039)  
2018年的 [Hyperbolic Embeddings with a Hopefully Right Amount of Hyperbole
by Chris De Sa, Albert Gu, Chris Ré, and Fred Sala](https://dawn.cs.stanford.edu/2018/03/19/hyperbolics/)  
不过这么做似乎还没有广泛应用，理论上也没有证明，也没有找到足够的证据说服这样是对的或者更好的。

### 代数拓扑 Algebraic Topology

Book: [Algebraic Topology, by Allen Hatcher](https://pi.math.cornell.edu/~hatcher/AT/AT+.pdf)  
Video: [Algebraic topology, by Pierre Albin](https://www.youtube.com/watch?v=XxFGokyYo6g&list=PLpRLWqLFLVTCL15U6N3o35g4uhMSBVA2b)  


