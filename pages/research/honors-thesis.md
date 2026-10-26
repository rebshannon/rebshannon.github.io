---
layout: page-fullwidth
title:  "Development of a Heat Transfer Model to Characterize the Solidification Process of Phase Change Materials"
subheadline:  Undergraduate Honors Thesis
teaser: "Characterization of renewable energy storage"
categories:
    - research
header: no
  # image_fullwidth: header_unsplash_leaf.jpg
permalink: /research/honors-thesis/
---

Tools/Skills: OpenFOAM, MATLAB, high performance computing

Advisor: Dr. Jingru Benner

Years: Summer 2020 - Spring 2021

## Abstract
The purpose of this study is to evaluate the effects of microencapsulation on the thermal characteristics of microencapsulated phase change materials (MEPCM).  A phase change material (PCM) stores energy in its latent heat of fusion, and an MEPCM is a particle on the scale of 10-200 microns that consists of a PCM core and an encapsulating shell.  MEPCM are being studied for their applications in energy storage for concentrated solar power.  A numerical analysis of MEPCM is performed to study the effects of the encapsulation on the particles’ heat transfer rate and energy density. 

A numerical model of the particle was developed using OpenFOAM software, which was accessed through the Boston University shared computing cluster at the Massachusetts Green High Performance Computing Center.  The encapsulation material was fused silica and the core materials were tin, aluminum, and copper.  The core radius was 50 microns and the shell thickness varied between 0 and 50 microns.  The initial temperature of the particle, heat transfer coefficient, and temperature of the heat transfer fluid were varied to determine each parameter’s effects on the heat transfer rate and energy density. 

It was found that increasing the shell thickness increased the heat transfer rate and decreased the energy density.  The particles with a tin core had the lowest energy density.  Aluminum and copper had comparable energy density results, but aluminum had a slight advantage over copper. For a given material, the cases where the phase change took place stored more energy than those that did not, meaning that more energy is stored in latent heat than sensible heat. 

The effects of the encapsulation on the heat transfer rate and energy density were as expected based on the convective heat transfer equation.  Similarly, the increased initial temperature, ambient emperature, and heat transfer coefficient followed the expected trends.  Aluminum and copper had higher energy densities than the tin cases because of the higher latent heat storage. However, most of conditions in this study did not allow copper to start or finish the phase change, so this material stored mostly sensible heat.  Therefore, within the scope of the study, aluminum had the best performance of storing latent heat as a PCM.  It is worth noting that at higher temperatures, copper will have a higher energy density if the phase change can be completed. 


<!--more-->




