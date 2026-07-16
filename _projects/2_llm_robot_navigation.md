---
layout: page
title: LLM-Guided Robot Navigation & Semantic Risk Mapping
description: A Clearpath Husky autonomously explores a Gazebo digital twin, reasons about site risks with an LLM, and builds a 3D risk map.
img: assets/img/7.jpg
importance: 2
category: work
related_publications: true
---

An autonomous mobile robot (AMR) navigation system built on the ROS 2 Nav2 stack, validated in a Gazebo digital twin of a real construction site.

The system compares four strategies — Nav2-only, manual keep-out costmaps, a rule-based scene graph, and LLM-based reasoning — where the LLM approach reaches the safest behavior (zero risk-zone intrusions at full task success). Ongoing work extends this toward autonomous risk-zone exploration and semantic 3D risk mapping using crack-texture detection (YOLO / Qwen2.5-VL).
