---
title: Onboard Visual Drone Detection for Drone Chasing and Collision Avoidance
year: 2020
excerpt: We proposed a method for real-time detection of flying drones and UAVs that could be run with a limited computing device like an onboard computer for a drone. This method is approached from a machine learning perspective resulting in an object detection model to detect and localize multiple drones in a given image.
pub-image: https://publishing.aip.org/wp-content/uploads/2022/10/AIPP-Master-Logo-Dark-RGB-300x106.png
pub-url: https://doi.org/10.1063/5.0059987
comments: false
---

We proposed a method for real-time detection of flying drones and UAVs that could be run with a limited computing device like an onboard computer for a drone. This method is approached from a machine learning perspective resulting in an object detection model to detect and localize multiple drones in a given image. The constraint is that the model will have to be lightweight and performant while still maintaining good accuracy. This leads us to choose SSD Mobilenet V2 model architecture to train and test how effective it is for detecting drones. Our method gained an average precision and recall of 0.586 and 0.622 (IoU 0.50 - 0.95, all area) respectively.