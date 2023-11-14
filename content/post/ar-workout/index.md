---
title: 'Paper Review: AR-Enhanced Workouts: Exploring Visual Cues for At-Home Workout Videos in AR Environment' 
subtitle: ''

# Summary for listings and search engines
summary: 'UIST 2023'

# Link this post with a project
projects: []

# Date published
date: '2023-05-10T00:00:00Z'

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
  - Undergraduate Research

categories:
  - Augmented Reality

---
[DOI](https://dl.acm.org/doi/10.1145/3586183.3606796)
## Problem 
- Hard to quickly learn the correct movements from the 2D video
- Failed to provide effective feedback

## Solution
**AR:**
  - Workout video centered in the user’s field of view
  - Real-time visual feedback

**Additional Camera:**
  - For the full-body status of the users
  - Give feedback to adjust users’ movements in real-time

## Design Space
**Data:**
  - Motion-data:
    - The movements that users need to pay attention
    - Movement direction & sequence
  - Non-motion data:
    - Goals that users only need to aim to achieve
    - Body skeleton (give feedback using joints)
    - Visual metaphors 
      - Chair (where to squat)
      - Cone (height)

**Task:** 
  - Identification:
    - Key movement information -> better understanding
  - Comparison:
    - Apply superposition
    - Overlaying users’ exercise performance onto standard visual cues

**Situation:**
  - Address frequent viewpoint shifts
    - Floating screen (out of sight)
    - On-ground (within sight)
