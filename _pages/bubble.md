---
title: "Primordial gravitational radiation from first order phase transition in the early universe"
permalink: /research/bubble/
layout: single
---

## Description: 
The project served as a pedagogical research training for undergraduates. It started from a two-month summer internship (remotely) in the Center for Gravitational Experiment (CGE) in Huazhong University of Science and Technology (HUST) in Wuhan, China, from the end of June to end of August in 2020. After one semester of courses, the work was resumed in the last semester as the undergraduate dissertation (in Chinese, unpublished). The dissertation was defended on May 25th 2021 at CGE in HUST. 

Motivated by the inflation models and some extensions for the standard model (BSM) of particle physics, it's generally believed that first order phase transition for a scalar field in the early universe, e.g., the inflaton, or the Higgs in BSM, can be a promising source for primordial gravitational wave (GW) background. The work studies a toy model for such a scenario, the collision of two simultaneously nucleated vacuum bubble formed after the quantum turnelling of the scalar field from a false to true vacuum state. Numerical simulations were done by coding in Matlab from scratch, with the typical discretization methods learned from textbooks. The GW power spectrum for the simulated scenario was computed at the end. 

In the two months of 2020 (at home), with no prior experience in numerical physics, I trained myself by reading and doing the exercises in the book, *Numerical Methods for Physics* by Alejandro L. Garcia. Coleman's bounce solution [1] as the field profile for vacuum bubble was generalized from 1D to 3D by numerical codes, and test codes for the collision dynamics were executed for 1D and 2D. From February to May in 2021, the collision dynamics for 3D vacuum bubbles were done for both zero and finite temperature, energy conservation for single bubble expansion was tested, and codes were written to project out the transverse-traceless components of metric perturbation for GW power spectrum computation, following the prescription of Garcia-Berllido *et. al* [5]. 


### Video for 2 vacuum bubble collition: 
<video width="640" height="360" controls>
  <source src="/files/TwoBubbleCollisionIn3D.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

Description:

The potential adopted here is taken from [2]
$$
V(\phi) = \frac{\lambda}{8} (\phi^2 - \phi_0^2)^2 + \epsilon \lambda \phi_0^3 (\phi + \phi_0).
$$
$\phi = \pm \phi_0$ is the degenerate vacuum. $\epsilon$ is a parameter characterising the breaking degeneracy. It's assumed that the expansion timescale is much shorter than Hubble expansion scale $H^{-1}$ at the time of phase transition, so that the spacetime background is approximated as Minkowski. The bubble field profile was solved from the bounce solution introduced by Coleman [1], who also argued in the same paper that the field evolves classically after the quantum turnelling to form the true vacuum bubbles. The field dynamics is simulated by evolving the equation of motion, and basically captures the oscillating pattern the the collision region mentioned in [2].

### Video for energy conservation of 1 bubble expansion:
<video width="640" height="360" controls>
  <source src="/files/OneBubbleTest.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

Description:


### Video for finite temperature collision:
<video width="640" height="360" controls>
  <source src="/files/TwoCollidingBubbles.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

Description ...... 

Power spectrum of the finite temperature collision:
(put the figure, with some caption)


## Main references

1. 
2. 



<div style="text-align: center;">
  <img src="/files/CGEpicture.png" alt="Experiment Setup for Project 1" />
  <p><em>CGE at HUST</em></p>
</div>


