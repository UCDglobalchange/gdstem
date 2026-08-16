---
layout: page
title: Model Description and Structure
description: Learn about the structure, biogeochemical processes, vegetation representation, land-use dynamics, environmental drivers, inputs, and outputs represented by GDSTEM.
banner: /assets/images/banners/model-banner.jpeg
banner_alt: Savannah
---

# Model Description and Structure

GDSTEM is a process-based terrestrial ecosystem model that simulates coupled **carbon, nitrogen, and water dynamics** within natural and managed terrestrial ecosystems. The model represents vegetation structure, land-use and land-management dynamics, and ecosystem responses to environmental drivers including climate, atmospheric CO₂, nitrogen deposition, and tropospheric ozone.

<img src="assets/images/gdstem-schematic.png"
     alt="Detailed schematic of the GDSTEM model"
     class="clickable-image">

*Figure 1. Schematic of GDSTEM showing major ecosystem pools, fluxes, processes, and environmental inputs.*

---

## Carbon, nitrogen, and water cycling

### Carbon cycle

GDSTEM represents the uptake, allocation, storage, and loss of carbon through vegetation and soils.

Vegetation carbon is distributed among structural and storage pools including:

- Leaves
- Fine roots
- Sapwood
- Heartwood
- Labile and seed storage

Major carbon fluxes include gross primary productivity (GPP), autotrophic respiration, net primary productivity (NPP), vegetation turnover, litter production, soil decomposition, heterotrophic respiration, dissolved organic carbon losses, and carbon fluxes associated with land-use change and management.

The model tracks changes in vegetation and soil carbon stocks through time in response to environmental conditions, ecosystem development, and disturbance.

### Nitrogen cycle

GDSTEM represents an **open nitrogen cycle** based on developments introduced in TEM6.0. Nitrogen can enter, cycle through, and leave terrestrial ecosystems through multiple pathways.

Processes represented include:

- Atmospheric nitrogen deposition
- Biological nitrogen fixation
- Nitrogen uptake by vegetation
- Nitrogen fertilization
- Mineralization and immobilization
- Dissolved inorganic nitrogen leaching
- Dissolved organic nitrogen losses
- Denitrification

Nitrogen availability interacts with vegetation productivity and carbon cycling, allowing nutrient limitation to influence ecosystem responses to environmental change.

### Water cycle

GDSTEM represents the major terrestrial hydrological processes controlling water availability to vegetation and the transfer of water through ecosystems.

These include precipitation, snow processes, infiltration, soil-water storage, evapotranspiration, drainage, and runoff. Water availability influences vegetation productivity and biogeochemical cycling, providing a coupled representation of carbon, nitrogen, and water dynamics.

---

## Vegetation representation

GDSTEM represents major differences in vegetation physiology, structure, and ecosystem functioning using **plant functional types (PFTs)**.

PFT-specific parameters control processes including photosynthesis, respiration, carbon allocation, vegetation turnover, nitrogen cycling, and water use. The current global model is being calibrated separately for individual PFTs across the range of climate and environmental conditions in which they occur.

Vegetation carbon is explicitly separated among structural components, allowing changes in vegetation allocation and structure to be represented through time.

---

## Land use, cohorts, and ecosystem history

Land-use and land-cover change is represented using a **cohort-based framework**.

Land-use transitions create or modify vegetation cohorts that retain information about ecosystem type, age, and land-use history. Multiple cohorts with different ages and histories can therefore coexist within the same grid cell.

<img src="assets/images/gdstem-cohort-approach.png"
     alt="Example of the GDSTEM cohort-based land-use framework"
     width="75%"
     class="clickable-image">

*Figure 2. Example of how GDSTEM represents historical land-use change using vegetation cohorts.*

This framework allows GDSTEM to represent the ecological consequences of historical land-use transitions and disturbance through their effects on vegetation structure, carbon and nitrogen stocks, and ecosystem fluxes.

The current model represents transitions among:

