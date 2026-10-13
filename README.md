<h1 align="center">N R Teja Prakash</h1>

<p align="center">
  <b>AI/ML Engineer</b> · Computer Vision · Edge AI on microcontrollers · Flutter
</p>

<p align="center">
  I build ML systems end to end, from the model to the firmware, the API and the app that use it.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/teja-prakash-0b49a830b"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:tejaprakash5164@gmail.com"><img src="https://img.shields.io/badge/Email-tejaprakash5164%40gmail.com-555?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Andhra%20Pradesh%2C%20India-555?style=flat-square&logo=googlemaps&logoColor=white" alt="Location">
</p>

---

### Now: Nxmpliscore Private Limited

**AI/ML Engineer** · consumer health-tech (infant care)

- **Edge AI:** took an audio-event detection model from cloud to microcontroller. It now runs as a quantised TensorFlow Lite Micro model inside ESP32-S3 firmware (ESP-IDF, C), so devices upload only the clips that matter.
- **Production ML service:** worked on a multi-stage audio classifier (detection gate → out-of-distribution check → multi-class ensemble), served with FastAPI in Docker on Google Cloud Run. Traced accuracy gaps between offline evaluation and live traffic back to preprocessing differences between training and serving.
- **Real-time device streaming:** built live audio/video from embedded hardware through a relay server to a Flutter app over WebRTC. The work covered firmware tuning (task/core pinning, PSRAM buffers, network stack), audio-codec bring-up and adaptive bitrate.
- **Flutter:** builds production mobile features across the company's apps.
- **LLM platform:** designs a retrieval-augmented assistant with per-user data isolation and an automated safety-evaluation suite.

<sub>The company's work is in private repositories. The public projects below are my own.</sub>

---

### Selected projects

**[Player Re-Identification](https://github.com/Teja5164/PlayerReIdentification_using_YOLOv11)** · `YOLOv11` `PyTorch` `ResNet50` `OpenCV`<br>
Detects players in match footage and keeps each player's ID when they leave the frame and come back. YOLOv11 handles detection, ResNet50 produces appearance embeddings, and cosine similarity re-matches players. The original audio is remuxed back in with ffmpeg. Built for an AI internship assignment at Liat.ai.

**[Poultry CCTV Analytics](https://github.com/Teja5164/bird-analytics-project)** · `OpenCV` `FastAPI`<br>
Counts birds over time from a fixed CCTV camera and estimates weight from a visual proxy. It uses MOG2 background subtraction on a cropped, downscaled region, plus a centroid tracker that gives each bird a stable ID. Per-frame counts and the weight index are written to JSON and served through a FastAPI API.

**[Chessboard → FEN](https://github.com/Teja5164/Chess_pieces_detectionusingYOLOv8)** · `YOLOv8` `OpenCV` `python-chess`<br>
Turns a photo of a chessboard into a FEN position string. Contour detection plus a perspective warp give a top-down board, a custom-trained YOLOv8 model detects the pieces, and each detection is mapped to its square.

**[Alzheimer's Stage Classification from MRI](https://github.com/Teja5164/Alzheimers-disease-detection-using-cnn)** · `CNN` `TensorFlow` `SMOTE`<br>
B.Tech team project at NIT Andhra Pradesh. A custom CNN classifies four dementia stages from brain MRI, with SMOTE used to rebalance a heavily skewed dataset. The full report is in the repo.

**[Phishing-Detection ML Pipeline](https://github.com/Teja5164/Network-Security-System)** · `scikit-learn` `MLflow` `MongoDB` `Docker` `GitHub Actions` `AWS ECR`<br>
A modular training pipeline with stages for ingestion, schema validation with a drift report, transformation and model selection. It is served through FastAPI and containerised, and GitHub Actions builds the image and pushes it to Amazon ECR.

**[Density-Based Traffic Controller](https://github.com/Teja5164/Density-Based-traffic-control-system)** · `Arduino` `C`<br>
A four-way signal controller driven by lane occupancy from IR sensors. It runs on an Arduino Uno and drives the lights through shift registers. The schematic and component list are included.

<sub>More: MLflow experiment tracking with S3/EC2 [(1)](https://github.com/Teja5164/mlflowproject-using-aws-s3-ec2-instance) [(2)](https://github.com/Teja5164/ANNusingMLOps) · Hugging Face [text summarizer](https://github.com/Teja5164/textsummerizer) · [classical ML notebooks](https://github.com/Teja5164/MachineLearningProjects)</sub>

---

### Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv,fastapi,docker,aws,gcp,githubactions,flutter,dart,c,arduino,mongodb,linux&perline=8" alt="Python, PyTorch, TensorFlow, scikit-learn, OpenCV, FastAPI, Docker, AWS, GCP, GitHub Actions, Flutter, Dart, C, Arduino, MongoDB, Linux">
</p>

**ML:** CNNs, detection & tracking (YOLO), re-identification embeddings, audio classification, TFLite Micro quantisation<br>
**MLOps:** MLflow, Docker, GitHub Actions, FastAPI serving, Cloud Run, ECR<br>
**Embedded:** ESP32-S3 (ESP-IDF), Arduino, sensor and audio-codec bring-up

---

### Background

- **B.Tech, Electronics & Communication Engineering**, NIT Andhra Pradesh (minor in Electric Vehicles)
- Previously: Junior Software Engineer (AI/ML) at Innovsolvetech; ML intern at Bharat Intern; Python intern at YBI Foundation
- Certifications: Machine Learning, IIT Kharagpur / NPTEL (top 2%) · Embedded Machine Learning, Edge Impulse / Coursera · IoT, NPTEL

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Teja5164&show_icons=true&hide=stars&hide_rank=true&hide_border=true&theme=transparent" alt="GitHub stats" height="150">
</p>
