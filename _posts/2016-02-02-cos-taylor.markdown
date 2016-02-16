---
layout: post
title:  "cosのテイラー展開"
date:   2016-02-02 0:00:00 +0900
categories: 数学
---
$$\cos x$$のテイラー展開を求めよう．

$$\frac{d}{dx}\sin x=\cos x$$であり
$$\frac{d}{dx}\cos x=-\sin x$$である．

$$f\left(x\right)=\cos x$$とおくと
$$f\left(0\right)=1,f'\left(0\right)=0,
f''\left(0\right)=-1,f'''\left(0\right)=0,\dots
$$が得られる．

$$\cos x$$のテイラー展開は以下のように求まる．

$$
\cos x =1-
\frac{1}{2!}x^2+\frac{1}{4!}x^4-\cdots
=
\sum_{n=0}^{\infty}\frac{\left(-1\right)^n}{\left(2n\right)!}x^{2n}
$$
