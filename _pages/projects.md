---
title: "Projects"
layout: single
permalink: /projects/
author_profile: true
---

<style>
.video-container {
  margin-bottom: 3rem;
  border: 1px solid #ddd;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 12px rgba(0, 0, 0, 0.05);
  position: relative;
  width: 100%;
  height: 0;
  padding-bottom: 56.25%; /* 16:9 aspect ratio */
}
.video-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>



## 🔐 CopyGuard – Serverless AI Code Detection Platform  
**Tech Stack**: AWS Lambda, Bedrock Claude v2, Terraform, S3, CloudFront, Grafana, MLOps  
[GitHub Repo](https://github.com/Yashmaini30/CopyGuard) | [Blog](https://ai-code-detector-with-aws-bedrock.hashnode.dev/building-copyguard-a-production-ready-ai-code-detection-platform-on-aws)
- Built a production-grade platform to detect AI-generated code using **Amazon Bedrock (Claude v2)**.
- Achieved **~99.9% availability** with sub-2s response time via AWS Lambda.
- Deployed complete IaC stack with Terraform (API Gateway, IAM, logging, CORS).
- Monitored system latency and model confidence using **Grafana dashboards**.
- Outputs versioned and stored in S3 for audit and reproducibility.

### 📽️ Demo Video
<div class="video-container">
  <iframe src="https://player.vimeo.com/video/1102706536?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479"
           frameborder="0"
           allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media; web-share"
           referrerpolicy="strict-origin-when-cross-origin"
           title="CopyGuard: AI Code Detector Powered by Claude v2 &amp; AWS">
  </iframe>
</div>

## 🔐 ThreatMatrix – MLOps Pipeline for Network Intrusion Detection  
**Tech Stack**: Python, FastAPI, MongoDB, MLflow, DagsHub, Docker, GitHub Actions, AWS EC2  
[GitHub Repo](https://github.com/Yashmaini30/ThreatMatrix-Predictor) | [Blog](https://mlops-threat-detection-platform.hashnode.dev/building-a-production-ready-mlops-platform-for-network-security-threat-detection)
- Developed an end-to-end MLOps system for **real-time intrusion detection**.
- Modular pipeline with custom internal Python package for data ingestion, validation, transformation, training, and prediction.
- Containerized pipeline using Docker and **CI/CD via GitHub Actions**; images deployed to Amazon ECR.
- Real-time **FastAPI endpoints** (`/train`, `/predict`) served on AWS EC2 with <15ms latency.
- Tracked experiments and metrics using **MLflow + DagsHub**.

### 📽️ Demo Video
<div class="video-container">
  <iframe src="https://player.vimeo.com/video/1102706272?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479"
           frameborder="0"
           allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media; web-share"
           referrerpolicy="strict-origin-when-cross-origin"
           title="ThreatMatrix: MLOps-Powered Intrusion Detection System">
  </iframe>
</div>

## 🏥 MP4-to-DICOM Conversion Pipeline (For AIIMS Delhi)  
**Tech Stack**: In progress (under evaluation)  
*No public code or blog available yet*
- Currently contributing to a project under the guidance of **Prof. Dr. Deepak Agrawal** (AIIMS Delhi), aimed at automating the conversion of **MP4 videos to DICOM format** for radiological workflows.
- The project is designed to benefit radiology departments at **AIIMS**, aligning with broader clinical infrastructure goals.
- Focused on **pipeline architecture**, tool selection, and reproducibility.
- Currently in the **planning and prototyping phase**.

## 🌿 Tomato Leaf Disease Detection  
**Tech Stack**: TensorFlow, Keras, Xception, Seaborn, Matplotlib  
[GitHub Repo](https://github.com/Yashmaini30/Tomato_Leaf_Disease_Detection) | [Blog](https://xception-model-for-leaf-diseases.hashnode.dev/xception-based-tomato-disease-detection-9723-9723-accuracy)
- Achieved **97.23% accuracy** using a fine-tuned **Xception** model with hyperparameter tuning.
- Used data augmentation, transfer learning, and dropout regularization.
- Backed by an **IEEE conference publication**.

## 🧠 Breast Cancer Detection Using Deep Learning  
**Tech Stack**: CNNs, Population-Based Training, Transfer Learning  
[GitHub Repo](https://github.com/Yashmaini30/Breast-Cancer-Detection) | [Blog](https://deep-learning-for-breast-cancer.hashnode.dev/discover-ais-role-in-breast-cancer-detection-deep-and-transfer-learning-achieves-9846-accuracy)
- Developed a deep learning pipeline for breast tumor classification from mammogram images.
- Achieved **98.46% accuracy** using **Population-Based Training** and model fine-tuning.
- Work presented at an **IEEE conference** and now extended to uncertainty-based model calibration for journal submission.

> For full research details and metrics, visit my [Publications](/publications/) or [Experience](/experience/) pages.

<script src="https://player.vimeo.com/api/player.js"></script>