---
layout: post
title:  "スターリングの公式の使用例"
date:   2016-01-19 0:00:00 +0900
categories: 数学
---
次の極限を求めよう．

$$
\lim_{n\rightarrow \infty}
\frac{\Gamma\left(\frac{n+1}{2}\right)}{\sqrt{n\pi}\Gamma\left(\frac{n}{2}\right)}
$$

スターリングの公式より

$$
\lim_{n\rightarrow \infty}
\frac{\Gamma\left(\frac{n+1}{2}\right)}{\sqrt{n\pi}\Gamma\left(\frac{n}{2}\right)}
=\lim_{n\rightarrow \infty}
\frac{\sqrt{2\pi}\left(\frac{n+1}{2}\right)^{\frac{n+1}{2}-\frac{1}{2}}e^{-\frac{n+1}{2}}}
{\sqrt{\pi n}
\sqrt{2\pi}\left(\frac{n}{2}\right)^{\frac{n}{2}-\frac{1}{2}}e^{-\frac{n}{2}}
}
=\lim_{n\rightarrow \infty}
\frac{1}{\sqrt{2\pi}e^{\frac{1}{2}}}\left(1+\frac{1}{n}\right)^{\frac{n}{2}}
=\frac{1}{\sqrt{2\pi}}
$$

