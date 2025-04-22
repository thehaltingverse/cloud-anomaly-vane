# 🌫️ cloud-anomaly-vane

*An exploration of machine learning for anomaly detection in cloud environments.*

---

## 📚 Overview

`cloud-anomaly-vane` is an open-ended machine learning project investigating anomalous patterns in cloud computing environments. The goal is to explore different algorithms and perspectives on what it means for behavior to "deviate" — not only in a technical sense, but in a conceptual one.

This project serves as a creative and technical sandbox for experimentation, modularization, and reflection on what anomaly detection *could* mean in complex, noisy systems.

---

## 🧠 Project Objectives

- Explore and compare anomaly detection algorithms (e.g., Isolation Forest, Autoencoders, One-Class SVM, etc.)
- Develop a flexible pipeline for ingesting, processing, and modeling cloud-related metrics
- Reflect philosophically on "normalcy" and how we define it through models
- Build a maintainable, scalable codebase for continued exploration

---

## 🗂️ Project Structure
```text
text cloud-anomaly-vane/
├── README.md # Project overview and guidance
├── requirements.txt # Python dependencies
├── .gitignore # Files and directories to exclude from version control
├── data/ # External data sources (not tracked by Git)
│ ├── raw/ # Unprocessed, original data 
│ └── processed/ # Cleaned and transformed data 
├── notebooks/ # Jupyter notebooks for experimentation 
│ └── 00_baseline.ipynb 
├── src/ # Core source code modules 
│ ├── __init__.py 
│ ├── data_loader.py # Data ingestion and utilities 
│ ├── models.py # Model definitions 
│ ├── train.py # Training logic 
│ └── evaluate.py # Model evaluation 
├── scripts/ # Helper scripts for automation or command-line tools 
└── tests/ # (Optional) Unit tests for code validation
```