---
layout: post
title:  "一様分布の2乗"
date:   2016-01-16 0:00:00 +0900
categories: 確率・統計
---
確率変数$$X$$は一様分布$$U\left(0,1\right)$$に従うとする．
$$X^2$$の従う分布を求めよう．

$$X^2$$の累積分布関数を$$F\left(x\right)$$とおくと，
以下の通り求まる．

$$
F\left(a\right)=P\left( X^2\le a\right)
=P\left(X\le \sqrt{a}\right)=\sqrt{a}
$$

ここから密度関数$$f\left(x\right)$$を求めると以下のようになる．

$$
f\left(x\right)=\frac{dF\left(x\right)}{dx}
=\frac{1}{2\sqrt{x}}
$$

上記の$$F$$と$$f$$の定義域は$$0$$と$$1$$の間である．
