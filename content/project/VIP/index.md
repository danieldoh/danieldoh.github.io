---
title: Vertically Integrated Projects (Data Sciences for Smart Cities)
summary: Computer vision research focused on real-world applications such as detecting cracks and scratches to prevent further damage.
tags:
  - Research
  - Computer Vision
  - Data Management
  - Artificial Intelligence
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
# VIP Data Science for Smart Cities

- Advisor: [Professor Jahanshahi](https://engineering.purdue.edu/CE/People/view_person?resource_id=113437)
- The Data Science for Smart Cities project aims to conduct interdisciplinary research to develop data analytics tools using robotics and autonomous sensing for condition assessment of urban systems.

# Research Motivation and Approach

![screen reader text](vip_motivation.jpg "Figure 1: Crack on the wall")
**Detecting Cracks and Scratches**
  - Ensure public safety.
  - Prevent further damages.

**Approach**
  - Use a 3D program (Houdini) to create a dataset.
  - Apply a semantic segmentation network to detect cracks and scratches.

**Why 3D Program**
  - Can generate a large amount of data easily. 
  - Problem: Cracks and scratches may **look similar** from certain angles due to lighting.
    - Can be distinguished with **different viewpoints**.


# Contribution

1. Generated 56 **datasets**, each with 308 images, of cracks and scratches using Houdini. 
    - Applied skeletonization to the binary crack images.
    ![screen reader text](vip_skeleton.jpg "Figure 2: Skeletonization")
    - Manually drew realistic scratches.
    - Generated a 3D wall with cracks and scratches.
    - Rendering the 3D scene and captured 308 images using camera movement.
  
2. Implemented a **semantic segmentation neural network** to detect cracks and scratches.
    - Extracted the **crack mask** and **scratch mask**.
    - **Multiclass Semantic Segmentation** Network.
      - Labeled each dataset
        - 0: Background
        - 1: Crack
        - 2: Scratch
    - **Training**
      - Model: U-Net (Transfer Learning)
      - Loss Function: Cross Entropy Loss
      - Optimizer: Adam
      - Learning Rate: 0.0001
      - Epochs: 20
    - **Evaluation**
      - **Uncertainty Quantification**
    ![screen reader text](vip_uncertainty.jpg "Figure 3: Evaluation")
    ![screen reader text](vip_uncertain2.jpg "Figure 4: Uncertainty")

      
