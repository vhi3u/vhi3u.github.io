---
layout: default
title: "research"
permalink: /research/
---
## Southern Ocean Biophysical Modeling (GT 2026 - Present)

Presently, I am developing  high-resolution regional model of the Eastern Southern Ocean using NumericalEarth, a modular modeling framework that can simulate the Earth system, using Oceananigans as the ocean component. This work is advised by [Dr. Lilian Dove](https://www.gato-lab.com/team). This model will be used to evaluate the spatiotemporal evolution of Antarctic Winter Water, and how biogeochemical tracers evolve within it. At the moment, I am working on implementing the Biogeochemical Southern Ocean State Estimate (B-SOSE) reanalysis data as boundary conditions for our model. 

This work will be partially funded by an NSF Graduate Research Fellowship. 

<figure style="margin: 1em 0; text-align: center;">
  <video src="{{ '/assets/bsose_i156_surface_201406_to_201605.mp4' | relative_url }}" controls autoplay loop muted playsinline style="max-width: 100%; height: auto;"></video>
  <figcaption style="font-size: 0.9em; font-style: italic; margin-top: 0.5em;">2-year monthly average snapshots of B-SOSE surface physical fields (temperature, salinity, zonal velocity, and meridional velocity). </figcaption>
</figure>


## Shoal-Flow Interactions (UNC 2025 - 2026)

I completed an honors thesis research project in collaboration with [Dr. Ken Zhao](https://unc-ocean-dynamics.github.io/) and [Dr. Harvey Seim](https://tarheels.live/seimlab/). For this project, we study how coastal bathymetry and winds drive offshore transport and eddy kinetic energy. This study uses an idealized hydrostatic model of barotropic flow over a shoal, lightly based off the coastal bathymetry of the Diamond Shoals off of coastal North Carolina. 

Manuscript in preparation for submission in Journal of Geophysical Research: Oceans. 

<figure style="margin: 1em 0; text-align: center;">
  <video src="{{ '/assets/shoal_reference_clipped.mp4' | relative_url }}" controls autoplay loop muted playsinline style="max-width: 100%; height: auto;"></video>
  <figcaption style="font-size: 0.9em; font-style: italic; margin-top: 0.5em;">Surface animation of temperature, salinity, cross-shore velocity, along-shore velocity, vorticity, and kinetic energy for reference run simulation of 0.2 m/s barotropic flow over a shoal. Shoal length is 40 km, and shoal depth is 5 m. Simulation ran for 50 days. </figcaption>
</figure>

## Cape Hatteras Mixing (UNC 2023 - 2026)

The Cape Hatteras coastal region off of North Carolina showcases a unique biogeographic boundary, driven by convergent shelfwater flow and influence from the Gulf Stream. Recent Gulf Stream deviations in position, as well as sea level rise north of Cape Hatteras show potential for large shifts in  atmospheric/oceanic forcings, and their effects on shelf and open ocean water exchange is understudied. Furthermore, the varying position of the Hatteras Front, this convergence, signals for a recharacterization of the Cape Hatteras coastal region as more of a "mixing zone" rather than a frontal system. 

I joined Dr. Harvey Seim's [Observational Physical Oceanography Lab](https://tarheels.live/seimlab/) in my spring semester freshman year at UNC (2023). In 2017-2018, my PI led the Processes Driving Exchange at Cape Hatteras (PEACH) Program, where several scientists made use of various observational instruments to better understand seawater exchange between the continental shelf and open ocean near Cape Hatteras, North Carolina. 

I used data collected from PEACH to study the hydrographic variability of the shelf near Cape Hatteras. This study uses underwater Slocum glider to observe the physical and biological characteristics of the water column. Concurrently, I worked as a glider pilot with SECOORA which provided oceanographic data off the coast of Georgia for hurricane forecasting. 

<figure style="margin: 1em 0; text-align: center;">
  <video src="{{ '/assets/r6salTempUVL.mp4' | relative_url }}" controls autoplay loop muted playsinline style="max-width: 100%; height: auto;"></video>
  <figcaption style="font-size: 0.9em; font-style: italic; margin-top: 0.5em;">Glider trajectory for Ramses 6 deployment (September 2018) with salinity (left) and temperature (right) indicated by coloration. Smaller dots represent the temperature/salinity of the lower third of the water column, while the larger outlined circle corresponds to the upper third of the water column. </figcaption>
</figure>

You can view my visualization scripts and preliminary figures [here](https://github.com/vhi3u/peachVIS).

## Carbon Dioxide Removal Long-term Impacts on Ocean and Atmosphere (TAMU 2024)

The burning of fossil fuels since the start of the Industrial Revolution has led to increased CO2 emissions, reaching levels higher than any time in the past 2 million years. In addition to reducing emissions through policy initiatives and transitioning to renewable energy sources, implementing technologies for carbon dioxide removal (CDR) has received growing attention.

In Summer 2024, I joined Dr. Shuang Zhang's [CArbon Cycle and Earth Environment (CACEE) Lab](https://www.caceelab.space/) at Texas A&M University as a part of an REU with the Department of Oceanography. Here, I worked with Dr. Zhang and PhD student Shihan Li to look at how different methods of CDR impact the ocean and atmosphere. Understanding how ocean and atmospheric tracers are impacted by CDR is an important contribution towards building a framework for monitoring, reporting, and verification (MRV) of CDR projects.

Our medium for studying this is the **i**nteractive **L**ong-term **O**cean-atmosphere-**S**ediment **CA**rbon cycle **R**eservoir (iLOSCAR) model, developed here at Texas A&M University. We used iLOSCAR to run simulations over more than 500 years to see how ocean/atmosphere tracers such as pCO₂, temperature, pH, and saturation states of aragonite and calcite change when we introduce fluxes attributed to CDR. iLOSCAR has both an inverse and forward component, and features a web-based UI that makes running the simulations simpler.

<figure style="margin: 1em 0; text-align: center;">
  <img src="{{ '/assets/LOSCAR-simplified.png' | relative_url }}" alt="Simplified diagram of the LOSCAR model" style="max-width: 100%; height: auto;" />
  <figcaption style="font-size: 0.9em; font-style: italic; margin-top: 0.5em;">Schematic of original LOSCAR model. Boxes represent (A) Atlantic Ocean, (I) Indian Ocean, (P) Pacific Ocean, (H) High-latitude regions, and each box has a (L) surface, (M) intermediate, (D) deep layers, and (Sed) sediment component. </figcaption>
</figure>

More work on iLOSCAR can be found [here](https://github.com/Shihan150/iloscar).
