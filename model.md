---
layout: page
title: Model
banner: /assets/images/banners/model-banner.jpeg
banner_alt: Savannah
---

# Model

---

## Overview

The **Global Dynamical and Structural Terrestrial Ecosystem Model (GDSTEM)** is a
process-based model designed to simulate terrestrial ecosystem dynamics at the
global scale.

It combines:
- Biogeochemical cycling
- Vegetation structural dynamics
- Land-use transitions

---

## Model Structure

<img src="{{ site.baseurl }}/assets/images/gdstem-schematic.png"
     alt="GDSTEM schematic"
     class="clickable-image">

*Figure 1. Conceptual schematic of the GDSTEM model showing major components and fluxes.*


GDSTEM simulates carbon storage and fluxes across:
- Leaves
- Roots
- Stem (sapwood and heartwood)
- Soil organic carbon pools

Key fluxes include:
- Gross Primary Production (GPP)
- Net Primary Production (NPP)
- Ecosystem respiration
- Net Biome Production (NBP)

---

## Land-Use Dynamics

Land-use and land-cover change (LULCC) is a central feature of GDSTEM, which tracks land use history using a cohort approach.

<img src="{{ site.baseurl }}/assets/images/gdstem-cohort-approach.png"
     alt="GDSTEM cohort approach"
     class="clickable-image">

*Figure 2. Example of how GDSTEM tracks historical land-use change through its cohort approach.*

The model tracks transitions between:
- Primary vegetation
- Secondary vegetation
- C3 crops
- C4 crops
- Perennial crops
- Pasture
- Rangeland
- Urban land

These transitions modify the vegetation structure, trigger disturbance processes, and influence water, carbon, nitrogen, and energy fluxes.

---

## Model Code

The source code of GDSTEM used on the Global Carbon Budget 2025 is available on GitHub: <https://github.com/UCDglobalchange/gdstem-trendyv14>

---

## Documentation (coming soon)

We are currently working on a description and evaluation manuscript. 
