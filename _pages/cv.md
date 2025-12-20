---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

**Carnegie Mellon University**  
M.S. in Electrical and Computer Engineering  
Sep 2023 – May 2025  
GPA: 4.0/4.0  
Courses: Visual Learning and Recognition, Physics-Based Rendering, Robot Localization and Mapping, Geometry-based Methods in Vision

**Beijing Jiaotong University**  
B.E. in Software Engineering (Advisor: Prof. Ruipeng Gao)  
Sep 2019 – May 2023  
GPA: 3.9/4.0 (Top 3%)

## Research Experience

**Pathak Research Group / Prof. Deepak Pathak**  
Graduate Research Assistant  
Sep 2024 – Present

* **Scaling Masked Diffusion Models in Data Constraint Settings**
  * Developed a comparative study on Masked Diffusion Models and Autoregressive Models in data-constrained scenarios, which shows the effectiveness of MDMs in learning from limited data and mitigating overfitting.
  * Constructing a data-constrained scaling law for MDMs.
  * Published a co-first author paper to NeurIPS 2025

* **Interpretation of Deception in LLM Beyond Hallucination**
  * Explored the bottom-up formation and top-down control of deceptive responses in LLMs, which analyzed how deception emerges and propagates to the next prediction.
  * Responsible for conducting layer-to-neuron level experiments to analyze how lying intent and incorrect facts are encoded in MLP and propagate through Attention.
  * Co-authored a paper currently under submission

**Robotic Caregiving and Human Interaction Lab / Prof. Zackory Erickson**  
Graduate Research Assistant  
Apr 2025 - July 2025

* **Robot Shared Autonomy with Real-world Incremental Learning**
  * Leveraged 3D diffusion models for shared autonomy in data-constrained real-world manipulation, using few RGB-D expert demonstrations complemented by a synthetic data generation pipeline.
  * Enabled continual user-specific improvement via incremental adaptation from in-the-loop corrections.

**Biorobotics Lab / Prof. Howie Choset**  
Graduate Research Assistant  
Jul 2023 - Dec 2024

* **Robot-agnostic Representation Learning**
  * Developed a unified latent shape space for robots that alleviates the data bottleneck and enables cross-robot knowledge by aligning kinematic configurations using geometric-based soft contrastive loss.
  * Exploring the integration of the unified latent space with pre-trained vision-language action models to enhance their robustness and generalizability.

* **ARPA-E REPAIR Mapping**
  * Developed a pipeline of robotic system for in-pipe inspection that leveraging confined space VILL-SLAM and geometry-based pipe defect detection and reconstruction. Responsible for algorithm and software design.
  * Responsible for developing a UE-based simulation environment for robotic sensing.
  * This project has been transited into the startup company Pipe Force.

**Prof. Ruipeng Gao**  
Undergraduate Research Assistant  
Feb 2022 - Mar 2023

* **Vehicle Off-route Detection via Multi-sensor Fusion**
  * Developed a multisensor fusion framework based on Particle Filter for real-time vehicle tracking and off-route prediction. Responsible for data fusion and processing, and model pruning for mobile deployment.
  * Published a paper in the Journal of IEEE Transactions on Intelligent Vehicles.

* **Smartphone-based Multi-level Indoor Floor Construction**
  * Developed a smartphone-based indoor floor plan construction system using acoustic ranging and inertial tracking. Responsible for processing IMU data and implementing the inertial sensing module.
  * Published a paper in WASA 2022

## Publications

**Diffusion Beats Autoregressive in Data-Constrained Settings**  
Mihir Prabhudesai*, Mengning Wu*, Amir Zadeh, Katerina Fragkiadaki, Deepak Pathak  
NeurIPS 2025 (accepted)

**Can LLMs Lie? Investigation beyond Hallucination**  
Haoran Huan*, Mihir Prabhudesai*, Mengning Wu*, Shantanu Jaiswal, Deepak Pathak  
arXiv preprint, 2025

**No Longer Getting Lost on Fork Road: Vehicle Off-Route Detection Via Multi-Sensor Integration**  
Xuan Xiao, Weiwei Xing, Ruipeng Gao, Mengning Wu  
IEEE Transactions on Intelligent Vehicles, 2024

**Smartphone-Based Multi-level Indoor Floor Plan Construction via Acoustic Ranging and Inertial Sensing**  
Chuize Meng, Shan Jiang, Mengning Wu, Xuan Xiao, Dan Tao, Ruipeng Gao  
International Conference on Wireless Algorithms, Systems, and Applications (WASA) 2022

## Projects

**Learning the Relationships Between Motions**  
Oct 2024 - Dec 2024  
Course Project
* Developed a VAE-based framework to encode and reconstruct human motions, enabling motion composition and similarity analysis, demonstrating the effectiveness of latent representations in capturing semantic info.

**Elevating Dense SLAM with 3D Gaussian Splatting**  
Feb 2024 - Apr 2024  
Course Project
* Developed a SLAM framework integrating 3DGS and leveraging a submap strategy to enhance scalability and real-time performance. Achieved an improved tracking speed (10X) while maintaining comparable reconstruction quality.

**3D Reconstruction System Based on End-Cloud Integration**  
Jan 2023 - Apr 2023  
Undergraduate Thesis
* Developed a generalized 3D reconstruction system that allows users to collect images and view 3D models using mobile devices. This system used COLMAP and Instant-NGP to create dense reconstruction.

## Honors & Awards

* First-class academic award, 2022
* Interdisciplinary Contest in Modeling Certificate of Achievement - Honorable Mention, Jun 2021
* The 45th ICPC Asia Regional Contest Jinan Site 2020-Bronze Medal, Dec 2020
* Second-class academic award, 2020, 2021

## Skills

**Programming:** Python, C/C++, Java

**Technologies:** PyTorch, verl, diffusers, Megatron & Deepspeed, ROS, MuJoCo, PyBullet, Open3D
