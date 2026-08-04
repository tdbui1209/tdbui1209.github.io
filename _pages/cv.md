---
layout: single
permalink: /cv/
title: Curriculum Vitae
author_profile: true
toc: true
toc_sticky: true
toc_label: "Contents"
toc_icon: "file-lines"
last_modified_at: 2026-08-05
---

[Download Resume (PDF)]({{ '/files/Computer-Vision-Engineer-Bui-Tung-Duong.pdf' | relative_url }}){: .btn .btn--primary}

## Professional Summary

Computer Vision and Software Engineer with **2+ years of full-time experience** and **one year of internship experience** in camera systems, computer vision, edge AI, and manufacturing software.

Experienced in RAW Bayer processing, ISP preprocessing, image validation, algorithm integration, failure analysis, and high-volume production-data automation.

Built and validated image-processing pipelines against customer-provided reference implementations with numerical deviation below \(10^{-9}\), while delivering automation solutions that reduced validation and analysis effort by up to **82%**.

Hands-on experience in AI model training, ONNX and TensorRT deployment, NVIDIA Jetson edge inference, camera calibration, geometric transformations, stereo vision, and real-time computer-vision systems.

## Core Skills

| Area | Technologies and experience |
|---|---|
| Programming | Python, C++, MATLAB |
| Computer vision and AI | OpenCV, PyTorch, TensorFlow, YOLO, InsightFace |
| Camera systems | RAW Bayer processing, ISP preprocessing, pinhole camera model, camera calibration, lens-distortion correction |
| Geometry and stereo vision | Coordinate transformations, homography, pose estimation, stereo calibration, rectification, disparity, depth reconstruction |
| Edge AI | NVIDIA Jetson Nano, ONNX, TensorRT, FP32, FP16, INT8 |
| Tools and systems | Git, PowerShell, manufacturing test systems |
| Engineering | Algorithm integration, numerical validation, image processing, failure analysis, root-cause analysis |
| English | TOEIC Speaking 140 |

## Work Experience

### LG Innotek Vietnam Haiphong

**Test Software Engineer**  
*January 2024 - Present · Haiphong, Vietnam*

- Developed and maintained production test software for main, ultra-wide, and telephoto smartphone camera modules using Python, C++, and MATLAB, supporting projects from NPI builds through PVT ramp.
- Processed RAW Bayer image data and integrated customer-defined image-processing and camera functional-test algorithms into high-volume manufacturing test flows.
- Reproduced and validated reference algorithms in production software, achieving numerical deviation below \(10^{-9}\) for verified outputs.
- Developed image-processing and automated validation tools that reduced initial failure-analysis reporting time by **80%**, validation cycle time by **60%**, and manual analysis effort by **82%**.
- Investigated image and test-result anomalies by analyzing software behavior, preprocessing parameters, configuration, equipment conditions, and camera-module characteristics.
- Communicated technical findings and root-cause conclusions with production, process, equipment, and customer teams, translating complex result differences into actionable corrective actions.

### Universal Scientific Industrial Vietnam

**SFIS Engineer Intern**  
*July 2023 - December 2023 · Haiphong, Vietnam*

- Supported SFIS operations and investigated production-data synchronization issues across interconnected manufacturing systems.
- Developed internal utilities to automate data processing and improve system-to-system data flow.
- Automated SCP-based data synchronization during off-peak periods, replacing manual synchronization and reducing production waiting time.
- Worked with manufacturing databases, system logs, and shop-floor applications to support production workflows and system integration.

### VNNet Haiphong

**Software Engineer Intern**  
*January 2023 - June 2023 · Haiphong, Vietnam*

- Collected and prepared image data, trained a YOLOv5 fire-and-smoke detection model, converted it from PyTorch `.pt` to ONNX and TensorRT, and benchmarked FP32, FP16, and INT8 inference on NVIDIA Jetson Nano based on latency, throughput, and mAP.
- Integrated automatic fire alerts through phone notifications and on-site alarm systems; the solution was accepted for deployment at a packaging manufacturing company in Hung Yen.
- Developed a configurable face-recognition attendance application using Hanet AI-camera APIs for identity recognition, event handling, and attendance recording.

## Selected Projects

### Camera Geometry Toolkit

[View source code](https://github.com/tdbui1209/camera-geometry-toolkit){: .btn .btn--info}

*July 2026 - August 2026*

A reproducible computer-vision toolkit covering pinhole-camera geometry, monocular calibration, stereo vision, and geometric transformations.

- Implemented pinhole-camera projection, coordinate transformations, monocular calibration, lens-distortion correction, planar homography, and ArUco-based pose estimation.
- Built a stereo-vision pipeline covering stereo calibration, image rectification, disparity estimation, and depth reconstruction.
- Structured the Python implementation as reusable modules with runnable demos and validation scripts.
- Developed OpenCV demos for environment verification and 3D-to-2D projection.

### Open-Set Face Recognition

[View source code](https://github.com/tdbui1209/Face-Recognition-With-InsightFace){: .btn .btn--info}

*December 2021 - January 2022*

An open-set face-identification application built with InsightFace.

- Built a face-identification pipeline covering face detection, alignment, 512-dimensional embedding extraction, gallery enrollment, and cosine-similarity matching.
- Implemented similarity-threshold rejection to classify identities outside the enrolled gallery as unknown.
- Organized the application into reusable enrollment and inference workflows for adding and recognizing identities.

### Global Wheat Detection

[View project](https://tdbui1209.github.io/portfolio/projects/kaggle-global-wheat-detection.html){: .btn .btn--info}

*July 2023*

An object-detection project for identifying wheat heads in outdoor agricultural images.

- Trained and evaluated an object-detection model for detecting wheat heads in outdoor agricultural images.
- Implemented dataset preprocessing, augmentation, training, inference, and prediction visualization.
- Analyzed false positives, missed detections, object-scale variation, and image-domain differences across datasets.

[View more projects]({{ '/portfolio/' | relative_url }}){: .btn .btn--primary}

## Awards

### LG Innotek Improvement Excellence Award 2026

*March 2026*

- Developed a direct software interface between the production test system and automated visual-inspection equipment.
- Accelerated inspection feedback and reduced the risk of defective units escaping downstream detection.
- Delivered estimated annual cost savings of approximately **KRW 600 million**.

### Data-Centric AI Competition 2021 — Prospective Prize

*FPT Software · December 2021*

- Developed a face-mask wearing-condition detection pipeline for the COVID-19 context.
- Improved data quality through augmentation, incorrect-label correction, bounding-box refinement, synthetic data generation, and model-assisted data collection.
- Increased model performance from **0.64 to 0.91 mAP@0.5:0.95**.
- Ranked **2nd in the student leaderboard** and **11th overall**.

## Education

### Vietnam Maritime University

**Bachelor of Information Technology**  
*October 2020 - April 2024*

- GPA: **3.61/4.00**

## Contact

- Email: [tdbui1209@gmail.com](mailto:tdbui1209@gmail.com)
- GitHub: [github.com/tdbui1209](https://github.com/tdbui1209)
- LinkedIn: [linkedin.com/in/tung-duong-bui-306427201](https://www.linkedin.com/in/tung-duong-bui-306427201)
- Location: Haiphong, Vietnam