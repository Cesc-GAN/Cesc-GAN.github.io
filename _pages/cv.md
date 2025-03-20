---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Optical Engineering, GitHub University, 2025 (expected)
* B.E. in Opto-electronic Information Science and Engineering, Zhejiang University, 2020

Research experience
======
* Sept. 2020 - present: Modulated illumination based 4Pi wide-field microscopic imaging platform
  * Optical system: Designed and built a 4Pi wide-field microscope platform based on fluorescence interference in the detection path and modulated illumination in the excitation path.
  * Fluorescence interference: Achieved fluorescence interference by fine-tuning the optical length difference between two detection arms; adjusted the uniformity of interference.
  * Control software: Designed and wrote a control software for 4Pi wide-field microscope based on LabVIEW. Achieved synchronized control of opto-electronic devices.
  * Basic super-resolution imaging: Achieved standard 3D structured illumination microscopy (SIM) and 3D single-molecule localization microscopy (SMLM).

* Sept. 2021 - Jul. 2023: Fluorescence interference based structured illumination microscopy
  * Theory and method: Proposed ensemble axial reconstruction method by fluorescence interference and multi-channel detection; theoretical derivation of polarized demodulation to map dipole orientations
  * Reconstruction Algorithm: Proposed an axial reconstruction algorithm based on the intensity distribution in the sub diffraction limit region of fluorescence interference.
  * Experiments and biological imaging: Achieved dynamic observation of polarization information and three-dimensional morphology of subcellular structures (including x, y, z, and polarization information) with 100 nm lateral resolution and sub-30 nm axial accuracy.

* Sept. 2021 - present: Single-molecule modulated illumination localization estimator (Collaborate with Professor Renjie Zhou’s group at the Chinese University of Hong Kong)
  * Theory and imaging model: Explored the principle of modulated illumination based single-molecule localization microscopy; derived Cram´er–Rao Lower Bound of the corresponding imaging modalities.
  * Application of deformable mirror: Calibrated the deformable mirrors through home-built interference system; achieved high axial super-resolution by introducing astigmatism on deformable mirror.
  * Reconstruction algorithm with joint parameter fitting: Achieved fast reconstruction of simulated SMILE data through GPU acceleration and joint parameter fitting.
  * Preparation for biological imaging: Optimized and calibrated relevant experimental parameters, including phase retardance of fluorescence interference, modulation depth of modulated illumination and PSF engineering introduced by deformable mirror.
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
