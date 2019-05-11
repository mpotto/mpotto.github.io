---
layout: post
title: "My First Post: testing features"
date: 2019-05-10 17:00:00
categories: tests
mathjax: true
--- 

{% include mathjax.html %}

## Big header

* Do *markdown* features truly work here?

### Not-so-big header

**A code snippet**

 ```python
from sklearn.base import BaseEstimator, TransformerMixin
class DataFrameSelector(BaseEstimator, TransformerMixin):

	def __init__(self):

	def fit(X, y=None):
		return self

	def transform(X, y):
		return X.values
```

**The normal equation**

$$ \hat{\boldsymbol{\theta}} = (\mathbf{X}^T  \mathbf{X})^{-1}  \mathbf{X}^T \cdot \mathbf{y}$$

And, what about inline math? $X \sim \operatorname{Poisson}\left({\lambda}\right)$ Well, it seems fine... perhaps a little too big for inline math, but Ok. 

