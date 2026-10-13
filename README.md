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

### Now: AI/ML Engineer at Nxmpliscore

I build the AI behind **ANVAYA**, the company's infant-care product line, across the whole stack: the models, the device firmware, the cloud services and the mobile apps.

<sub>These projects are closed source. The descriptions cover what I built, not internal details.</sub>

**ANVAYA SMART: AI baby monitor** · `ESP32-S3` `ESP-IDF` `WebRTC` `Flutter`<br>
A camera-and-microphone baby monitor that streams live video and audio to the parent's phone. I wrote the firmware, the streaming path and the app side. I profiled the device and network path and turned a stuttering stream into smooth, stable, low-latency playback.

**Cry Analysis Engine** · `Deep learning` `FastAPI` `Docker` `Google Cloud Run`<br>
Listens to a baby's cry and tells the parent the likely reason. It's a multi-class audio model, served on Google Cloud, that sets aside sounds it doesn't recognise instead of guessing. I traced gaps between test accuracy and real-world accuracy back to differences between how audio was prepared for training and for serving.

**On-device cry detection** · `TensorFlow Lite Micro` `ESP32-S3` `C`<br>
The first stage of the Cry Analysis Engine, quantised to run inside the monitor's firmware. The device recognises a cry by itself and uploads only those clips, which saves bandwidth and keeps everyday household sound off the cloud.

**ANVI: Pediatric Intelligence Platform** · `LLMs` `RAG` `PostgreSQL / pgvector` `FastAPI`<br>
An AI assistant for parents that answers from vetted pediatric knowledge and the family's own records. Each family's data is kept separate, and an automated safety test suite, itself checked with mutation testing, guards every answer. I designed it and am leading the build.

**ANVAYA app** · `Flutter` `Dart` `Firebase`<br>
The free Flutter app for tracking a baby's daily care. It works offline first and runs on a shared design system I built.

---

### Public projects

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
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv,fastapi,docker,aws,gcp,githubactions,flutter,dart,firebase,c,arduino,postgres,mongodb,linux&perline=9" alt="Python, PyTorch, TensorFlow, scikit-learn, OpenCV, FastAPI, Docker, AWS, GCP, GitHub Actions, Flutter, Dart, Firebase, C, Arduino, PostgreSQL, MongoDB, Linux">
</p>

**ML:** CNNs, detection & tracking (YOLO), re-identification embeddings, audio classification, TFLite Micro quantisation, RAG and LLM evaluation<br>
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
