---
layout: page
title: Multi-CCTV 3D Worker Localization & UAV Reconstruction
description: Drone-anchored, VGGT-based 3D mapping fused with multi-camera detection for real-time worker safety monitoring.
img: assets/img/12.jpg # TODO: replace with a real figure from your work
importance: 1
category: work
related_publications: true
---

A pipeline for locating workers and equipment in 3D across a construction site from multiple fixed CCTV feeds, anchored by UAV-based scene reconstruction.

Core components: VGGT metric-depth reconstruction, COLMAP re-localization, YOLO detection, 3D back-projection, and Kalman / Mahalanobis-gated tracking. On the preliminary-defense evaluation, tracking quality improved substantially across stages (IDF1 0.27 → 0.50 → 0.77, against an Oracle of 0.82).

<!-- TODO: add 2–3 figures via {% include figure.liquid path="assets/img/your_figure.png" %} and a short results paragraph. -->
