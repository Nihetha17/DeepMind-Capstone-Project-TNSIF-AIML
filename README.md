# Group 6 Capstone Project

A machine learning capstone project consisting of two applications that demonstrate **Supervised Learning** and **Unsupervised Learning** concepts.

---

## 📌 Projects

### 1. 📧 Email Spam Detection

**Type:** Supervised Machine Learning

A machine learning application that classifies emails as:

- **Spam**
- **Not Spam (Ham)**

The model is trained using labelled email data and uses text preprocessing and feature extraction to make predictions on new emails.

#### Key Concepts

- Labelled datasets
- Text preprocessing
- Feature extraction
- Train/Test Split
- Classification
- Model Evaluation
- Model Saving and Reuse
- Prediction through an application interface

---

### 2. 👥 Customer Persona Segmenter

**Type:** Unsupervised Machine Learning

A customer segmentation application that groups customers into different personas based on characteristics such as:

- Annual Income
- Spending Score

The project uses **K-Means Clustering** to identify customer groups without predefined labels.

#### Key Concepts

- Unlabelled data
- Data preprocessing
- Feature scaling
- K-Means Clustering
- Cluster analysis
- Customer persona mapping
- Data visualization

---

## 🏗️ Repository Structure

```text
Group-6-Capstone-Project/
│
├── README.md
│
├── supervised/
│   └── email-spam-detection/
│       ├── README.md
│       ├── requirements.txt
│       │
│       ├── backend/
│       │   ├── train_model.py
│       │   ├── app.py
│       │   └── spam_emails.csv
│       │
│       └── frontend/
│           ├── index.html
│           ├── style.css
│           └── script.js
│
└── unsupervised/
    └── customer-persona-segmenter/
        ├── README.md
        ├── requirements.txt
        ├── dataset_unsupervised.py
        ├── train_kmeans.py
        ├── main_unsupervised.py
        └── app_unsupervised.py
