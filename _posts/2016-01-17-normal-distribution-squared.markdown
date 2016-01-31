---
layout: post
title:  "標準正規分布の2乗"
date:   2016-01-17 0:00:00 +0900
categories: 確率・統計
---
確率変数$$X$$は標準正規分布$$N\left(0,1\right)$$に従うとする．
$$X^2$$の従う分布を求めよう．

$$X^2$$の累積分布関数を$$F\left(x\right)$$とおくと，
以下の通り求まる．

$$
F\left(a\right)=P\left( X^2\le a\right)
=P\left(-\sqrt{a}\le X\le \sqrt{a}\right)=
2\int_0^{\sqrt{a}}\frac{1}{\sqrt{2\pi}}e^{-\frac{x^2}{2}}dx
$$

ここから密度関数$$f\left(x\right)$$を求めると以下のようになる．

$$
f\left(x\right)=F'\left(x\right)
=2\frac{d\sqrt{x}}{dx}\frac{1}{\sqrt{2\pi}}e^{-\frac{\sqrt{x}^2}{2}}
=\frac{1}{\sqrt{2\pi x}}e^{-\frac{x}{2}}
$$
