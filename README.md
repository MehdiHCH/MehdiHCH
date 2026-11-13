<h1 align="center">EL MEHDI Hicham</h1>
<h3 align="center">Computer Vision Engineer · AI & Computer Vision R&D</h3>
<p align="center">
  Turning football video into tracking data, spatial understanding, and actionable analysis.
</p>

<p align="center">
  <a href="https://mehdihch.github.io/Portfolio/"><img src="https://img.shields.io/badge/Portfolio-Explore_my_work-0891B2?style=for-the-badge" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/elmehdihicham/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="mailto:mehdihicham736@gmail.com"><img src="https://img.shields.io/badge/Email-Let's_talk-334155?style=for-the-badge" alt="Email" /></a>
</p>

<p align="center">
  Based in Morocco 🇲🇦 · Computer Vision Engineer at <b>Harmony Technology</b><br />
  Open to technical collaborations, applied research, and knowledge sharing
</p>

---

## About me

I'm a Computer Vision Engineer with a Master's degree in **Artificial Intelligence and Virtual Reality** from **Ibn Tofail University, Kénitra**.

My work connects deep learning with geometry: detecting players and balls, maintaining identities through occlusion, calibrating cameras, projecting movement onto the pitch, and extracting information from video. I also work on the engineering that makes these pipelines practical: GPU inference, temporal consistency, model conversion, and performance evaluation.

Alongside my professional work, I develop **TactiVision**, an independent football video analytics R&D project.

## What I work on

| Area | Focus |
| --- | --- |
| **Detection & segmentation** | Players, balls, referees, goals, pitch regions, and field keypoints |
| **Tracking & identity** | Multi-object tracking, player ReID, team assignment, and jersey OCR |
| **Geometric vision** | Camera calibration, homography, pitch projection, and 2D/3D spatial analysis |
| **Video understanding** | Possession, passes, shots, interceptions, goals, and temporal smoothing |
| **Inference & deployment** | TensorRT, ONNX, FP16, CUDA streams, batching, and pipeline profiling |
| **Analytics outputs** | Annotated video, trajectories, heatmaps, pass maps, JSON timelines, and CSV statistics |

## Career

### Harmony Technology · Computer Vision Engineer
**October 2026 – Present · Morocco**

Working on computer vision for **3D football officiating and spatial analysis**, with a focus on player and ball tracking, camera calibration, geometric understanding, and pipeline reliability.

### Priori Sports · Computer Vision Engineer — Contract
**2026 · United States · Remote**

Contributed to football spatial tracking and **ball-height estimation** using camera calibration and geometric reconstruction. Work included linking image observations to spatial coordinates and refining trajectories over time.

### SPORTSCORE · R&D Intern — Computer Vision & AI
**April – October 2025 · France · Remote**

Developed components of an automated futsal video analysis pipeline, from detection and tracking to event analysis and reporting.

- Fine-tuned ball detection and worked on goal confirmation.
- Integrated player tracking, team colors, jersey OCR, pose estimation, and pitch projection.
- Built action analysis for passes, shots, dribbles, interceptions, and goals.
- Optimized inference with CUDA streams, batching, caching, and TensorRT FP16.
- Mentored a small team of interns and delivered annotated videos and structured analytics.

### Ibn Tofail University · SETIME Laboratory
**October 2024 – January 2025 · Kénitra, Morocco**

Built an end-to-end video event spotting workflow with **RegNet-Y, Gate Shift Modules, and Bi-GRU**, covering video extraction, annotation, training, and evaluation.

### Orange Business · CDN Security Engineering Internship
**September – November 2023 · Sala Al Jadida, Morocco**

Worked on secure content delivery, token-based URL generation, shell scripting, and CDN access controls.

## Selected results

| Work | Reported result | Context |
| --- | --- | --- |
| **Futsal frame classification** | **99.95% accuracy** | Main-view vs. other-view classification; approximately 33% of frames filtered |
| **Pipeline parallelization** | **22m57s → 12m12s** | Same 1m14s test video; approximately 46.8% less processing time |
| **Futsal ball detection** | **90.1% precision · 83.4% recall · 83.4% mAP50** | Fine-tuned detector evaluation |
| **Video event spotting** | **0.93 recall** | DRIVE class in the university research project |

