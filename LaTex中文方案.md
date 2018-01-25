---
title: LaTex中文方案
date: 2018-01-13 12:09:34
tags: LaTex
categories: Sally
---

呀，总算找到最简单的LaTex显示中文的方案了。


    \usepackage{xeCJK}
    xelatex


据说CJK包已经非常古老了，很难用哇。还有以下这种也可以用，不过生成目录时好像有点问题

    \usepackage{ctex}
    xelatex
