---
layout: post
title:  "Γ関数の性質"
date:   2016-01-20 0:00:00 +0900
categories: 数学
---
$$\Gamma$$関数を以下で定義する

$$
\Gamma\left(x\right)=
\int_0^\infty e^{-t}t^{x-1}dt.
$$

次の公式を形式的に示す．

$$
\Gamma\left(x+1\right)=x\Gamma\left(x\right)
$$

証明

$$
\Gamma\left(x+1\right)=
\int_0^\infty e^{-t}t^{x}dt
=\left[-e^{-t}t^{x}\right]_0^\infty - \int_0^\infty -e^{-t}xt^{x-1}dt
=x\Gamma\left(x\right)
$$
