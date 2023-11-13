---
title: Vertically Integrated Projects (VIP Smart Cities)
summary: Computer vision research focused on real-world applications such as detecting cracks and scratches to prevent further damage.
tags:
  - Computer Vision
date: '2023-05-04T00:00:00Z'

external_link: ''

image:
  caption: 
  focal_point: 

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---
## VIP Data Science for Smart Cities

- The Data Science for Smart Cities project aims to conduct interdisciplinary research to develop data analytics tools using robotics and autonomous sensing for condition assessment of urban systems.

## Research Motivation and Approach

**Detecting Cracks and Scratches**
  - Ensure public safety.
  - Prevent further damages.

**Approach**
  - Use a 3D program (Houdini) to create a dataset.
  - Apply a semantic segmentation network to detect cracks and scratches.

**Why 3D Program**
  - Can generate a large amount of data easily. 
  - Problem: Cracks and scratches may look similar from certain angles due to lighting.
    - Can be distinguished by changing viewpoints.


## Contribution

1. Generated 56 datasets, each with 308 images, of cracks and scratches using Houdini. 
    - Applied skeletonization to the binary crack images.
    - Manually drew realistic scratches.
    - Generated a 3D wall with cracks and scratches.
    - Rendering the 3D scene and captured 308 images using camera movement.
  
2. Implemented a semantic segmentation neural network to detect cracks and scratches.
    - Extract the **crack mask** and **scratch mask**.
    - Multiclass Semantic Segmentation Network.
    - Label each dataset
      - 0: Background
      - 1: Crack
      - 2: Scratch
    - Training
      - Model: U-Net (Transfer Learning)
      - Loss Function: Cross Entropy Loss
      - Optimizer: Adam
      - Learning Rate: 0.0001
      - Epochs: 20
    - Evaluation
      - Uncertainty Quantification