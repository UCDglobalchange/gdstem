# GDSTEM Website

This repository contains the source code for the GitHub Pages site for the Global Dynamical and Structural Terrestrial Ecosystem Model (GDSTEM) hosted and maintained by the UC Davis Global Environmental Change Lab.

🌐 Live site: https://UCDglobalchange.github.io/gdstem/

---

## Overview

This website provides:
- A high-level description of the model  
- A schematic figure illustrating the model structure  
- Links to the source code repository  
- References to publications using the model  
- (Coming soon) performance comparisons with related models  

---

## Repository Structure
.
├── index.md # Main landing page
├── pages/ # Additional pages (comparisons, results, etc.)
│ └── comparisons.md
├── assets/
│ └── images/ # Figures and schematics
│ └── model-schematic.png
├── _layouts/ # Jekyll HTML layouts (optional)
├── _includes/ # Reusable components (optional)
├── _config.yml # Site configuration
└── README.md


---

## Editing Content

Most content is written in Markdown (`.md` files).

To update the site:
1. Edit `index.md` or files in `pages/`
2. Commit and push changes
3. GitHub Pages will automatically rebuild the site

---

## Adding Figures

1. Place images in:
assets/images/

2. Reference them in Markdown:
```markdown
![Model schematic](assets/images/model-schematic.png)
