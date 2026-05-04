---
layout: default
title: Model
---

# GDSTEM Model Description

## Overview

The **Global Dynamical and Structural Terrestrial Ecosystem Model (GDSTEM)** is a
process-based model designed to simulate terrestrial ecosystem dynamics at the
global scale.

It combines:
- Biogeochemical cycling
- Vegetation structural dynamics
- Land-use transitions

---

## 🧩 Model Structure

![GDSTEM schematic](assets/images/schematic.png)

GDSTEM represents ecosystems using a **cohort-based approach**, where each grid
cell contains multiple vegetation cohorts that differ in:
- Age (stand age)
- Plant functional type (PFT)
- Disturbance history

---

## 🔄 Land-Use Dynamics

Land-use and land-cover change (LULCC) is a central feature of GDSTEM.

The model tracks transitions between:
- Primary vegetation
- Secondary vegetation
- Cropland
- Pasture
- Urban land

These transitions:
- Modify vegetation structure
- Trigger disturbance processes
- Influence carbon fluxes

---

## 🌿 Carbon Cycle

GDSTEM simulates carbon storage and fluxes across:
- Leaves
- Roots
- Wood (sapwood and heartwood)
- Soil organic carbon pools

Key fluxes include:
- Gross Primary Production (GPP)
- Net Primary Production (NPP)
- Ecosystem respiration
- Net Biome Production (NBP)

---

## 🧪 Model Code

The GDSTEM source code is available on GitHub:

👉 https://github.com/UCDglobalchange/gdstem

---

## 📄 Documentation (coming soon)

- Model equations
- Parameter descriptions
- Input datasets
