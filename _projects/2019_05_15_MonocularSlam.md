---
title: "Estimating 3D trajectory using feature-based sparse SLAM"
collection: research
custom: 'true'
custom_remark: "A class project for CS 763 (Computer Vision), Spring '19, IIT Bombay"
permalink: /projects/MonocularSlam
excerpt: "The presented algorithm revolves around feature-based sparse SLAM, called MonoSLAM, for recovering a camera's 3D trajectory. Key steps include feature extraction, distance-based feature matching, essential matrix estimation, pose estimation, world coordinate computation, and visualization. Code link [here](https://github.com/neeleshverma/Monocular-slam)"
date: 2019-05-15
venue: 'NA'
---

<style>

/* Style the counter cards */
.card {
<!--   box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* this adds the "card" effect */ -->
  padding: 16px;
<!--   text-align: center; -->
<!--   background-color: #f1f1f1; -->
}

a:link {
  text-decoration: none;
}
</style>

In this project, we implement an algorithm to recover the 3D trajectory of a camera through feature-based sparse SLAM (Simultaneous Localization and Mapping) using a single camera, also known as MonoSLAM. The keypoints are extracted using ORB. Subsequently, feature matching involves calculating the distances between all point pairs through a brute-force approach, followed by the estimation of 2 nearest neighbors using knn clustering and the elimination of points/pairs through a ratio test. Essential matrix estimation is then carried out using the 8-point algorithm, converting image coordinates to camera coordinates, and employing thresholding and RANSAC to eliminate outliers. The subsequent steps involve pose estimation, where the pose of the current frame is estimated using the essential matrix, and world coordinate computation, achieved by triangulation using two projection matrices as input.  

Code [here](https://github.com/neeleshverma/Monocular-slam)