---
layout: post
title:  "Video Stablization with CUDA Implementation"
date:   2017-6-10 13:46:52
comments: true
image: /images/gpu_final.jpg
categories: computer vision, cuda, video stablization
---

# Abstract

A video captured with a hand-held device (e.g., a cell-phone or a portable camcorder) often appears remarkably shaky and undi-rected. Digital videostabilization improves the video quality by re-moving unwanted camera motion. We implement a video stabilization method [Liu et al. 2013] which models cam-era motion with a bundle of (multiple) camera paths. The model is based on a mesh-based, spatially-variant motion representation and an adaptive, space-time path optimization. Also, the motion representation allows users to fundamentally handle parallax and rolling shutter effects while it does not require long feature trajectories or sparse 3D reconstruction. Furthermore, we speed up this method by parallelizing some parts with CUDA support. Check this [webpage](https://naughtychen.cc/GPU_Final/) for more details.

# Features
- Bundled Video Stablizatioon
- CUDA support
- OpenCL