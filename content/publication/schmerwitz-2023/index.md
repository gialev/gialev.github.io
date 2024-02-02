---
title: Calculations of Excited Electronic States by Converging on Saddle Points Using
  Generalized Mode Following
authors:
- Yorick L. A. Schmerwitz
- Gianluca Levi
- Hannes Jónsson
date: '2023-01-01'
publishDate: '2024-02-02T14:14:57.364513Z'
publication_types:
- article-journal
publication: '*Journal of Chemical Theory and Computation*'
doi: 10.1021/acs.jctc.3c00178
abstract: Variational calculations of excited electronic states are carried out by
  finding saddle points on the surface that describes how the energy of the system
  varies as a function of the electronic degrees of freedom. This approach has several
  advantages over commonly used methods especially in the context of density functional
  calculations, as collapse to the ground state is avoided and yet, the orbitals are
  variationally optimized for the excited state. This optimization makes it possible
  to describe excitations with large charge transfer where calculations based on ground
  state orbitals are problematic, as in linear response time-dependent density functional
  theory. A generalized mode following method is presented where an $n^textth$-order
  saddle point is found by inverting the components of the gradient in the direction
  of the eigenvectors of the $n$ lowest eigenvalues of the electronic Hessian matrix.
  This approach has the distinct advantage of following a chosen excited state through
  atomic configurations where the symmetry of the single determinant wave function
  is broken, as demonstrated in calculations of potential energy curves for nuclear
  motion in the ethylene and dihydrogen molecules. The method is implemented using
  a generalized Davidson algorithm and an exponential transformation for updating
  the orbitals within a generalized gradient approximation of the energy functional.
  Convergence is found to be more robust than for a direct optimization approach previously
  shown to outperform standard self-consistent field approaches, as illustrated here
  for charge transfer excitations in nitrobenzene and N-phenylpyrrole, involving calculations
  of $4^textth$- and $6^textth$-order saddle points, respectively. Finally, calculations
  of a diplatinum and silver complex are presented, illustrating the applicability
  of the method to excited state energy curves of large molecules.
links:
- name: arXiv
  url: https://arxiv.org/abs/2302.05912
- name: URL
  url: https://doi.org/10.1021/acs.jctc.3c00178
---
