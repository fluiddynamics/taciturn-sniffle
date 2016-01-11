---
layout: post
title:  "自然数の足し算"
date:   2016-01-07 0:00:00 +0900
categories: 数学
---
前の記事で$$0$$と$$S$$を使って自然数を定義したので，さらに足し算を定義する．

$$n$$と$$m$$を自然数とするとき，$$m+n$$を次で定義する．

$$
m+n=\left\{
\begin{array}{ll}
n & \left(m = 0\right)\\
S\left(m'+n\right) & \left(m = S\left(m'\right)\right)
\end{array}
\right.
$$


### $$1+1=2$$の証明
$$1+1$$を計算する．上の定義より
$$1+1=S(0)+S(0)=S(0+S(0))=S(S(0))=2$$．
