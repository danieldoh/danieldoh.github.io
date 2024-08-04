---
title: Summer Undergraduate Research Fellowship (SURF)
summary: Conducted individual research by implementing an animation generation pipeline. 
tags:
  - Research
  - Artificial Intelligence
date: "2023-08-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""
image:
  caption: "SURF Symposium Poster"
  focal_point: 
---
# Animation from Text and Pose

**Research Problem**
- Animation is hard and only a select few can create animations today.

**Motivation**
- Our goal is to enable those without professional software expertise to create animations.

**Approach**
- Our pipeline generates animations from text and human poses by employing two key components:
  1. Motion-Diffusion-Model (MDM): generating human skeleton sequences based on text.
  2. Follow Your Pose: Pose-Guided Text-to-Video model.

**Applications**
- Animation

# Methodology

![screen reader text](surf_pipeline.jpg "Figure 1: Pipeline of Animation from Text and Pose")

**MDM**
- Input text: human action text (e.g., "a person walks forward and stops")

**Pose-Guided Text-to-Video**
- Generate the video based on reality video.
- Input text: Appearance and Background (e.g., "Iron man on the beach")

**Path Drawing Tools**
- Enable user interaction through mouse movement.
- Implemented with OpenCV.

# Results
![screen reader text](surf_1.jpg "Figure 2: Characters and Background Variation")
![screen reader text](surf_2.jpg "Figure 3: Captain America kicks with his right leg in the snow")
![screen reader text](surf_path.jpg "Figure 4: An astronaut is dancing on the moon & Path drawing tool")

# Conclusion
- Generated video showed strong alignment with provided prompts and pose
- Interaction with the users by providing path drawing tools

# Future Works
- Need to implement MDM for generating **sequence of multiple human action** within a single video.
- More **complex human action** need to be generated.
- **Smoothness of the background** should be improved.




