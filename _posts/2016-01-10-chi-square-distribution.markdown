---
layout: post
title:  "χ2乗分布"
date:   2016-01-10 0:00:00 +0900
categories: 確率・統計
---
自由度$$n$$のχ2乗分布の密度関数を以下に示す

$$
f_n\left(x\right) = k_nx^{\frac{n}{2}-1}e^{-\frac{x}{2}}.
$$

ここで，$$k_n$$は$$
\displaystyle
\int_{\mathbb R}f_n\left(x\right)dx
=1$$になるように定める．

$$k_n$$を求めてみよう．
$$\displaystyle 2t = x$$とおくと

+ $$2dt=dx$$，
+ $$\int_{\mathbb R}$$は$$\int_{\mathbb R}$$のまま

なので，

$$
\int_{\mathbb R}
f_n\left(x\right) =
k_n \int_{\mathbb R} \left(2t\right)^{\frac{n}{2}-1}
e^{-t} 2dt
=
k_n 2^{\frac{n}{2}}\int_{\mathbb R} t^{\frac{n}{2}-1}e^{-t}dt
=k_n2^{\frac{n}{2}}\Gamma\left(\frac{n}{2}\right).
$$

$$
k_n = \frac{1}{2^{\frac{n}{2}}\Gamma\left(\frac{n}{2}\right)}
$$

と求まる．
