# BBL 514E Spring 2025 project
Prepared By:
**Ahmet Ajam - 518231020**

---
# Detector-Free Feature Matching for Visual SLAM
**Evaluation of LoFTR and ELFOTR on Challenging Scenes**

This repository contains the code and results for the BBL 514E Spring 2025 project at Istanbul Technical University. The project benchmarks state-of-the-art detector-free feature matching models — **LoFTR** and **ELFOTR** — on visual SLAM-relevant datasets, focusing on their performance in terms of homography estimation and matching reliability.



---

## 📌 Project Summary

Visual SLAM (Simultaneous Localization and Mapping) requires robust feature matching to estimate camera motion and reconstruct 3D scenes. Traditional feature detectors like ORB and SIFT struggle in low-texture or dynamic environments. In this project, we evaluate **transformer-based detector-free models** for feature matching:

- **LoFTR**: detector-free local feature matching without keypoint detection.
- **ELFOTR**: A lightweight, faster version of LoFTR with similar accuracy.

We benchmark their performance on the **MegaDepth1500** and **ScanNet1500** datasets and to assess suitability for SLAM pipelines.

---

## 🛠️ Reproduction Instructions

⚠️ **Note**: This project builds on the official implementations of [LoFTR](https://github.com/zju3dv/LoFTR) and [ELFOTR](https://github.com/SLDGroup/ELFOTR).  
To ensure accurate results and full functionality, please follow their setup instructions for model weights and basic test procedures.

---

