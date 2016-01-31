---
layout: post
title:  "Γ関数の公式"
date:   2016-01-22 0:00:00 +0900
categories: 数学
---
$$\Gamma$$関数の定義

$$
\Gamma\left(x\right)=
\int_0^\infty e^{-t}t^{x-1}dt
$$

において$$t=r^2$$とおいてみよう．

- $$dt=2r dr$$，
- $$\int_0^\infty$$は$$\int_0^\infty$$のまま

より

$$
\Gamma\left(x\right)=
\int_0^\infty e^{-t}t^{x-1}dt
= 2\int_0^\infty e^{-r^2}r^{2x-1}dr
$$

となる．

## 使用例

$$\Gamma\left(\frac{1}{2}\right)
=\int_{-\infty}^\infty e^{-r^2}dr$$
