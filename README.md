# Contralesional-grey-matter-volume-as-an-index-of-macrostructural-plasticity-

## Table of contents
* [General info](#general-information)
* [Built with](#built-with)
* [License](#license)
* [Contact](#contact)
* [Citation](#citation)

# General information

Welcome! This repository contains the codes developped for the article 'Contralesional grey matter volume as an index of macrostructural plasticity in patients with brain tumors'. 

The study investigates brain-wide structural alterations associated with left-hemisphere brain tumors, focusing on macrostructural changes in the contralesional hemisphere. By combining Voxel-Based Morphometry (VBM) and Principal Component Analysis (PCA), we developed a data-driven approach to characterize deviations from normative structural covariance patterns and investigate their evolution following tumor resection. 

This repository provides the code for the PCA-based anomaly detection approach, which models the normative structural covariance of contralesional grey matter volume using healthy participants and identifies patient-specific deviations from this pattern.

The VBM processing and segmentation steps required to obtain the grey matter volume measurements can be found in the following repository: 
https://github.com/lmansoo/Grey-matter-reshaping-of-language-related-regions-depends-on-tumor-lateralization-/blob/main/README.md

# Built with
For the development of this project, we have used the following softwares and toolboxes in the indicated versions:

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg" height=20 width=20/> Matlab 2014B (The Mathworks, Inc., Natick, MA, USA, 2014.)

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg" height=20 width=20/> Matlab 2021B (The Mathworks, Inc., Natick, MA, USA, 2021.)

<img src="https://www.fil.ion.ucl.ac.uk/spm/images/spm12.png" height=25 width=25/> [Statistical Parametric Mapping](https://www.fil.ion.ucl.ac.uk/spm/) (SPM12) toolbox in Matlab for the processing of the images. 

<img src="https://people.cas.sc.edu/rorden/mricro/icon.png" height=10 width=15/> [Mricron](https://www.nitrc.org/projects/mricron) software for creating the tumor masks 

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height=20 width=20/> Python(Python Software Foundation).

# License
Apache License 2.0

# Contact
- Lucía Manso-Ortega: 📧 lmanso@bcbl.eu 🐦 [@lmanso_](https://twitter.com/lmanso_?t=IrcvEAfN-fsiAWpH_0HFhA&s=08)

# Citation
If you use this code, please cite as: 

  Manso-Ortega, L., Gisbert-Muñoz, S., Amoruso, L., Bermúdez, G., Gil-Robles, S., Pomposo, I., Carreiras, M., & Quiñones, I. (2026). Contralesional grey matter volume as an index of macrostructural plasticity in patients with brain tumors. NeuroImage, 337, 122029. 10.1016/j.neuroimage.2026.122029.