<sub>Results are specific to their evaluation datasets, hardware, and pipeline configurations. They are not general benchmarks or end-to-end accuracy claims.</sub>

## Tools & software

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/Ultralytics_YOLO-111827?style=flat-square" alt="Ultralytics YOLO" />
  <img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="TensorRT" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX" />
</p>

| Category | Tools & methods |
| --- | --- |
| **Core development** | Python, NumPy, OpenCV, Git, Linux, Windows, Shell |
| **Deep learning** | PyTorch, Ultralytics YOLO — including YOLO11 and YOLO26, TensorFlow/Keras, scikit-learn |
| **Tracking & ReID** | ByteTrack, OC-SORT, DeepSORT, OSNet / Torchreid |
| **OCR & annotation** | PaddleOCR, EasyOCR, CVAT |
| **Calibration & geometry** | Field keypoints, RANSAC, homography, camera models, reprojection checks, temporal smoothing |
| **GPU inference** | TensorRT, ONNX Runtime, CUDA streams, FP16, batching, caching |
| **Applications & deployment** | Docker, FastAPI, AWS |
| **Other project experience** | ROS2, Gazebo, reinforcement learning, CRNN-based OCR |

## TactiVision · Independent R&D

**Football video → detections → identities & pitch coordinates → game state → events & analytics**

I use TactiVision to explore how computer vision can support football analysis across tactical and broadcast footage.

- **Perception:** player, ball, referee, goalkeeper, and pitch keypoint detection.
- **Identity:** team assignment, ReID, jersey OCR, and recovery after occlusion.
- **Geometry:** camera calibration, homography stabilization, and pitch projection.
- **Game understanding:** possession, action detection, trajectories, and tactical visualizations.
- **Engineering:** multiple TensorRT models, GPU parallelism, and structured outputs.

**Current research priorities:** stable identities after players leave and re-enter the frame, calibration during camera motion, ball tracking, and longer-sequence reliability. I am also exploring VLM-assisted identity recovery.

<sub>TactiVision is under active development and validation. Demonstrated match sequences do not imply validated performance across complete 90-minute matches.</sub>

[Explore my portfolio](https://mehdihch.github.io/Portfolio/) · [Follow my research updates](https://www.linkedin.com/in/elmehdihicham/)

## Other projects

| Project | Technical focus |
| --- | --- |
| **Tifinagh OCR** | Handwritten Amazigh character recognition, CRNN, and OCR workflows |
| **Autonomous navigation** | Reinforcement learning with TD3 and ROS2/Gazebo simulation |
| **Diabetic retinopathy classification** | EfficientNetB0, APTOS 2019, preprocessing, and augmentation |

## How I work

I enjoy turning an ambiguous video problem into an experiment with measurable results. My approach combines dataset preparation, model evaluation, visual debugging, and iteration on difficult sequences.

My experience also includes **mentoring interns, documenting methods, coordinating technical work remotely, and explaining model behavior and limitations**.

## Education & languages

**Master's in Artificial Intelligence and Virtual Reality**  
Ibn Tofail University · Faculty of Sciences, Kénitra · 2025

| Arabic | French | English |
| :---: | :---: | :---: |
| Native | Professional | Intermediate |

<details>
<summary><b>Additional certifications</b></summary>

Skillsoft · November 2023

- Automation Testing for Python
- AI/ML Data Strategy
- Network Monitoring & Remote Access

</details>

## GitHub activity

<p align="center">
  <a href="https://github.com/MehdiHCH">
    <img src="https://github-activity-graph.luckylinux.dev/graph?username=MehdiHCH&theme=react-dark&hide_border=true&area=true" width="95%" alt="Hicham's GitHub contribution activity graph" />
  </a>
</p>

## Let's connect

Interested in **computer vision, sports technology, geometric vision, or efficient video inference**? I'm happy to exchange ideas and discuss relevant technical collaborations.

**[Portfolio](https://mehdihch.github.io/Portfolio/)** · **[LinkedIn](https://www.linkedin.com/in/elmehdihicham/)** · **[Email](mailto:mehdihicham736@gmail.com)**

<sub>Last updated: November 2026</sub>
