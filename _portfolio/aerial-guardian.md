---
title: "Aerial Guardian: Drone-based Multi-Object Person Tracking"
excerpt: "A real-time aerial detection and tracking pipeline using VisDrone, YOLO26n, ByteTrack, and BoT-SORT."
collection: portfolio
---

Developed an aerial person detection and multi-object tracking pipeline using the VisDrone MOT dataset. The project focused on the difficulty of detecting small people from aerial imagery and maintaining identities across frames when the camera itself is moving.

<ul class="tag-list">
  <li>Computer Vision</li>
  <li>Object Tracking</li>
  <li>YOLO</li>
  <li>ByteTrack</li>
</ul>

* Fine-tuned YOLO26n for small-object aerial detection.
* Integrated ByteTrack and BoT-SORT with Global Motion Compensation.
* Achieved 40+ FPS on a Tesla P100 GPU and improved tracking performance from 24.2% to 28.3% MOTA and 38.8% IDF1.
* Compared detector and tracker behavior across challenging motion, scale, and occlusion conditions.
* Built the pipeline as a practical computer vision system rather than only a model-training exercise.
