---
layout: page
title: Machine Learning for Blast Performance Analysis in Mining
description: Automated Blast Rating from Drone Footage
img: assets/img/BlastingLogo.png
importance: 1
category: Team
related_publications: false
---


This team project leverages computer vision and machine learning to analyze blast performance from drone footage, providing key insights to optimize efficiency and safety. By automating smoke plume segmentation and analysis, the system enables data-driven assessment of blast quality, enhancing decision-making in mining operations.

### Team Contributions

Shuai Liu – Responsible for both front-end and back-end development.

Agustin Marks – Data labeling and project management.

Daniel Wright – Contributing mining domain expertise and data labeling.


### Multi-stage approach

**Stage 1 Image Registration**

- Aligns design maps with drone footage using feature matching and homography transformation.

**Stage 2  Smoke Plume Segmentation**

- Uses deep learning (Mask R-CNN) to detect and quantify smoke plumes, extracting key metrics like area, expansion rate, and dimensions.

**Stage 3 Blast Performance Prediction**

- Applies decision trees to predict blast quality based on extracted features.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/multi-stage.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### App Showcase

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/blasting_app.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


