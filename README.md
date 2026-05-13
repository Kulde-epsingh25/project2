<p align="center">
  <img src="docs/images/banner.png" alt="NexusAI Banner" width="100%">
</p>

# 🚀 NexusAI Pro Suite: Advanced Conversational AI & Market Analytics

[![Python](https://img.shields.io/badge/Python-3.14%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Data](https://img.shields.io/badge/Data-Real--Time--Capable-green)](https://github.com/NexusAI)
[![Models](https://img.shields.io/badge/Models-Random%20Forest%20%7C%20Naive%20Bayes%20%7C%20NLP-purple)](#key-features)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

**NexusAI Pro Suite** is a high-performance framework designed to unify the power of predictive analytics and intelligent conversational agents. By blending classical statistical rigor with state-of-the-art Natural Language Processing (NLP), this project provides a seamless ecosystem for both customer retention and interactive AI assistance.

---

## 📽️ Project Overview
The platform automates the entire AI/ML lifecycle: from multi-source data ingestion (CSV/XLSX) and feature engineering to model deployment and interactive glassmorphism visualization.

### 📊 The Intelligence Ecosystem
The suite provides dedicated interfaces for conversational AI and predictive churn analysis, both powered by high-performance scikit-learn backends.

---

## 🛠️ Architecture & Workflow

```mermaid
graph TD
    A[Data Acquisition] -->|CSV/XLSX Ingestion| B[Preprocessing Layer]
    B --> C{Feature Engineering}
    C -->|One-Hot/Scaling| D[Model Training]
    C -->|Sentiment Extraction| D
    D --> E[Statistical Models]
    D --> F[Conversational AI]
    E -->|Random Forest/LR| G[Evaluation Engine]
    F -->|NLP/Regex Fallback| G
    G -->|Accuracy Scoring| H[Champion Selection]
    H --> I[Interactive Web Portal]
    H --> J[FastAPI Backend]
```

---

## ✨ Key Features
- **Multi-Model Intelligence**: Simultaneously handles **Random Forest** for churn forecasting and **Naive Bayes** for intent classification.
- **Sentiment-Driven Insights**: Integrates real-time lexicon analysis to capture the "human" emotion behind customer interactions.
- **Contextual Memory**: Built-in persistence layer that allows the AI to remember and adapt to multi-turn conversation flows.
- **Enterprise Reporting**: Generates ready-to-use exports for Power BI and interactive HTML dashboards for business stakeholders.

---

## 🚦 Getting Started

### 1. Environment Setup
Clone the repository and initialize your workspace:
```bash
# Clone the repository
git clone https://github.com/NexusAI/pro-suite.git
cd nexus-ai-pro-suite

# Setup Virtual Environment
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# Install Dependencies
pip install -r backend/chatbot/requirements.txt
```

### 2. Execution Pipeline
Launch the master portal and start the backend engines:

| Task | Command | Location |
| :--- | :--- | :--- |
| **Master Portal** | Open `index.html` | Root Directory |
| **Chatbot Server** | `python server.py` | `backend/chatbot/` |
| **Churn API** | `python main.py` | `backend/churn/` |
| **Model Training** | `python train_model.py` | `backend/churn/` |

---

## 🏗️ Project Structure
```text
├── frontend/      # Unified UI: Chatbot and ChurnSight Dashboards
├── backend/       # AI Engines: FastAPI, ML Models, and Inference
├── data/          # Enterprise datasets (CSV, XLSX)
├── notebooks/     # Research: Jupyter Notebooks for EDA
├── powerbi/       # Reporting: PBIX Business Intelligence files
├── docs/          # Technical guides, images, and dev notes
└── README.md
```

---
*Developed for research and analytical purposes. Built with passion for the future of AI.*
