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
- Development of Open Source Software Tools
- Oceanic Teleconnections in the North Atlantic
- Uncertainty Quantification & Observing System Design



## Development of open source software tools



Applying a spatial filter to gridded data from models or observations is a common analysis method in the Earth Sciences, for example to study oceanic and atmospheric motions at different spatial scales or to develop subgrid-scale parameterizations for ocean models. The spatial filters that are included in existing python packages, such as SciPy's multidimensional Gaussian filter, are typically specialized for image processing. For data from General Circulation Models (GCMs), image processing tools are however of limited use because these tools assume a regular and rectangular Cartesian grid and employ simple boundary conditions. In contrast, GCMs come on irregular curvilinear grids, and continental boundaries in GCMs need more careful treatment than currently supported. 

Here we introduce a new python package, GCM-Filters, which is specifically designed to filter GCM data. The GCM-Filters algorithm applies a discrete Laplacian to smooth a field through an iterative process that resembles diffusion. The discrete Laplacian takes into account the varying grid-cell geometry of the complex GCM grids and uses a no-flux boundary condition, mimicking how diffusion is internally implemented in GCMs and ensuring conservation of the integral. Conservation of the integral is a desirable filter property for many physical quantities, for example energy or ocean salinity. The user can employ GCM-Filters on either CPUs or GPUs, with NumPy or CuPy input data. Moreover, GCM-Filters leverages Dask and Xarray to support filtering of larger-than-memory datasets and computational flexibility.


`GCM-Filters` is a python package that allows scientists to perform spatial filtering analysis in an easy, flexible and efficient way. The package implements the filtering method that was introduced by @grooms2021diffusion. The filtering algorithm is analogous to smoothing via diffusion; hence the name *diffusion-based filters*. `GCM-Filters` is designed to work with gridded data that is produced by General Circulation Models (GCMs) of ocean, weather, and climate. Spatial filtering of GCM data is a common analysis method in the Earth Sciences, for example to study oceanic and atmospheric motions at different spatial scales or to develop subgrid-scale parameterizations for ocean models.

## Quantitative observing system design

<figure>
  <img src="/assets/images/QND.png" alt="">
  <figcaption> 
The Global Ocean Observing System (GOOS) consists of an eclectic mix of satellite and in-situ platforms. Designing optimal observing strategies that account for complementarity and redundancy of observational assets is an unsolved scientific and computational challenge.
</figcaption>
</figure>

Observing systems are expensive to build and maintain, and therefore have to be designed carefully. 
A central focus of my research is the development of quantitative and dynamics-based methods that support the design of long-term effective observing systems. I am interested in questions such as:
- What dynamical information is contained in already existing observation networks? 
- What is the optimal instrument configuration, which is both cost-efficient and capable to monitor key processes and ocean variability?

To tackle these questions, I perform quantitative observing system design, through a combination of adjoint modeling, Bayesian inverse methods, and Hessian uncertainty quantification. By means of these computational tools, quantitative observing system design suggests an optimal observing strategy and supports effective instrument placements in the future.

Related publications: [Loose et al.](https://doi.org/10.1029/2020JC016112), J. Geophys. Res (2020); 
[Loose and Heimbach](https://doi.org/10.1002/essoar.10504562.1), submitted (2020);
[Fujii et al.](https://www.frontiersin.org/articles/10.3389/fmars.2019.00417/full), Front. Mar. Sci. (2019).

## Dynamical proxy potential of the OSNAP array
 
<figure>
  <img src="/assets/images/OSNAP.png" alt="">
  <figcaption> What information do the OSNAP observations (black) provide for remote regions such as (i) subsurface temperature at the East Greenland margin (purple) and (ii) heat content of the Norwegian Sea (green)? </figcaption>
</figure>

The first data from the OSNAP (Overturning in the Subpolar North Atlantic Program) array, a recently installed observing system in the subpolar North Atlantic, has provided new insights into volume, heat, and freshwater transports at the latitudes of the array. A next step is to put the OSNAP observations into a broader spatial and temporal context. I am interested in the following question:
- Can the OSNAP array inform - or could even serve as a _proxy_ for - unobserved hydrographic and circulation quantities remote from the array?

I'm quantifying the proxy potential of the OSNAP array by means of a new dynamics-based technique that uses adjoint modeling and uncertainty quantification within the ECCO (Estimating the Circulation and Climate of the Ocean) state estimation framework.
This technique evaluates OSNAP's proxy potential based purely on dynamical information as opposed to techniques that are based on statistical inference, e.g., correlations, regression and EOFs.

Related publications: [Loose et al.](https://doi.org/10.1029/2020JC016112), J. Geophys. Res (2020); 
“Sensitive Spots … and How to Find Them,” [ArcGis StoryMap](https://ecco-group.org/storymaps.cgi?id=43), based on Loose et al. (2020), ECCO group website, uploaded August 2020;
Loose, [PhD Dissertation](http://bora.uib.no/handle/1956/24456), 2019.

## Remote drivers of Nordic Seas heat anomalies and climate predictability

<figure>
  <img src="/assets/images/sens2wind.png" width="1000px" alt="">
  <figcaption>Sensitivity of Nordic Seas heat content to wind perturbations at a lead time of 3 years. The eastern boundary of the North Atlantic and the intergyre boundary are oceanic regions that may help predict northern climate. </figcaption>
</figure>

Variability in the poleward progression of ocean heat across the Nordic Seas - from the subpolar North Atlantic towards the Arctic Ocean - is important for Arctic sea ice, melting of the Greenland Ice Sheet, and northwestern European climate. 
I'm trying to understand what drives anomalies in Nordic Seas heat content on seasonal to decadal timescales. 
I'm particularly interested in _where_ and _at what lead times_ such heat anomalies originate, because anomalies that originate remotely may contribute to decadal climate predictability.

To identify remote origins and drivers of climate predictability, I'm using the ECCO (Estimating the Circulation and Climate of the Ocean) state estimate and adjoint-derived sensitivities.

Related publications: Loose, [PhD Dissertation](http://bora.uib.no/handle/1956/24456), 2019.



