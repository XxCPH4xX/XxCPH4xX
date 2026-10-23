# Fahim Shahrier

**Machine Learning & AI | Computer Vision | Python Development**

I’m a Software Engineering graduate from Zhengzhou University focused on building applied machine learning and computer vision projects in Python. My work spans data preparation, model training and evaluation, prediction explainability, and integrating inference workflows with APIs and web interfaces. I also develop full-stack applications that support practical business and operational workflows.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-1F425F?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Computer Vision](https://img.shields.io/badge/Computer_Vision-2D6A73?style=flat-square)

**Core focus:** Predictive modeling · Deep learning · Computer vision · Explainable AI · ML-backed APIs and dashboards

---

## Featured ML & Computer Vision Projects

These projects demonstrate different parts of the applied AI workflow, from dataset preparation and model evaluation to visual explanations and application integration.

### 1. [Predictive Maintenance AI Platform](https://github.com/XxCPH4xX/Predictive-Maintenance-AI-Platform)

An end-to-end predictive maintenance workspace built around the UCI AI4I 2020 synthetic dataset. It combines equipment failure-risk prediction, model evaluation, explainability, and an interactive dashboard.

**Technical highlights**
- Compares Logistic Regression and Random Forest baselines with XGBoost, using separate training, validation, and held-out test partitions.
- Implements SHAP-based global and individual prediction explanations.
- Integrates a FastAPI backend with a Next.js and TypeScript dashboard for single predictions, batch CSV analysis, simulated telemetry, what-if scenarios, and prediction history.
- Includes Jupyter notebooks for exploratory analysis, preprocessing, model selection, evaluation, and reproducible experimentation.

**Reported held-out test results:** Precision 40.56% · Recall 85.29% · ROC-AUC 0.9806 · Average precision 0.7706

These results apply to the project's dataset, not to real-world industrial equipment. The selected operating threshold produces false alarms, and the model has not been validated as an industrial failure-warning system.

**Technologies:** Python, Pandas, scikit-learn, XGBoost, SHAP, Jupyter, FastAPI, Next.js, TypeScript

[Repository](https://github.com/XxCPH4xX/Predictive-Maintenance-AI-Platform) · [Model card](https://github.com/XxCPH4xX/Predictive-Maintenance-AI-Platform/blob/main/reports/model_card.md)

### 2. [Chest X-ray Pneumonia Classification](https://github.com/XxCPH4xX/Chest-X-ray-Pneumonia-Classification)

An educational and research project that classifies chest X-ray images into NORMAL and PNEUMONIA categories using a ResNet18-based deep learning workflow.

**Technical highlights**
- Uses PyTorch and Torchvision to train, evaluate, and export an image classification model.
- Implements Grad-CAM visualizations to inspect regions influencing model predictions.
- Connects model inference to a FastAPI backend and a Next.js dashboard.
- Organizes experimentation into notebooks covering dataset checks, preprocessing, model development, evaluation, and inference.

**Reported held-out test results:** Accuracy 87.66% · Sensitivity 96.15% · Specificity 73.50% · ROC-AUC 94.49%

These are dataset-level results, not evidence of clinical effectiveness. The repository documents limitations involving potential patient overlap and domain shift. The model is not clinically validated, and its predictions must not be used for patient care.

**Technologies:** Python, PyTorch, Torchvision, Grad-CAM, Jupyter, FastAPI, Next.js, TypeScript

[Repository](https://github.com/XxCPH4xX/Chest-X-ray-Pneumonia-Classification)

### 3. [Plant Disease Detection Using Deep Learning](https://github.com/XxCPH4xX/plant-disease-detection-using-deep-learning)

A leaf-image classification project that identifies 38 disease and healthy-leaf categories across 14 plant species through a convolutional neural network.

**Technical highlights**
- Implements a CNN with 10 convolutional layers using TensorFlow/Keras.
- Processes RGB leaf images and produces predictions across the supported plant classes.
- Includes training and evaluation notebooks, training-history visualizations, a confusion matrix, and a classification report.
- Provides a Streamlit interface for uploading leaf images and viewing predictions.

The project documents evaluation workflows and visualizations; no performance figure is included here because a representative, verified test metric has not been established for this profile.

**Technologies:** Python, TensorFlow, Keras, NumPy, scikit-learn, Matplotlib, Streamlit

[Repository](https://github.com/XxCPH4xX/plant-disease-detection-using-deep-learning)

### 4. [HandSign Detection](https://github.com/XxCPH4xX/HandSign-Detection)

A real-time webcam-based hand-sign recognition project covering six ASL letter classes: **I, L, O, V, E, and U**.

**Technical highlights**
- Detects hands from live webcam input and classifies supported hand signs.
- Uses hand-region cropping, resizing, and normalization before inference.
- Includes a data-collection workflow for capturing custom training images.
- Combines MediaPipe-based hand processing with a TensorFlow/Keras classification model.

The implementation recognizes the listed letters; it does not represent a complete sign-language translation system.

**Technologies:** Python, OpenCV, MediaPipe, cvzone, TensorFlow/Keras, NumPy

[Repository](https://github.com/XxCPH4xX/HandSign-Detection)

### 5. [Smart Attendance System Using Face Recognition](https://github.com/XxCPH4xX/smart-attendance-system-using-face-recognition)

A webcam-based attendance prototype that identifies registered faces and records attendance with timestamps.

**Technical highlights**
- Processes live webcam frames using OpenCV.
- Generates and compares face encodings using the `face_recognition` library.
- Distinguishes recognized faces from unknown individuals.
- Records attendance in CSV format with timestamps.

**Technologies:** Python, OpenCV, face_recognition, dlib, NumPy

[Repository](https://github.com/XxCPH4xX/smart-attendance-system-using-face-recognition)

---

## Other Software Engineering Projects

Alongside ML/AI experimentation, I build web applications that combine backend services, databases, frontend interfaces, and domain-specific business logic.

| Project | Overview | Repository |
|---|---|---|
| **PharmacyPOS** | Pharmacy operations and POS development pilot covering medicine catalogues, barcode/SKU lookup, batch and expiry tracking, FEFO inventory handling, box/strip/pack conversion, role-based access, and operational records. Built with Next.js, TypeScript, Django REST Framework, and PostgreSQL. | [View repository](https://github.com/XxCPH4xX/PharmacyPOS) |
| **Restaurant POS (EzPOS)** | Restaurant management and point-of-sale application covering dine-in, takeaway and delivery orders, table management, kitchen tickets, stock tracking, reservations, payments, and reporting. Uses Next.js, React, TypeScript, Django REST Framework, and PostgreSQL. | [View repository](https://github.com/XxCPH4xX/POS) |
| **Customer Feedback Dashboard** | Feedback collection and ratings dashboard with PostgreSQL persistence, Chart.js visualizations, and keyword-based sentiment classification. Uses an Express backend and JavaScript frontend. | [View repository](https://github.com/XxCPH4xX/Customer-Feedback-Dashboard) |

---

## Technical Skills

The following technologies are drawn from my existing profile and project documentation. Their inclusion reflects use across projects, not an assertion of equal proficiency in every tool.

### Machine Learning & AI

`scikit-learn` · `XGBoost` · `SHAP` · Predictive modeling · Classification · Model evaluation · Explainable AI

### Deep Learning & Computer Vision

`PyTorch` · `Torchvision` · `TensorFlow` · `Keras` · `OpenCV` · `MediaPipe` · `cvzone` · `Grad-CAM`

### Data Analysis & Experimentation

`NumPy` · `Pandas` · `Jupyter Notebook` · `Matplotlib` · `Seaborn` · Exploratory data analysis · Data preprocessing · Train/validation/test evaluation

### Programming Languages

`Python` · `TypeScript` · `JavaScript` · `SQL`

### Backend Development & APIs

`FastAPI` · `Django` · `Django REST Framework` · `Express`

### Frontend Development

`Next.js` · `React` · `Tailwind CSS` · `Streamlit`

### Databases, Tools & Development Environments

`PostgreSQL` · `SQLite` · `Git` · `GitHub` · `Linux` · `VS Code`

---

## Engineering Approach

Across my projects, I focus on connecting implementation details with measurable outcomes and usable software:

- **Data and evaluation:** Inspecting datasets, preparing model inputs, separating training and evaluation stages, and reporting measured results with their limitations.
- **Model interpretation:** Using techniques such as SHAP and Grad-CAM to examine model behavior rather than presenting predictions without context.
- **Application integration:** Connecting Python-based inference workflows to APIs, dashboards, and practical user interfaces.
- **Software development:** Applying backend, frontend, and database technologies to build applications around clearly defined workflows.

---

## Explore More

For source code, implementation details, setup instructions, notebooks, and project-specific documentation, visit the repositories directly.

**[Browse all repositories on GitHub →](https://github.com/XxCPH4xX?tab=repositories)**

**[GitHub Profile](https://github.com/XxCPH4xX)**
