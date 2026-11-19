<div align="center">

<img src="assets/avatar_pro.png" width="130" alt="Parvathi"/>

# Parvathi M

**AI / ML Engineer · Computer Vision · Deep Learning**

*Building efficient, intelligent perception systems through research and engineering.*

<br>

<a href="https://www.linkedin.com/in/parvathi-m-a1b684289/"><img src="https://img.shields.io/badge/LinkedIn-Connect-4f46e5?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="mailto:parvathim213@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-4f46e5?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/Parvathi-Mn"><img src="https://img.shields.io/badge/GitHub-Parvathi--Mn-4f46e5?style=flat-square&logo=github&logoColor=white"/></a>

<br>

[About](#about) · [Research](#research-highlight) · [Projects](#projects) · [Stack](#tech-stack) · [Experience](#experience) · [Achievements](#achievements)

</div>

---

## About

Final-year **B.Tech Computer Science** student at **VIT Bhopal** (CGPA 8.55) with hands-on research experience in computer vision and deep learning. At **IIT Kharagpur**, I designed, trained and benchmarked a real-time instance segmentation architecture on NVIDIA RTX 4090 GPUs.

|  |  |
|:--|:--|
| 🔭 **Currently** | Building a crop classification and irrigation advisory system with Sentinel-2 and SAR imagery |
| 📚 **Learning** | GenAI and AI engineering: LLMs, RAG, deployment |
| 🎯 **Looking for** | ML / Computer Vision internships in efficient perception for unmanned systems |
| 📝 **Writing** | Co-authoring a journal manuscript on instance segmentation *(in preparation)* |

---

## Research Highlight

### YOLO-MambaRegionMoE
*Real-time instance segmentation · IIT Kharagpur (RCG-SIDM) · May – Jun 2026*

A hybrid architecture built on **YOLOv12** that combines:

- **Mamba VSSBlock** (2D selective scan) for global context at linear cost
- **A2C2f** area-attention refinement in the PAN-FPN neck
- **Sparse top-K Mixture-of-Experts** routing, with soft top-K in training and hard top-K at inference so only K experts run

<div align="center">

| mAP@50 | mAP@50–95 | Parameters | Compared with Mask R-CNN |
|:--:|:--:|:--:|:--:|
| **0.900** | **0.743** | **6.3M** | **~7× smaller** (44.4M) |

<sub>Highest mAP among six models trained from scratch under identical conditions on COCO128-Seg · NVIDIA RTX 4090 · ~200 hyperparameter trials per model</sub>

</div>

**Also built:** a Genetic Algorithm tuning framework adapted across Ultralytics YOLO, TorchVision Mask R-CNN, Mamba-YOLO, YOLO-Master and Mask2Former, plus a unified COCO evaluation pipeline so every model reports comparable metrics.

---

## Projects

| Project | What it does | Stack |
|:--|:--|:--|
| **MambaRegionMoE** | Efficient instance segmentation research, benchmarked against five other architectures | `PyTorch` `YOLOv12` `Mamba` `MoE` |
| **FloodLine** | AI-powered flood intelligence with multilingual assistance | `Python` `FastAPI` `Gemini` |
| **Climate Gentrification Risk Mapping** | Random Forest risk model served through an API to an interactive GIS dashboard | `Python` `FastAPI` `React` `Leaflet` |
| **Crop Classification & Irrigation Advisory** | ISRO Bharatiya Antariksh Hackathon 2026 (PS-06), using optical and SAR satellite imagery *(in progress)* | `Sentinel-2` `SAR` `Python` |

---

## Tech Stack

**Languages**<br>
![Python](https://img.shields.io/badge/-Python-4f46e5?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-4f46e5?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/-C-4f46e5?style=flat-square&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4f46e5?style=flat-square&logo=mysql&logoColor=white)

**Deep Learning & Computer Vision**<br>
![PyTorch](https://img.shields.io/badge/-PyTorch-6366f1?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-6366f1?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/-Ultralytics%20YOLO-6366f1?style=flat-square)
![CUDA](https://img.shields.io/badge/-CUDA-6366f1?style=flat-square&logo=nvidia&logoColor=white)
![ViT](https://img.shields.io/badge/-Vision%20Transformers-6366f1?style=flat-square)
![Mamba](https://img.shields.io/badge/-State%20Space%20Models-6366f1?style=flat-square)

**ML & Optimization**<br>
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-8b5cf6?style=flat-square&logo=scikitlearn&logoColor=white)
![Genetic Algorithms](https://img.shields.io/badge/-Genetic%20Algorithms-8b5cf6?style=flat-square)
![Hyperparameter Tuning](https://img.shields.io/badge/-Hyperparameter%20Tuning-8b5cf6?style=flat-square)

**Geospatial**<br>
![GIS](https://img.shields.io/badge/-GIS-0ea5e9?style=flat-square)
![Remote Sensing](https://img.shields.io/badge/-Remote%20Sensing-0ea5e9?style=flat-square)
![Sentinel-2](https://img.shields.io/badge/-Sentinel--2%20%2F%20SAR-0ea5e9?style=flat-square)

**Tools & Cloud**<br>
![FastAPI](https://img.shields.io/badge/-FastAPI-64748b?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/-React-64748b?style=flat-square&logo=react&logoColor=white)
![Git](https://img.shields.io/badge/-Git-64748b?style=flat-square&logo=git&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS%20Certified-64748b?style=flat-square&logo=amazonaws&logoColor=white)

---

## Experience

**Research Intern** · IIT Kharagpur, Computer Vision & Deep Learning (RCG-SIDM)
*7 May – 30 June 2026 · Supervisor: Prof. Bharath Haridas Aithal*

- Designed and benchmarked a hybrid real-time instance segmentation model (see Research Highlight)
- Integrated and debugged multiple research codebases, resolving tensor-shape and dependency issues through to stable training
- Built foundations in remote sensing, GIS, GNSS and digital image processing before moving to CNNs, U-Net and YOLO
- Presented progress to the supervisor and mentor and sent daily written updates

---

## Education

**Vellore Institute of Technology, Bhopal**
B.Tech, Computer Science Engineering · CGPA 8.55 · 2023 – 2027

<sub>Coursework: Data Structures & Algorithms · Operating Systems · Computer Organization & Architecture · DBMS · OOP · Theory of Computation</sub>

---

## Achievements

- 🏅 Selected from **80,000+ applicants** for an elite Graph Algorithms Camp led by a Codeforces Master
- 🔬 Research Intern at **IIT Kharagpur**
- 🛰️ Participant, **ISRO Bharatiya Antariksh Hackathon 2026**
- ☁️ Certified: **AWS Solutions Architect**, Machine Learning (NPTEL), Fundamentals of AI/ML

---

<div align="center">

<sub>Open to internships and research collaborations · <a href="https://www.linkedin.com/in/parvathi-m-a1b684289/">Let's connect</a></sub>

<sub>Always learning. Always building.</sub>

</div>
