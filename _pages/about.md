---
permalink: /
title: ""
excerpt: "About me"
layout: archive
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
First, two things:

'If I feel unhappy, I do mathematics to become happy. If I am happy, I do mathematics to keep happy.' - Alfred Renyi

'A mathematician is a device for turning coffee into theorems.' - Alfred Renyi


Some questions and thoughts I have about neural networks \(ongoing, in no particular order\)
======
- Why is it almost, but not quite, as effective to make layers very wide instead of networks very deep?
- Restrict your hypothesis class: restrict your kernel to be convolution; restrict your bases to be Fourier modes – can we represent those differences formally through a more coherent description of networks and their constituent operations? In what way might the use of something like [Greg Yang’s tensor notation](https://github.com/thegregyang/GP4A) make comparisons more consistent and difference more obvious?
- Neural networks are really good at finding structure – why? Because in what way might we relate it to their original inspiration from biological design? Brains are really good at finding structure. But there are other things in brains that are equally as active and important as neurons – what are they doing? Can we put them into our mathematical models? Or are they somehow already there?
- Composed tensor operations ~ networks ~ graphs ~ random matrices ...
- Neural networks are a set \[series\] of random matrices \[they are ordered\]. Training is you moving around the space that’s spanned by them.
- Layers of wavelet transforms \- is that like fitting appropriate basis functions for a few rounds first, then you do the final touch of statistical learning magic also known as a linear layer?
- What difference do the different spaces of activation functions mean? An obvious thing is some are more and less differentiable \- what does their smoothness entail? Or they have more and less relation to normal probability distributions \- how does that for instance make more and less connection to the central limit theorem make sense?
