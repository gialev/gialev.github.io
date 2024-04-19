---
title: Saddle Point Search Algorithms for Variational Density Functional Calculations
  of Excited Electronic States with Self-Interaction Correction
authors:
- Yorick Leonard Adrian Schmerwitz
- Núria Urgell Ollé
- Gianluca Levi
- Hannes Jónsson
date: '2024-01-01'
publishDate: '2024-04-19T00:56:53.583017Z'
publication: '*Proceedings of the Platform for Advanced Scientific Computing (PASC) 2024 Conference (accepted)*'
publication_types:
- article-journal
doi: '10.48550/arXiv.2402.16601'
abstract: Excited electronic states of molecules and solids play a fundamental role
  in fields such as catalysis and electronics. In electronic structure calculations,
  excited states typically correspond to saddle points on the surface described by
  the variation of the energy as a function of the electronic degrees of freedom.
  A direct optimization algorithm based on generalized mode following is presented
  for density functional calculations of excited states. While conventional direct
  optimization methods based on quasi-Newton algorithms usually converge to the stationary
  point closest to the initial guess, even minima, the generalized mode following
  approach systematically targets a saddle point of a specific order l by following
  the l lowest eigenvectors of the electronic Hessian up in energy. This approach
  thereby recasts the challenging saddle point search as a minimization, enabling
  the use of efficient and robust minimization algorithms. The initial guess orbitals
  and the saddle point order of the target excited state solution are evaluated by
  performing an initial step of constrained optimization freezing the electronic degrees
  of freedom involved in the excitation. In the context of Kohn-Sham density functional
  calculations, typical approximations to the exchange-and-correlation functional
  suffer from a self-interaction error. The Perdew and Zunger self-interaction correction
  can alleviate this problem, but makes the energy variant to unitary transformations
  in the occupied orbital space, introducing a large amount of unphysical solutions
  that do not fully minimize the self-interaction error. An extension of the generalized
  mode following method is proposed that ensures convergence to the solution minimizing
  the self-interaction error.
tags:
- density functional calcula-
- excited states
- generalized
- saddle point searches
- self-interaction correction
- tions
- variational calculations
links:
- name: arXiv
  url: https://arxiv.org/abs/2402.16601
- name: URL
  url: http://arxiv.org/abs/2402.16601
---
