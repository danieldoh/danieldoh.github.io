---
title: 'Paper Review: Visual Captions: Augmenting Verbal Communication with On-the-fly Visuals' 
subtitle: ''

# Summary for listings and search engines
summary: 'CHI 2023'

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
[DOI](https://dl.acm.org/doi/10.1145/3544548.3581566)
## Problem 
- Input: continuous stream of conversation
- During the conversation, limited cognitive resources to interact with AI prompts
- Without a real-time system deployed, it is difficult to study how people could interact with and benefit from visuals


## Solution
**synchronous human-human verbal communication**
- Automatically predicts the “visual intent” of a conversation
- The visuals that people would like to show at the moment of their conversation
- Suggests them for users to immediately select and display


## Design Space
**Temporal:**
- Synchronous
  - Users select 
- Asynchronous
  - Set up corresponding visuals before
  - Select and edit visuals after the text is composed


**Subject:** 
- By the speaker to express their ideas (visualize their own speech)
- By the listener to understand others (visualize others’ speech)
- Support both subjects and allow all parties to visually supplement their own speech and ideas

    
**Visual:**
- Visual Content - what information to be visualized? 
  - Disambiguate the most critical and relevant information to visualize in the current context
- Visual Type - how should the visual be presented?
  - Ranging from abstract to concrete
- Visual Source - where the visual should be retrieved from?
  - From personal and public assets


**Scale & Space:**
- One-to-one
- One-to-many
- Many-to-many

**Privacy**
- Privately shown visuals are only presented to the speaker
- Publicly shown visuals are presented to everyone in the conversation
- The visuals can be selectively presented to a subset of audiences.


**Initiation**
- Proactively providing visual augmentations without user interaction
  - On-demand-suggest
  - Auto-suggest
  - Auto-display


**Interaction**
- Speech
- Gesture
- Body pose
- Facial expression
- Gaze
- Custom input devices

