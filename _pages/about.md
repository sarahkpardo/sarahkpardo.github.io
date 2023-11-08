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

In the meantime, you can visit [this Zotero library](https://www.zotero.org/groups/5240598/found-objects) where I am gathering a collection of things which I find interesting to look at next to each other. You can also look at some generations I made with DALL-E [here](https://labs.openai.com/sc/RT6MUL6KeUCZSat2AQXU0ZJT). I was totally floored by the humanity of [this one](https://labs.openai.com/s/n6ebRMT5wb57CxkkVWXR34Vu) in particular. On the other hand, [this one](https://labs.openai.com/s/n6ebRMT5wb57CxkkVWXR34Vu) is rather concerning.

***A model, when fitted to data created and labeled by humans, is no less than a mirror which reflects back to us our patterns.***

Also, I have been wondering lately why I've never heard anybody refer to ReLU, i.e. the ramp function $R(x) = \max\\{0, 1\\},$ as the antiderivative of the Heaviside step function, because it makes the effectiveness of GELU make so much more sense. 

$R(x)$ is on my mind at the moment for a variety of reasons, not least of which is that it satisfies the differential equation

$$
\frac{d^{2}x}{dx^{2}}R(x - x_{0}) = \delta(x - x_{0}),
$$

which means that it is a Green's function for the second derivative operator, and as such, for any function $f(x)$ with an integrable second derivative $f^{\prime\prime}$, 

$$
f(x) = f(a) + (x - a)f^{\prime}(a) + \int_{a}^{b}R(x - s)f^{\prime\prime}(s)ds, \quad a < x < b.
$$

Expanded thoughts on the significance of this are also under construction.
