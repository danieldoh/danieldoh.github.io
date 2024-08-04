---
title: Plant Growth Analysis in an Aerosol Exposure Chamber 
summary: Analyzed and visualized data on plant growth in an aerosol exposure chamber.
tags:
  - Computer Vision
  - Artificial Intelligence
  - Data Management
  - Research
date: "2024-05-20T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""
image:
  caption: 
  focal_point: 
---
# Plant Growth in an Aerosol Exposure Chamber

[Source Code](https://github.com/danieldoh/plant_app)

[Plant Experiment Tutorial(Google Slides)](https://docs.google.com/presentation/d/1RLL0T2k3RYVzmFKLUulBE1aZwghCcP8Qk9Uw5Ux0VKQ/edit#slide=id.p)

[Plant-Analysis App](https://plant-analysis.streamlit.app/)

# Project Description
- Motivation: Investigate whether aerosol exposure affects plant's growth.
- Analyzed the growth of two plants(kidneys) in different conditions:
  - One in a non-aerosol exposure chamber.
  - One in an aerosol exposure chamber.

# Contribution
**Data Collection**
- Methodology: Collected frames from 24-hour recorded video using OpenCV.
  - Installation: 4 Cameras
    - 2 Cameras for Trunk
    - 2 Cameras for Leaf
![screen reader text](kidney_exposure.jpg "Figure 1: Kidney Trunk in an Aerosol Exposure Chamber")
![screen reader text](kidney_no.jpg "Figure 2: Kidney Trunk in a Non-Aerosol Exposure Chamber")
![screen reader text](leaf_exposure.jpg "Figure 3: Kidney Leaf in a Aerosol Exposure Chamber")
![screen reader text](leaf_no.jpg "Figure 4: Kidney Leaf in a Non-Aerosol Exposure Chamber")

**Analysis**
- Indices: Analyzed plant growth using 9 indices (4 indices for leaves, 5 indices for trunks):
  - Leaf: Width, Length, Tilt, Area
  - Trunk: Diameter, Height, Cumulative Height, Angle Tilted, Surface Area
- Tool: Streamlit-based web analysis software.
- Visualization: Presented the analyzed data with Google sheets.

![screen reader text](leaf_analysis.jpg "Figure 5: Analysis of Kidney Leaf ")
![screen reader text](trunk_analysis.jpg "Figure 6: Analysis of Kidney Trunk")
![screen reader text](plant_main_page.jpg "Figure 7: Main Page of Web Analysis Software")
![screen reader text](trunk_page.jpg "Figure 8: Trunk Analysis Page")
![screen reader text](leaf_page.jpg "Figure 9: Leaf Analysis Page")
![screen reader text](data_page.jpg "Figure 10: Database")


**Skills**
- Python: Analysis(Streamlit-based Web application), Video Streaming, Frame Extraction
- OpenCV: Video Streaming, Frame Extraction
- Google sheets: Database for Streamlit web application
  


