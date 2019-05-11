---
layout: post
title: "Jupyter Notebook conversion"
date: 2019-05-11 08:52:00
categories: tests
mathjax: true
--- 

{% include mathjax.html %}

## Markowitz Problem

{::nomarkdown}
\begin{equation*}
\begin{aligned}
& \underset{w_i}{\text{minimize}} 
& & \sum_{i=1}^{n} \sum_{j=1}^{n} w_i w_j \sigma_{ij} \\
& \text{subject to}
& & \sum_{i=1}^{n} w_i \mathbb{E}(r_i) = \bar{r}\\
& & & \sum_{i=1}^{n} w_i = 1 
\end{aligned}
\end{equation*}
{:/nomarkdown}