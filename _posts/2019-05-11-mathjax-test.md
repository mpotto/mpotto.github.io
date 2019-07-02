---
title: "MathJax Test"
mathjax: true
date: 2019-05-11 10:00:00
---

{% include mathjax.html %}

### Central limit theorem

Let $X_{1}, X_{2},\ldots$ be independent random variables with characteristic functions $\phi_{1},\phi_{2},\ldots$ and distribution functions $F_{1},F_{2},\ldots$ and let $\mathbb{E} X_{i}=0$ and $\mathbb{E} X_{i}^{2}=\sigma_{i}^{2}<\infty$, $i=1,2,\ldots$.

Write $S_{n} = \sum_{i=1}^{n}X_{i}$ and $s_{n}=\text{Var}(S_{n}) = \sum_{i=1}^{n}\sigma^{2}_{i}$. Let 

$$
\begin{align}
L_{n}(\varepsilon) & = s^{-2}_{n}\sum_{i=1}^{n}\mathbb{E}\big[ X_{i}^{2}\mathbb{I}\big(|X_{i}|>\varepsilon s_{n}\big)\big] \nonumber \\ 
& = s_{n}^{-2}\sum_{i=1}^{n}\int_{|x|>\varepsilon s_{n}}x^{2}\operatorname{d}F_{n}(x)
\end{align}
$$

The _Lindeberg condition_ states:

$$\begin{equation}\text{for all } \varepsilon>0,\ L_{n}(\varepsilon)\rightarrow0 \text{ as }n\rightarrow\infty.\label{LindCond}\end{equation}$$
If $\mathbb{E}|X_{1}|^{3}<\infty$ and $s_{n}^{-3}\sum_{i=1}^{n}\mathbb{E}|X_{i}^{3}|\rightarrow 0$ as $n\rightarrow\infty$ then Lindeberg's condition holds.  This condition under which the Lindeberg's condition holds is known as Liapounov's condition.


