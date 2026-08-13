---
layout: page
title: Model Description and Structure
description: Learn about the GDSTEM model structure, processes, inputs, outputs, vegetation represented, land-use cohort representation, and simulation framework.
banner: /assets/images/banners/model-banner.jpeg
banner_alt: Savannah
---

# Model Description and Structure

---

## Overview

**GDTEM, the Global Dynamical and Structural Terrestrial Ecosystem Model** is a
process-based model designed to simulate terrestrial ecosystem dynamics at the
global scale.

It combines:
- Biogeochemical cycling
- Vegetation structural dynamics
- Land-use transitions

---

## Model Structure

<img src="assets/images/gdstem-schematic.png"
     alt="GDSTEM schematic"
     class="clickable-image">

*Figure 1. Detailed schematic of the GDSTEM model showing the various pools, fluxes, processes and input.*


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

<img src="assets/images/gdstem-cohort-approach.png"
     alt="GDSTEM cohort approach" width="75%"
     class="clickable-image">

*Figure 2. Example of how GDSTEM tracks historical land-use change through its cohort approach.*

The model tracks transitions between:
- Primary vegetation
- Secondary vegetation
- C3 annual crop
- C4 annual crop
- C3 perennial crop
- C4 perennial crop
- Pasture
- Rangeland
- Urban

These transitions modify the vegetation structure, trigger disturbance processes, and influence water, carbon, nitrogen, and energy fluxes.

---

## Model Code

The GDSTEM source code used in the Global Carbon Budget 2025 simulations is available on GitHub at:
<https://github.com/UCDglobalchange/gdstem-trendyv14>

---

## Documentation (coming soon)

We are currently working on a description and evaluation manuscript. 
