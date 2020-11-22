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

Operator Norms
======
$\newcommand{\ceil}[1]{\lceil#1\rceil}
\newcommand{\floor}[1]{\lfloor#1\rfloor}
\newcommand{\of}[1]{\left(#1\right)} 
\newcommand{\at}[1]{\left[#1\right]}
\newcommand{\substitute}[1]{\left(#1\right)} 
\newcommand{\tuple}[1]{\left(#1\right)}
\newcommand{\inner}[3]{\left(#1, #2\right)_{#3}}

\newcommand{\braces}[1]{\left\{#1\right\}}
\newcommand{\abs}[1]{\lvert#1\rvert}
\newcommand{\norm}[1]{\lvert\lvert#1\rvert\rvert}
\newcommand{\bra}[1]{\langle#1\rvert}
\newcommand{\ket}[1]{\lvert#1\rangle}
\newcommand{\braket}[1]{\langle#1\rangle}$

1. Consider $\mathcal{A}\left[{u, \gamma}\right] : H_{0}^{1}\of{\Omega} \rightarrow \mathbb{R}$ as a linear functional such that $\mathcal{A}\left[{u, \gamma}\right]\left({\phi}\right) := \langle{\mathcal{A}'rangle\left[{u, \gamma}, \phi\right]$

1. Define the norm of $\mathcal{A}\left[{u, \gamma}\right]$ induced by the H1 norm as
    $\lvert\mathcal{A}\left[u, \gamma\right]\rvert_{op} := \sup_{\phi\in H^{1}_{0}, \phi\neq 0}\frac{\langle\mathcal{A}left[{u, \phi}\right], \phi\rangle \lvert\lvert{\phi}\rvert\rvert_{H^1}$
    where the $H^{1}$-norm of $\phi$ is given by $\lvert\lvert{\phi}^{2}\rvert\rvert_{H^{1}\of{\Omega}} = \int_{\Omega}\lvert\phi\left({x\right)\rvert^{2} + \lvert\nabla\phi\left(x\right)^{2}\rvert dx$
    
1. With the parameterized $\tuple{u_\Theta, \gamma_\Theta}$ and $\phi_\eta$, define
    $E\left(\Theta, \eta\right) := \lvert\langle\mathcal{A}\left[u_\Theta, \gamma_\Theta\right], \phi_{\eta}\rangle\rvert^{2}$
