---
layout: post
title:  "直線回帰"
date:   2016-01-08 0:00:00 +0900
categories: 数学
---
点列$$\left( x_1,y_1\right),\dots \left( x_n,y_n\right)$$
に近い直線を求めよう．

$$y=ax+b$$をイメージして
$$\displaystyle R=\sum_{i=1}^n\left( y_i-\left( ax_i+b \right)\right)^2$$
を最小にする$$a,b$$を決定すればよい．

この結果は

$$
\begin{array}{ccl}
a &=& \frac{\overline{xy}-\bar{x}\bar{y}}{\overline{x^2}-\overline{x}^2}\\
b&=& -a\bar{x}+ \bar{y}
\end{array}
$$

となる．

ただし，$$\displaystyle \overline{x}= \frac{1}{n}\sum_{i=1}^n x_i$$，
$$\displaystyle \overline{xy} = \frac{1}{n}\sum_{i=1}^n x_iy_i$$，
$$\displaystyle \overline{y}= \frac{1}{n}\sum_{i=1}^n y_i$$，
$$\displaystyle \overline{x^2}= \frac{1}{n}\sum_{i=1}^n x_i^2$$とした．

### $$x$$と$$y$$を入れ替える場合

（続く）


### 点と直線の距離を使う場合

（続く）
