---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

Magnetic reconnection is the process by which magnetic energy is converted to particle energy through a topological rearrangement of magnetic field lines, and it is thought to be involved in a host of plasma phenomena including solar flares, coronal mass ejections, and the generation of terrestrial aurorae. Though a ubiquitous process, the underlying dynamics of magnetic reconnection are not yet well understood. Several fluid models exist to explain reconnection, but are generally insufficient in explaining a process that is innately intertwined with small-scale kinetic physics (which is based on statistical distribution functions).

Computational simulation is vital to understanding magnetic reconnection, as it complements experimental observation with superior data resolution and access to a larger region of parameter space. For magnetic reconnection, the kinetic models required to capture full electron and ion dynamics necessitate the use of high performance computing, as billions of particles regularly cross over domains and constant communication is needed between cores. My research goal is to use VPIC fully-kinetic simulations to model collisionless magneticreconnection and elucidate its underlying dynamics.

An overview of my research for a general audience can be found <a href="https://www.krellinst.org/csgf/fellows/fellow-reflections/blake-wetherton">here</a>.

Drift-kinetic gradients and agyrotropy
=======

My research focuses on collisionless plasma physics. Collisions function to maintain isotropy in the velocity space distribution of a plasma component. In a magnetized collisionless plasma, this means that the dynamics parallel to the local magnetic field can become decoupled from those in the perpendicular plane, leading to anisotropic pressure tensors. This is important in the inflows of collisionless magnetic reconnection, and is the foundation of many of the projects I have worked on. When further nonideal processes are included, the two directions perpendicular to the local magnetic field can decouple. This is called agyrotropy, and it is often taken to be an indicator of particles demagnetizing. One of my favorite projects to date is the development of a drift-kinetic method for determining gradients in plasma properties based on local measurements of the velocity space distribution function. The work establishes a fundamental connection between gradients in plasma properties and agyrotropy in the distribution function. The figure below illustrates the basic principle of how this works, and I now have a draft out of the formal theory, which is based in drift-kinetics and applies vector calculus liberally to estimate gradients in arbitrary moments of the distribution function based on local measurements. That draft can be found <a href="https://arxiv.org/abs/2003.00198">here</a>. 



<figure>
<img src="/images/sat.png" alt="satellite">
<figcaption>Illustration of how a single spacecraft sampling the electron distribution can be applied for characterizing the gradient in the gyrotropic electron distribution function. More electrons coming from a higher density region cause an increased phase space density of electrons traveling in the -y direction. This is also the cause of the diamagnetic drift. </figcaption>
</figure>
