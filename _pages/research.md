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
- Quantitative observing system design
- Dynamical proxy potential of the OSNAP array
- Remote drivers of Nordic Seas heat anomalies and climate predictability
- Ice-ocean interactions
- Constraints of proxy data on past ocean circulation


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

## Ice-ocean interactions 

<figure>
  <img src="/assets/images/Greenland.png" alt="">
  <figcaption> 
Sensitivity of subsurface temperature close to (left) Jakobshavn Isbræ and (right) Helheim Glacier to changes in remote surface heat fluxes on a 5-year timescale.
</figcaption>
</figure>

The interaction of warm subpolar North Atlantic ocean waters with Greenland's marine-terminating glaciers is a dominant trigger for the glaciers' retreat and acceleration. Jakobshavn Isbræ and Helheim Glacier are two examples of marine-terminating glaciers in Greenland that have gained much attention recently, as they have undergone rapid changes since the 1990s. I am exploring the sensitivity of subsurface temperature close to Greenland's marine-terminating glaciers, such as Jakobshavn Isbræ and Helheim Glacier, to climate signals in the far-field.

Related publications: Loose, [PhD Dissertation](http://bora.uib.no/handle/1956/24456), 2019.


## Constraints of proxy data on past ocean circulation

<figure>
  <img src="/assets/images/MIS3cores.png" alt="">
  <figcaption> 
Marine sediment core locations with SST proxy data from marine isotope stage 3 (29-60 kyr ago) during the last glacial, which shows a number of abrupt climate change events. What dynamical constraints are provided by proxy data, taking into account its sparsity and uncertainty?
</figcaption>
</figure>

Paleoclimate archives provide information on the evolution of past climates and can improve our understanding of the processes that underlie low-frequency variability in the climate system. 
However, paleoceanographic data types and coverage are (and always will be) very limited, and proxy data entails large uncertainties. 
For paleoclimate reconstructions, model-data synthesis is promising since it permits using dynamical principles to constrain interpretations of proxy observations and to compute unobservable climate aspects.
I'm interested in quantifying the capability of the available proxy data to dynamically constrain ocean circulation of the past, taking into account its sparsity and uncertainties.

Related publications: Loose, [PhD Dissertation](http://bora.uib.no/handle/1956/24456), 2019.
