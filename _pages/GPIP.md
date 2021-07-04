---
title: "GPIP"
permalink: /GPIP
layout: single
date: 2020-02-25
---

# **<center>Group Prior Individual Parcellation</center>**

## Introduction

Cortical parcellation based on resting fMRI is an important tool for investigating the functional organization and connectivity of the cerebral cortex. Group parcellation based on co-registration of anatomical images to a common atlas will inevitably result in errors in the locations of the boundaries of functional parcels when they are mapped back from the atlas to the individual. This is because areas of functional specialization vary across individuals in a manner that cannot be fully determined from the sulcal and gyral anatomy that is used for mapping between atlas and individual.

We describe GPIP (Group Prior Individual Parcellation), a method that avoids this problem by refining an initial group parcellation so that for each subject the parcel boundaries are optimized with respect to that subject's resting fMRI. Initialization with a common parcellation results in automatic correspondence between parcels across subjects. Further, by using a group sparsity constraint to model connectivity, we exploit group similarities in connectivity between parcels while optimizing their boundaries for each individual.

We applied this approach with initialization on both high and low density group cortical parcellations and used resting fMRI data to refine across a group of individuals. Cross validation studies show improved homogeneity of resting activity within the refined parcels. Comparisons with task-based localizers show consistent reduction of variance of statistical parametric maps within the refined parcels relative to the group-based initialization indicating improved delineation of regions of functional specialization. This method enables a more accurate estimation of individual subject functional areas, facilitating group analysis of functional connectivity, while maintaining consistency across individuals with a standardized topological atlas.

This page provides a MATLAB implementation of GPIP described in

M. Chong, C. Bhushan, A. A. Joshi, S. Choi, J. P. Haldar, D. W. Shattuck, R. N. Spreng, R. M. Leahy, "Individual parcellation of resting fMRI with a group functional connectivity prior", *NeuroImage*, vol. 156, pp. 87--100, 2017. &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Chong_2017_Neuroimage_Group.bib)

Please cite the paper above in your publications if you have used GPIP in your research.

## Disclaimer

IN NO EVENT SHALL THE AUTHORS, THE CONTRIBUTORS, THE DISTRIBUTORS AND THE UNIVERSITY OF SOUTHERN CALIFORNIA ("AUTHORS") BE LIABLE TO ANY PARTY FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES, INCLUDING LOST PROFITS, ARISING OUT OF THE USE OF THIS CODE, EVEN IF THE AUTHORS HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. THE AUTHORS SPECIFICALLY DISCLAIMS ANY WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. FOR RESEARCH PURPOSE ONLY. THIS CODE IS PROVIDED ON A "AS IS" BASIS AND THE AUTHORS HAVE NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS.

## Download

Please follow this [link](https://software.imagicastle.com:48877/download.php?app=gpip){:target="_blank_"} (will open a new page) and fill out the form. An e-mail will be sent to you with a personal download link. 

## Support

Should you have any questions, please contact Dr. Richard Leahy at leahy <i class="fa fa-at" aria-hidden="true"></i> sipi DOT usc DOT edu
