---
layout: page-fullwidth
title:  "Analysis of Particle Attribute of Microencapsulated Phase Change Materials Using Long Short-Term Memory"
subheadline:  Masters Thesis
teaser: "Using finite volume simulations with machine learning"
categories:
    - prjects
header:
   image_fullwidth: header_unsplash_leaf.jpg
permalink: /projects/ms-thesis/
---

 Tools/Skills: OpenFOAM, MATLAB, high performance computing

Advisor: Dr. Jingru Benner

## Abstract
Microencapsulated phase change materials (MEPCMs) are being studied as an 
environmentally friendly alternative for energy storage in concentrated solar power systems.  During production, the manufacturer can learn valuable information about the particles’ energy storage potential and fabrication process from the particle attributes, particularly the size of the phase change material (PCM) core, but methods for nondestructively measuring this are not widely available in production environments.  Therefore, a method to indirectly estimate the shell-to-core ratio of MEPCMs using a Long Short-Term Memory (LSTM) network is proposed.  This method makes use of the particle’s temperature history during cooling, and simulated data is used to study the method’s feasibility.  It was found that an LSTM network is able to predict the shell-to-core ratio of a copper MEPCM from the supplied temperature data.  Some LSTM hyperparameters, namely the number of neurons and mini-batch size, were found to have a significant effect on the response of the network; therefore, to have the smallest error, the network needs to be tuned.  Finally, the network was generalized to be applicable to multiple PCM types; when given data from copper, aluminum, and zinc MEPCMs, the network still gave an estimate for the shell-to-core ratio.  The error for the generalized case was higher, so the hyperparameters would need to be tuned to fit the larger dataset.  The network’s success using simulated data indicates that it can also be used with experimental data, but further study is required. 
<!--more-->





 [1]: http://foundation.zurb.com/docs/components/grid.html
