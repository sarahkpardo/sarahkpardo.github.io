---
permalink: /
title: "This is Sarah's academic website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

It is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages.

Operator Norms
======
1. Consider $\mathcal{A}\at{u, \gamma} : H_{0}^{1}\of{\Omega} \rightarrow \mathbb{R}$ as a linear functional such that $\mathcal{A}\at{u, \gamma}\of{\phi} := \braket{\mathcal{A}\at{u, \gamma}, \phi}$
1. Define the norm of $\mathcal{A}\at{u, \gamma}$ induced by the H1 norm as
    $$\norm{\mathcal{A}\at{u, \gamma}}_{op} := \sup_{\phi\in H^{1}_{0}, \phi\neq 0}\frac{\braket{\mathcal{A}\at{u, \phi}, \phi}}{\norm{\phi}_{H^1}}$$
    where the $H^{1}$-norm of $\phi$ is given by $$\norm{\phi}^{2}_{H^{1}\of{\Omega}} = \int_{\Omega}\of{\abs{\phi\of{x}}^{2} + \abs{\nabla\phi\of{x}}^{2}}dx$$
1. With the parameterized $\tuple{u_\Theta, \gamma_\Theta}$ and $\phi_\eta$, define
    $$E\of{\Theta, \eta} := \abs{\braket{ \mathcal{A}\at{u_\Theta, \gamma_\Theta}, \phi_{\eta}}}^{2}$$
