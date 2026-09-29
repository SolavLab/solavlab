---
layout: research-topic
title: "Soft Hyperelastic Lattice Structures: Numerical Homogenization and Experimental Validation"
authors: "Dror Raf, Itay Magen, Lee Jordan & Dana Solav"
permalink: /research/lattice-structures/
redirect_from: /lattice-structures
---

<p>Lattice structures have become increasingly popular in various applications due to their lightweight and wide range of effective properties that can be locally tailored by adjusting their geometric features. They can be utilised to modulate the stress distribution in biomechanical interfaces that contact the human body, such as shoe soles, cushions, prosthetics, and orthotics. Advancements in additive manufacturing have enabled the fabrication of previously unattainable lattice structures. Finite Element Analysis (FEA) is commonly used to predict their mechanical response and inform inverse design algorithms. Yet, simulating lattice geometries poses significant computational demands owing to the large number of elements needed for meshing them. This challenge can be overcome by replacing the lattice geometry with a homogeneous material with equivalent mechanical properties. However, determining a suitable constitutive model and parameters is difficult, particularly when the mechanical response is nonlinear and anisotropic. To this end, this work involves numerical homogenisation to a hyperelastic orthotropic constitutive law and experimental validation of soft lattice structures.</p>

<p>We conducted experimental and numerical analyses on several thick beam-based lattice structures generated using Creo 9 (PTC, USA). The structures were manufactured using selective laser sintering (SLS) on a Lisa Pro 3D printer (Sinterit, Poland) out of Flexa Bright TPU powder. The printed TPU material parameters were calibrated using tension and compression experiments in three printing orientations. Next, we conducted multiple FEAs simulating large uniaxial tension, compression, and shear deformations. The results of these simulations were used to perform numerical homogenisation to a Fung compressible orthotropic hyperelastic model. We investigated lattice cells with various geometrical parameters (e.g., beam thickness, angles, and aspect ratios) and fitted the homogenised model parameters for each case. Finally, the numerical results were validated against compression experiments on lattice structures by measuring the reaction forces and the full-field surface deformations using 3D digital image correlation (DIC). Overall, the results demonstrate that replacing the lattice structure with the homogenised material in the FEA led to deviations smaller than 8% in the predicted responses compared to the exhaustive simulations of lattice structures, while reducing the computational time by up to three orders of magnitude. Therefore, this method can enhance the design of various biomechanical interfaces with spatially variable mechanical properties, which can be achieved by tailoring the local geometrical properties of lattice cells.</p>

<figure class="topic-figure">
  <img src="https://static.wixstatic.com/media/152d97_8933fa84f6704612a52bf8388b387bf8~mv2.jpg" alt="Lattice structures graphical abstract" loading="lazy">
</figure>

<h2 class="topic-subhead">Related publications</h2>
<ul class="topic-pubs">
  <li>Raf, Dror, Itay Magen, Lee Jordan, and Dana Solav. <a href="https://doi.org/10.1007/s40964-026-01759-9" target="_blank" rel="noopener">“Characterization of the mechanical properties of TPU fabricated by SLS in different printing orientations.”</a> <em>Progress in Additive Manufacturing</em> 11 (2026): 7625–7638. (Preprint: <a href="https://doi.org/10.31224/4689" target="_blank" rel="noopener">EngrXiv</a>)</li>
  <li>Raf, Dror, Itay Magen, Amit Ashkenazi, Lee Jordan, and Dana Solav. <a href="https://doi.org/10.1016/j.mechmat.2025.105534" target="_blank" rel="noopener">“Soft orthotropic hyperelastic lattice structures: numerical homogenization and experimental validation.”</a> <em>Mechanics of Materials</em> 212 (2026): 105534. (Preprint: <a href="https://doi.org/10.31224/4772" target="_blank" rel="noopener">EngrXiv</a>)</li>
</ul>
