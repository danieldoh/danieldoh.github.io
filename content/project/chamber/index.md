---
title: Animal behavior Analysis in an Aerosol Exposure Chamber 
summary: Analyzed and visualized data on lizard behavior in an aerosol exposure chamber.
tags:
  - Computer Vision
  - Artificial Intelligence
  - Data Management
  - Research
date: "2024-04-05T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""
image:
  caption: 
  focal_point: 
---
# Animal Behavior Analysis in an Aerosol Exposure Chamber

[Source Code](https://github.com/danieldoh/lizard_behavior_analysis)

[Lizard Experiment Tutorial(Google Slides)](https://docs.google.com/presentation/d/1wFzATak-2whAXQeKLtLqoFcYjUzspXlpnnTqukoNyHw/edit?usp=sharing)

# Project Description
- Motivation: Investigate whether aerosol exposure affects animal's behavior and walking patterns.
- Analyzed the behavior of two lizards in different conditions:
  - One in a non-aerosol exposure chamber.
  - One in an aerosol exposure chamber.

# Contribution
**Tracking**
- Methodology: Tracked lizards using a deep learning network trained with a self-labeled dataset.
  - Model: YOLOv8
  - Dataset: Generated 1,701 labeled images from recorded videos, manually labeling each lizard joint.
![screen reader text](lizard_track.jpg "Figure 1: Lizards (Yellow and Black Dot) Tracking")
![screen reader text](lizard_track_2.jpg "Figure 2: Black Dot Lizard Tracking in a Non-aerosol Exposure Chamber")


**Analysis**
- Indices: Analyzed lizard behavior using 4 indices:
  - Stride Speed
  - Movement
  - Speed
  - Leg Angle
- Visualization: Presented the analyzed data using Python.

![screen reader text](lizard_stride.jpg "Figure 3: Analysis of Lizard Stride Speed ")
![screen reader text](lizard_position.jpg "Figure 4: Analysis of Lizard Movement")
![screen reader text](lizard_speed.jpg "Figure 5: Analysis of Lizard Speed")
![screen reader text](lizard_angle.jpg "Figure 6: Analysis of Lizard Leg Angle")


**Skills**
- Python: Analysis, Visualization, Deep Learning Training and Inference
- PyTorch: Deep Learning Training and Inference
- OpenCV: Video Streaming, Frame Extraction
  


