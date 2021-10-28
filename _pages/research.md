---
title: "Research"
layout: single
sitemap: true
permalink: /research/
author_profile: true
toc: true
toc_label: "Research"
toc_icon: "gear"
toc_sticky: true
---

My research lies at the intersection of physical oceanography and computational science. Current research projects include:
- Ocean Mesoscale Eddies
- Uncertainty Quantification & Observing System Design
- Oceanic Teleconnections in the North Atlantic
- Development of Open Source Software Tools

## Ocean mesoscale eddies

<figure>
  <img src="/assets/images/KE.png" width="1000px" alt="">
  <figcaption>Left: The kinetic energy field in NeverWorld2: a high-resolution idealized model that I use for studying the ocean energy cycle.
Right: A schematic of the ocean energy cycle.
</figcaption>
</figure>

Ocean mesoscale eddies are energetic motions that have horizontal scales of tens to hundreds of kilometers.
Despite their relatively small scale, these eddies play an important role in transporting momentum, heat, salt, carbon, and nutrients throughout the world's oceans.
My research focuses on the energy cycle of the ocean mesoscale eddy field – its generation, its interaction with the large-scale flow, and its dissipation. 
To diagnose the energy cycle, I am currently using high-resolution idealized models. 
With a better understanding of the ocean eddy energy cycle, I am hoping to improve the representation of mesoscale processes in global ocean models.


## Uncertainty Quantification & Observing System Design

<figure>
  <img src="/assets/images/QND.png" alt="">
  <figcaption> 
The Global Ocean Observing System (GOOS) consists of an eclectic mix of satellite and in-situ platforms. Designing optimal observing strategies that account for complementarity and redundancy of observational assets is an unsolved scientific and computational challenge.
</figcaption>
</figure>

Ocean observing systems are expensive to build and maintain, and therefore have to be designed carefully. I am interested in questions such as:
- What dynamical information is contained in already existing observation networks? 
- What is the optimal instrument configuration, which is both cost-efficient and capable to monitor key processes and ocean variability?

To tackle these questions, I perform quantitative observing system design, through a combination of adjoint modeling, Bayesian inverse methods, and Hessian uncertainty quantification. By means of these computational tools, quantitative observing system design suggests an optimal observing strategy and supports effective instrument placements in the future.

Related publications: [Loose et al.](https://doi.org/10.1029/2020JC016112), J. Geophys. Res (2020); 
[Loose and Heimbach](https://doi.org/10.1029/2020MS002386), JAMES (2021);
[Fujii et al.](https://www.frontiersin.org/articles/10.3389/fmars.2019.00417/full), Front. Mar. Sci. (2019).

## Oceanic Teleconnections in the North Atlantic

<figure>
  <img src="/assets/images/NordicSeas.png" alt="">
  <figcaption> 
An adjoint-derived sensitivity map that highglights ''sensitive spots'' where wind anomalies can trigger heat anomalies in the Nordic Seas (black contour) months or years later. Both local and remote winds are important!
</figcaption>
</figure>

The seas around Greenland, Iceland, and Norway transport heat from the North Atlantic toward the Arctic.
I am using adjoint-derived sensitivities in the [ECCO](https://ecco-group.org/) state estimate to identify drivers and locations (both near and far) that affect ocean heat transport in this region.

Related publications:
[StoryMap](https://www.ecco-group.org/storymaps.htm?id=43);
 [Loose et al.](https://doi.org/10.1029/2020JC016112), J. Geophys. Res (2020);
Loose, [PhD Dissertation](http://bora.uib.no/handle/1956/24456), 2019.

## Development of open source software tools

I am engaged with developing open-source software tools to enable our Earth Science community to perform data analysis in an efficient and reproducible way. Recently, my focus has been on the python package [GCM-Filters](https://github.com/ocean-eddy-cpt/gcm-filters). 

`GCM-Filters` is a python package that allows scientists to perform spatial filtering analysis in an easy, flexible, efficient, and reproducible way. `GCM-Filters` is designed to work with gridded data that is produced by General Circulation Models (GCMs) of ocean, weather, and climate. Users can employ `GCM-Filters` on either CPUs or GPUs, with NumPy or CuPy input data. Moreover, GCM-Filters leverages Dask and Xarray to support filtering of larger-than-memory datasets and computational flexibility. Community contributions are welcome!

<figure>
  <img src="/assets/images/filter.png" alt="">
  <figcaption> 
Filtering high-resolution model output with the open-source python package GCM-Filters.
</figcaption>
</figure>


