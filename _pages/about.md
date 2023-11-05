---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Under construction.

In the meantime, you can visit this [Zotero library](https://www.zotero.org/groups/5240598/found-objects) with a collection of things which I find interesting to juxtapose.

Also, I have been wondering lately why I've never heard anybody refer to ReLU, a.k.a. the ramp function $R(x),$ as the antiderivative of the Heaviside step function, because it makes the effectiveness of GELU make so much more sense, so I'm referring to it here for anyone who wonders the same thing. 

It also satisfies the differential equation

$$
\frac{d^{2}x}{dx^{2}}R(x - x_{0}) = \delta(x - x_{0}),
$$

which means that it is a Green's function for the second derivative operator, and as such, for any function $f(x)$ with an integrable second derivative $f^{\prime\prime}$, 

$$
f(x) = f(a) + (x - a)f^{\prime}(a) + \int_{a}^{b}R(x - s)f^{\prime\prime}(s)ds, \quad a < x < b,
$$

which is food for thought.

