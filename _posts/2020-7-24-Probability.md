---
layout: post
title: 概率论学习总结1
categories: Probability-theory
description: 概率论学习总结
keywords: Probability
---

# 概率论背景一览：

概率(或然率或几率) ——  随机事件出现的可能性的量度—— 其起源与博弈问题有关.

概率论是一门研究客观世界随机现象数量规律的 数学分支学科.

16世纪意大利学者开始研究掷骰子等赌博中的一些问题；17世纪中叶，法国数学家B. 帕斯卡、荷兰数学家C. 惠更斯 基于排列组合的方法，研究了较复杂 的赌博问题， 解决了“ 合理分配赌注问题” ( 即得分问题 ).

对客观世界中随机现象的分析产生了概率论；使 概率论 成为 数学的一个分支的真正奠基人是瑞士数学家J.伯努利；而概率论的飞速发展则在17世纪微积分学说建立以后.

第二次世界大战军事上的需要以及大工业与管理的复杂化产生了运筹学、系统论、信息论、控制论与数理统计学等学科.

数理统计学是一门研究怎样去有效地收集、整理和分析带有随机性的数据，以对所考察的问题作出推断或预测，直至为采取一定的决策和行动提供依据和建议的 数学分支学科.

统计方法的数学理论要用到很多近代数学知识，如函数论、拓扑学、矩阵代数、组合数学等等，但关系最密切的是概率论，故可以这样说：概率论是数理统计学的基础，数理统计学是概率论的一种应用.  但是它们是两个并列的数学分支学科，并无从属关系.

## 基本术语：

随机现象（或偶然现象）：

1.每次试验前不能预言出现什么结果。
2.每次试验后出现的结果不止一个。
3.在相同的条件下进行大量观察或试验时，出现的结果有一定的规律性—— 称之为统计规律性 

对某事物特征进行观察或实验, 统称`试验`.若它有如下特点,则称为`随机试验`,用`E`表示：

> 在相同的条件下可重复进行。
>
> 试验结果不止一个,但能明确所有的结果。
>
> 试验前不能预知出现哪种结果。

`样本空间`—— 随机试验E 所有可能的结果

组成的集合称为`样本空间`   记为Ω。

样本空间的元素, 即E 的直接结果, 称为`样本点(or基本事件)`  常记为ω，Ω = {ω}。

`随机事件` —— 在随机试验中，对某些现象或某些情况的陈述。Ω的子集, 记为A ,B ,…

------

> 理解总结：
>
> 某些事件的发生可能存在不明确的结果，这类事件称为随机事件（随机现象）；此处应注意各字符对应含义。

------

事件通常分为以下几种类型：

`基本事件` —— 仅由一个样本点组成的子集它是随机试验的直接结果,每次试验必定发生且只可能发生一个基本事件.

`必然事件`——全体样本点组成的事件,记为Ω, 每次试验必定发生的事件.

`不可能事件`——不包含任何样本点的事件,记为Φ ,每次试验必定不发生的事件.

## 事件关系与运算

![](http://p.qlogo.cn/qqmail_head/Q3auHgzwzM7qJfYMXHt5doEGNELY23yZicjz2PBScp8IhicApTK5dhAtxqHZziafYT1IqK5R2ezfu91A7oZE0PSobIOVd4uvcHicsqYMWhyO4tA/0)

![](http://p.qlogo.cn/qqmail_head/Q3auHgzwzM7qJfYMXHt5doEGNELY23yZIshEaMiakXdlY0KQFFgEaXhCa22cTRn41MATTq2XphRDBMjqnnl61vvFwkPK40A2Ev0FTlbctSrY/0)

![](http://p.qlogo.cn/qqmail_head/Q3auHgzwzM7qJfYMXHt5doEGNELY23yZUS1JObTIsBxodkgicF2LCSjwrxxQMb2Q33sgeOhHBH2K0s8t1o0neSibgv8FnKiaZEaiaf6MtHOU424/0)

![](http://p.qlogo.cn/qqmail_head/Q3auHgzwzM7qJfYMXHt5doEGNELY23yZuNVoAYK7P6Kj343hzLx6l816cQhbPDbpJjYyMD4XSjmic5kJT4q5X3JUiarQHwrDYsZOmdXOhia0XQ/0)

![](http://p.qlogo.cn/qqmail_head/Q3auHgzwzM7qJfYMXHt5doEGNELY23yZHHD6f5MIC0WBvdIr5eRAV5aCLOwt2SlBmX5OyJG3hI27c1owwwNKs0ePl9dXFgERP2pxlyzMMZ0/0)

![](http://p.qlogo.cn/qqmail_head/Q3auHgzwzM7qJfYMXHt5doEGNELY23yZyO6CFFPKBMYJKp4Nkc69V0W43YnHeSJYFNasajiciavZU4ibe5wmXj7q2pjQrmiaQOgEhKzC6XuFiaia8/0)

运算：

![](http://p.qlogo.cn/qqmail_head/Q3auHgzwzM7qJfYMXHt5doEGNELY23yZfpPvxtOibWYZ0fwKe4J8TTPU2qSg7ChKUIBtwcQ9MnBGIicrlMcdxdeugHVIzLwtTliapwV2ND5ichY/0)

![](http://p.qlogo.cn/qqmail_head/Q3auHgzwzM7qJfYMXHt5doEGNELY23yZWGRId0ZaFNvAovhXJvPtZlOHVlmf3Nu1yXBQz3GnF3sTN7eBQA3dwdgzuKIWwiaH8icHMrrGlpPBE/0)

------

> 理解总结：
>
> 巧记对偶律：并的补等于补的交。

------