- Primary vegetation
- Secondary vegetation
- C3 annual crop
- C4 annual crop
- C3 perennial crop
- C4 perennial crop
- Pasture
- Rangeland
- Urban land

Timber harvest can also create secondary vegetation cohorts and alter ecosystem carbon stocks and fluxes.

---

## Land management

GDSTEM represents several forms of land management that modify ecosystem carbon, nitrogen, and water dynamics.

Management processes include:

- Irrigation
- Nitrogen fertilization
- Crop establishment and harvest
- Grazing
- Mowing

**Pasture** and **rangeland** are represented as distinct managed grassland systems. Pasture represents more intensively managed grassland that can receive irrigation and fertilization, whereas rangeland is represented without these management inputs.

The current **C4 perennial crop** is parameterized to represent switchgrass. A **C3 perennial crop** representation based on perennial woody crops such as fruit trees is currently being calibrated.

Urban land is represented as a mixture of vegetated and non-vegetated components, including native vegetation, turf lawn, and impervious surfaces.

---

## Environmental drivers

GDSTEM represents ecosystem responses to interacting environmental and anthropogenic drivers, including:

- Climate variability and change
- Atmospheric CO₂
- Nitrogen deposition
- Tropospheric ozone
- Land-use and land-cover change
- Irrigation
- Fertilization

These drivers influence ecosystem productivity, vegetation structure, nutrient cycling, hydrology, and terrestrial carbon storage.

---

## Spatial and temporal configuration

For global applications, GDSTEM normally operates at:

- **0.5° latitude/longitude spatial resolution**
- **Monthly temporal resolution**

Historical global simulations represent changes in environmental conditions and land use beginning in **1700**.

The underlying model can also be applied at finer spatial and temporal resolutions for regional and site-level applications.

---

## Model inputs and outputs

### Major inputs

GDSTEM uses spatially and temporally varying information describing environmental conditions and human activities. Major inputs include:

- Climate
- Atmospheric CO₂
- Nitrogen deposition
- Tropospheric ozone
- Soil properties
- Vegetation and PFT distributions
- Land-use transitions
- Irrigation
- Nitrogen fertilization
- Ecosystem-specific model parameters

### Major outputs

GDSTEM produces a broad range of ecosystem state variables and fluxes.

Major carbon-cycle outputs include:

- Gross Primary Productivity (GPP)
- Net Primary Productivity (NPP)
- Autotrophic respiration
- Heterotrophic respiration
- Net ecosystem carbon exchange
- Net Biome Productivity (NBP)
- Vegetation carbon
- Soil carbon

Nitrogen-cycle outputs include vegetation and soil nitrogen stocks and fluxes associated with nitrogen uptake, fixation, mineralization, leaching, and denitrification.

Hydrological outputs include evapotranspiration, soil moisture, drainage, and runoff.

The model also produces information describing vegetation structure, ecosystem cohorts, and land-use history.

---

## Net Biome Productivity

GDSTEM uses **Net Biome Productivity (NBP)** to represent the net terrestrial carbon balance after accounting for both ecosystem metabolism and additional carbon fluxes associated with disturbance, land-use change, product pools, dissolved organic carbon losses, and crop establishment.

NBP therefore provides a more complete measure of net ecosystem carbon exchange than the difference between NPP and heterotrophic respiration alone.

---

## Current model status

GDSTEM is under active **development, calibration, and evaluation**.

Current work includes global PFT-specific calibration and benchmarking, continued improvement of ecosystem processes, and development of additional disturbance capabilities. The current model does not include wildfire or wetlands; a **wildfire module is under development**.

A comprehensive GDSTEM model description and evaluation manuscript is currently in preparation.

---

## Model code

The current GDSTEM source code is under active development. A public release of the current model version is planned as ongoing development, calibration, and evaluation progress.

---

## Documentation

Comprehensive model documentation is being developed alongside the GDSTEM description and evaluation manuscript and will be made available on this website.
