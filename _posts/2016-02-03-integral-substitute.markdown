---
layout: post
title:  "積分（円）"
date:   2016-02-03 0:00:00 +0900
categories: 数学
---
定積分$$\displaystyle I=\int_0^1 \sqrt{1-x^2}dx$$を求めよう．

$$x=\sin\theta$$とおくと

- $$dx$$は$$dx=\cos\theta d\theta$$
- $$\theta$$の範囲は$$0$$から$$\frac{\pi}{2}$$

なので以下の通り求まる

$$I=\int_0^{\frac{\pi}{2}}\sqrt{1-\sin^2\theta}\cos\theta d\theta
=\int_0^{\frac{\pi}{2}}\cos^2\theta d\theta
=\left[\frac{1}{2}\theta+\frac{1}{4}\sin 2\theta\right]_0^{\frac{\pi}{2}}=
\frac{\pi}{4}
.$$
