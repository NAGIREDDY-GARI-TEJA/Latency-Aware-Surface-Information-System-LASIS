# LASIS - Latency-Aware Surface Information System

![LASIS Banner](https://via.placeholder.com/1000x200?text=Latency-Aware+Surface+Information+System+(LASIS))

🚧 **Confidential Research Project** — Code not publicly available. This repository is for showcasing methodology and results only.

LASIS (Latency-Aware Surface Information System) is a real-time semantic segmentation system optimized for unmanned aerial vehicles (UAVs). Designed for Android-based drone controllers, LASIS provides low-latency, accurate segmentation of aerial images and video feeds—without requiring external GPUs or cloud connectivity.



---

## 🚀 Project Highlights

- 📦 Lightweight U-Net architecture with 94% segmentation accuracy
- ⚡ Inference time reduced to 0.5s (mobile) and 1s (drone controller)
- 💡 Onboard real-time segmentation on resource-constrained devices
- 🌍 Applications in agriculture, disaster response, urban planning, etc.

---

## 📑 Table of Contents

- [Objectives](#-objectives)
- [System Architecture](#-system-architecture)
- [Datasets Used](#-datasets-used)
- [Preprocessing](#-preprocessing)
- [Applications](#-applications)
- [Results](#-results)
- [Project Milestones](#-project-milestones)
- [Publications](#-publications)
- [Commercialization](#-commercialization)
- [Demo](#-demo--video)
- [Contributors](#-contributors)
- [License](#-license)

---

## 🎯 Objectives

- Enable real-time semantic segmentation onboard UAVs
- Reduce latency using edge computing and lightweight AI models
- Ensure model accuracy across diverse landscapes and terrains
- Provide a scalable, cost-effective framework for aerial monitoring

---

## ⚙️ System Architecture

- 📷 Image capture & preprocessing (onboard camera)
- 🧠 TFLite-based U-Net model inference
- 🖥️ Overlay & display on Android UI
- 📱 Kotlin-based Android apps for image and video segmentation
- 🧩 Modular components for easy adaptation to different drones

---



## 🗂️ Datasets Used

- 🏙️ UaVid: Urban scene understanding
- 🌊 FloodNet: Post-flood damage detection
- 🌾 AeroSpace: Agricultural segmentation

Each includes:
- Pixel-level annotated masks
- Multi-class segmentation (e.g., buildings, vegetation, roads, water)

---

## 🧹 Preprocessing

- Resizing all images to a uniform size
- Normalization to [0, 1] pixel values
- Label harmonization across datasets
- Semi-supervised learning with sparse labels

---

## 🧭 Applications

- 🧑‍🌾 Precision Agriculture
- 🧯 Disaster Response
- 🏙️ Urban Planning & Infrastructure Inspection
- 🌳 Environmental Monitoring
- 🪖 Military Reconnaissance
- 🐘 Wildlife Conservation

---

## 📈 Results

| Platform              | Model             | IOU Score | Accuracy | Inference Time |
|----------------------|-------------------|-----------|----------|----------------|
| Android Drone         | Compressed U-Net  | 65%       | 94%      | 1 sec          |
| Android Mobile Device | Compressed U-Net  | 65%       | 94%      | 0.5 sec        |



![Segmentation Result](https://via.placeholder.com/600x300?text=Sample+Segmentation+Output)

---



## 💼 Commercialization

- 🤝 Collaborators:
  - Garuda Aerospace Pvt. Ltd.
  - IIIT Guwahati, Boston University
  - RINL-VSP for stockpile verification
- 🏢 Startup: Bhoodhristi Pvt. Ltd. (Incubated at IIITDM Kurnool)

---

## 🎥 Demo & Video

▶️ All demo videos available here:  
https://drive.google.com/drive/folders/1LSvds3--gpCnjZWgeBX_NdAAx9PS_dzX

---


