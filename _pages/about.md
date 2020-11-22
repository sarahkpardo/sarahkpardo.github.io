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
Operator Norms
======
1. Consider $\mathcal{A}\at{u, \gamma} : H_{0}^{1}\of{\Omega} \rightarrow \mathbb{R}$ as a linear functional such that $\mathcal{A}\at{u, \gamma}\of{\phi} := \braket{\mathcal{A}\at{u, \gamma}, \phi}$

1. Define the norm of $\mathcal{A}\at{u, \gamma}$ induced by the H1 norm as
    $\norm{\mathcal{A}\at{u, \gamma}}_{op} := \sup_{\phi\in H^{1}_{0}, \phi\neq 0}\frac{\braket{\mathcal{A}\at{u, \phi}, \phi}}{\norm{\phi}_{H^1}}$
    where the $H^{1}$-norm of $\phi$ is given by $\norm{\phi}^{2}_{H^{1}\of{\Omega}} = \int_{\Omega}\of{\abs{\phi\of{x}}^{2} + \abs{\nabla\phi\of{x}}^{2}}dx$
    
1. With the parameterized $\tuple{u_\Theta, \gamma_\Theta}$ and $\phi_\eta$, define
    $E\of{\Theta, \eta} := \abs{\braket{ \mathcal{A}\at{u_\Theta, \gamma_\Theta}, \phi_{\eta}}}^{2}$
