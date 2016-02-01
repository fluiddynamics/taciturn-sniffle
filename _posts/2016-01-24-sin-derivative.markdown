---
layout: post
title:  "sinのテイラー展開"
date:   2016-01-24 0:00:00 +0900
categories: 数学
---
$$\sin x$$のテイラー展開を求めよう．

$$\frac{d}{dx}\sin x=\cos x$$であり
$$\frac{d}{dx}\cos x=-\sin x$$である．

$$f\left(x\right)=\sin x$$とおくと
$$f\left(x\right)=0,f'\left(x\right)=1,
f''\left(x\right)=0,f'''\left(x\right)=-1,\dots
$$が得られる．

$$\sin x$$のテイラー展開は以下のように求まる．

$$
\sin x =
x-\frac{1}{3!}x^3+\frac{1}{5!}x^5-\cdots
=
\sum_{n=0}^{\infty}\frac{\left(-1\right)^n}{\left(2n+1\right)!}x^{2n+1}
$$
