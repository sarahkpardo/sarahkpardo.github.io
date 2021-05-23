---
permalink: /
title: "This is Sarah's academic website"
excerpt: "About me"
layout: splash
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Some questions and thoughts I have about neural networks \(ongoing, in no particular order\)
======
- Do we really need all those parameters? Do we really need all those layers? Why is it not quite the same to make them very wide instead? Should we relate all of the components of all of the dimensions of all of these objects, with a different nonlinear operation? Specifically how do these modifications alter the class of functions and reduce their generality? Does it actually impose a restriction, or does it just make certain states and resulting functions more or less probable?
- What can you do with four neurons and an activation between? What space is that? Is it surprisingly small, or surprisingly big?
- What difference to the different spaces of activation functions mean? An obvious thing is some are more and less differentiable \- what does their smoothness entail? Or they have more and less relation to normal probability distributions \- how does that for instance make more and less invocation of the central limit theorem make sense?
- Restrict your hypothesis class: restrict your kernel to be convolution; restrict your bases to be Fourier modes – can we represent those differences formally through a more coherent description of networks and their constituent operations? In what way might the use of something like [Greg Yang’s tensor notation] (https://github.com/thegregyang/GP4A) make comparisons more consistent and difference more obvious?
- These things are really good at finding structure – why? Because in what way might we relate it to their original inspiration from biological design? Brains are really good at finding structure too. But there are other things in brains that are equally as active and important as neurons – what are they doing? Can we put them into our mathematical models? Or are they somehow already there?
- Composed tensor operations ~ networks ~ graphs ~ random matrices ...
- Neural networks are a set \[series\] of random matrices \[they are ordered\]. Training is you moving around the space that’s spanned by them.
- Layers of wavelet transforms \- is that like fitting appropriate basis functions for a few rounds first, then you do the final touch of statistical learning magic also known as a linear layer?
