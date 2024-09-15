
# TDM-SLAM: A Two-Stage Dynamic SLAM with Improved Motion Region Segmentation

## Video Demos

https://github.com/qinliangql/TDM-SLAM/assets/94153596/b6418d82-481b-4d51-b2df-b2bd8194d253


https://github.com/qinliangql/TDM-SLAM/assets/94153596/7d66c29a-9d1e-4c15-8a76-cd7b46684d1d

## Overview

This repository provides supplementary materials showcasing real-world experiments as outlined in Section 4.4 of the Main Text. The demonstration videos, captured using handheld smartphones, highlight the capabilities of TDM-SLAM in challenging environments.

## Explanation

### Demo Details

**Demo 1**:  
Recorded in an indoor setting—a long corridor with varying lighting and dynamic pedestrians.

**Demo 2**:  
Captured on an outdoor road, featuring complex dynamic scenes with moving vehicles and pedestrians.

### Video Analysis

![Demo Video Screenshot](images/show.png)

- **Input Frames vs. Dynamic Remove**:  
  The upper part of the demo videos compares key frames ("Input Frames") with frames after dynamic region removal ("Dynamic Remove"). Dynamic regions are identified using TDM-SLAM's motion segmentation, enhancing scene clarity.

- **Initial Points 3D and Scene Reconstruction**:  
  The lower section showcases 3D point cloud maps ("Initial Points 3D") and their rendering into a final 3D Gaussian scene model ("Scene Reconstruction"), visualized using the SIBR viewer.

- **Localization**:  
  On the right side, "Localization" demonstrates TDM-SLAM's real-time camera pose estimation and map point construction, emphasizing accuracy and robustness in dynamic environments.

Throughout the demonstrations, key moments are highlighted with informative prompts, providing insights into TDM-SLAM's operation and performance.

