<div align="center">

# 🚗 Vehicle Insurance Prediction MLOps Pipeline

### End-to-End MLOps Project | Machine Learning | Docker | AWS | CI/CD | MongoDB | FastAPI

<p align="center">
<img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Machine%20Learning-ScikitLearn-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/Docker-Containerized-blue?style=for-the-badge&logo=docker">
<img src="https://img.shields.io/badge/AWS-ECR%20%7C%20EC2-yellow?style=for-the-badge&logo=amazonaws">
<img src="https://img.shields.io/badge/MongoDB-Atlas-green?style=for-the-badge&logo=mongodb">
<img src="https://img.shields.io/badge/GitHub-Actions-black?style=for-the-badge&logo=githubactions">
<img src="https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge">
</p>

### ⭐ An End-to-End Production Grade Machine Learning Pipeline following MLOps Best Practices

</div>

---

# 📌 Overview

This project demonstrates a **complete MLOps lifecycle** for predicting vehicle insurance outcomes.

Unlike traditional ML notebooks, this project focuses on **production-ready architecture**, including:

- Data Versioning
- MongoDB Integration
- Modular ML Pipeline
- Automated Model Training
- Model Evaluation
- AWS S3 Model Registry
- Docker Containerization
- CI/CD using GitHub Actions
- Deployment on AWS EC2
- REST API using FastAPI

---

# 🚀 Project Architecture

```
                Dataset
                   │
                   ▼
            MongoDB Atlas
                   │
                   ▼
          Data Ingestion Pipeline
                   │
                   ▼
          Data Validation Pipeline
                   │
                   ▼
        Data Transformation Pipeline
                   │
                   ▼
            Model Training
                   │
                   ▼
            Model Evaluation
                   │
                   ▼
            Model Registry
               (AWS S3)
                   │
                   ▼
          Docker Container
                   │
                   ▼
        GitHub Actions CI/CD
                   │
                   ▼
             AWS ECR
                   │
                   ▼
              AWS EC2
                   │
                   ▼
            FastAPI Web App
```

---

# ✨ Features

✅ End-to-End Machine Learning Pipeline

✅ Modular Project Structure

✅ MongoDB Atlas Integration

✅ Custom Exception Handling

✅ Logging Framework

✅ YAML Based Configuration

✅ Automated Data Validation

✅ Feature Engineering

✅ Model Training Pipeline

✅ Model Evaluation

✅ AWS S3 Model Registry

✅ Dockerized Application

✅ GitHub Actions CI/CD

✅ AWS Elastic Container Registry (ECR)

✅ AWS EC2 Deployment

✅ FastAPI Prediction API

---

# 🛠️ Tech Stack

| Category | Technology |
|-----------|------------|
| Language | Python 3.10 |
| ML | Scikit-Learn |
| Data | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Database | MongoDB Atlas |
| Backend | FastAPI |
| Cloud | AWS EC2 |
| Storage | AWS S3 |
| Container | Docker |
| Registry | AWS ECR |
| CI/CD | GitHub Actions |
| Version Control | Git & GitHub |

---

# 📂 Project Structure

```
MLops-Proj1
│
├── artifacts/
├── notebook/
├── src/
│   ├── components/
│   ├── configuration/
│   ├── cloud/
│   ├── entity/
│   ├── pipeline/
│   ├── utils/
│   ├── exception/
│   ├── logger/
│   └── aws_storage/
│
├── templates/
├── static/
├── app.py
├── demo.py
├── requirements.txt
├── setup.py
├── pyproject.toml
├── Dockerfile
├── .dockerignore
└── .github/workflows/aws.yaml
```

---

# ⚙️ Installation

Clone Repository

```bash
git clone https://github.com/<yourusername>/MLops-Proj1.git

cd MLops-Proj1
```

Create Environment

```bash
conda create -n vehicle python=3.10 -y

conda activate vehicle
```

Install Requirements

```bash
pip install -r requirements.txt
```

---

# 🍃 MongoDB Setup

- Create MongoDB Atlas Cluster
- Create Database User
- Allow Network Access
- Obtain MongoDB Connection String

Set Environment Variable

### Linux / Mac

```bash
export MONGODB_URL="your_connection_string"
```

### Windows PowerShell

```powershell
$env:MONGODB_URL="your_connection_string"
```

---

# ☁️ AWS Configuration

Configure AWS Credentials

```bash
export AWS_ACCESS_KEY_ID="YOUR_KEY"

export AWS_SECRET_ACCESS_KEY="YOUR_SECRET"

export AWS_DEFAULT_REGION="us-east-1"
```

Required AWS Services

- IAM
- S3
- ECR
- EC2

---

# 🐳 Docker

Build Image

```bash
docker build -t vehicleproj .
```

Run Container

```bash
docker run -p 5000:5000 vehicleproj
```

---

# 🚀 CI/CD Pipeline

This project implements a complete CI/CD pipeline using **GitHub Actions**.

Workflow:

```
Developer Push
        │
        ▼
GitHub Actions
        │
        ▼
Build Docker Image
        │
        ▼
Push to AWS ECR
        │
        ▼
Deploy on EC2
        │
        ▼
Application Live
```

---

# 🌐 Deployment

Deployment Platform

- AWS EC2

Container Registry

- AWS ECR

Storage

- AWS S3

Application

- FastAPI

---

# 📊 Machine Learning Workflow

```
Data Collection

↓

Data Validation

↓

Data Transformation

↓

Model Training

↓

Model Evaluation

↓

Model Registry

↓

Prediction Pipeline
```

---

# 🔥 API

Train Model

```
/training
```

Prediction

```
/
```

---

# 📸 Screenshots

> Add screenshots here

- Home Page
- Prediction Page
- Training Pipeline
- GitHub Actions
- AWS EC2
- MongoDB Atlas

---

# 📈 Future Improvements

- Kubernetes Deployment
- Terraform Infrastructure
- MLflow Integration
- Model Monitoring
- Data Drift Detection
- Prometheus & Grafana
- Auto Retraining Pipeline

---

# 🤝 Contributing

Contributions are always welcome.

Fork the repository

Create a feature branch

Submit a Pull Request

---

# 👨‍💻 Author

## Satyam Suri

Machine Learning Engineer | MLOps Enthusiast | Python Developer

📧 Email: your-email@example.com

💼 LinkedIn: https://linkedin.com/in/yourprofile

🌐 Portfolio: https://yourportfolio.com

---

<div align="center">

### ⭐ If you found this project helpful, don't forget to Star the Repository ⭐

Made with ❤️ using Python, Docker & AWS

</div>