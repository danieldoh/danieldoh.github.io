---
title: Vertically Integrated Projects (VIP Smart Cities)
subtitle: Computer vision research focused on real-world applications such as detecting cracks and scratches to prevent further damage.

# Summary for listings and search engines
summary: Computer vision research focused on real-world applications such as detecting cracks and scratches to prevent further damage.
# Link this post with a project
projects: []

# Date published
date: '2023-05-04T00:00:00Z'

# Date updated
lastmod: '2023-11-01T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 
  focal_point: ''
  placement: 
  preview_only: false

authors:
  - admin

tags:
  - VIP Team

categories:
  - Computer Vision
---

## Project Description

VIP Data Science for Smart Cities

- The Data Science for Smart Cities project aims to conduct interdisciplinary research to develop data analytics tools using robotics and autonomous sensing for condition assessment of urban systems.

## Motivations

**Detecting Cracks and Scratches**

    - Keep public safety
    - Prevent further damages

**Approach**
    - Using 3D program (Houdini) to create a dataset.
    - Using semantic segmentation network to detect cracks and scratches.

**Why 3D Program**
    - Can generate a large amount of data easily. 
    - Problem: Cracks and scratches could look similar from certain angles. 
        - Can be distinguished by changing viewpoints.


## Contribution

1. Generated 56 datasets, each with 308 images, of cracks and scratches using Houdini. 
    - Applied skeletonization to the binary crack images.
    - Manually drew realistic scratches.
    - Generated a 3D wall with cracks and scratches.
    - Rendering the 3D scene and captured 308 images using camera movement.
  
2. Implemented a semantic segmentation neural network to detect cracks and scratches
    - 


