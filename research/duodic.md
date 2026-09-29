---
layout: research-topic
title: "DuoDIC: an open-source stereo DIC toolbox"
title_link: https://github.com/SolavLab/DuoDIC
authors: "Asaf Silverstein & Dana Solav"
permalink: /research/duodic/
redirect_from: /duodic
---

<p>DuoDIC is an open-source MATLAB toolbox for three-dimensional (stereo) Digital Image Correlation (3D-DIC) using two cameras. For multi-view (3 cameras or more), please visit our <a href="https://github.com/MultiDIC/MultiDIC" target="_blank" rel="noopener">MultiDIC toolbox</a>. 3D-DIC is an important technique for measuring the mechanical behavior of materials. DuoDIC was developed to allow simple calibration and data processing and to be easily adaptable to different experimental requirements. DuoDIC integrates the 2D-DIC subset-based software <a href="https://github.com/justinblaber/ncorr_2D_matlab" target="_blank" rel="noopener">Ncorr</a> with MATLAB's camera calibration algorithms to reconstruct 3D surfaces from stereo image pairs. Moreover, it contains algorithms for computing and visualizing 3D displacement, deformation, and strain measures. High-level scripts allow users to perform 3D-DIC analyses with minimal interaction with MATLAB syntax, while proficient MATLAB users can also use stand-alone functions and data structures to write custom scripts for specific experimental requirements. Comprehensive documentation, <a href="https://github.com/SolavLab/DuoDIC/blob/main/docs/instructions/DuoDIC_instruction_manual_1_1_0.pdf" target="_blank" rel="noopener">instruction manual</a>, and <a href="https://github.com/SolavLab/DuoDIC/tree/main/sample_data" target="_blank" rel="noopener">sample data</a> are included. Validation results are included in the <a href="https://joss.theoj.org/papers/10.21105/joss.04279" target="_blank" rel="noopener">JOSS paper</a>.</p>

<figure class="topic-figure">
  <img src="{{ '/assets/img/research/duodic.gif' | relative_url }}" alt="DuoDIC 3D displacement field animation" loading="lazy">
</figure>
