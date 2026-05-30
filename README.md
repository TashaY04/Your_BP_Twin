# 🩺 Digital Twin for Hypertension Treatment Recommendation

## Overview

Digital Twin for Hypertension Treatment Recommendation is an AI-powered healthcare platform that creates a virtual representation of a patient and simulates treatment outcomes before real-world intervention.

The system combines Machine Learning, Synthetic Data Generation, and Predictive Analytics to support personalized hypertension treatment recommendations. By leveraging GAN-generated synthetic patient profiles and ensemble learning models, the platform addresses data scarcity, class imbalance, and rare clinical scenarios.

---

## Key Highlights

* Built a healthcare Digital Twin framework for treatment outcome simulation.
* Trained ensemble models on 7,000+ patient records.
* Achieved 95.6% prediction accuracy.
* Generated synthetic patient profiles using GANs to improve model robustness.
* Developed an end-to-end React + Flask application.
* Research paper currently under review at a Scopus-indexed journal.

---

## Problem Statement

Hypertension remains one of the most prevalent chronic diseases worldwide. Treatment outcomes vary significantly based on:

* Age
* Lifestyle
* Medical history
* Existing comorbidities
* Medication response

Traditional machine learning approaches often struggle with:

* Limited clinical datasets
* Rare patient conditions
* Class imbalance
* Lack of simulation capability

This project addresses these challenges through Digital Twin technology and synthetic data augmentation.

---

## System Architecture

<img width="1400" height="1800" alt="project_flow" src="https://github.com/user-attachments/assets/005d17a0-f070-4130-a03e-5e12db034108" />

### Workflow

Patient Data
     ⬇
Data Preprocessing
     ⬇
GAN-based Synthetic Data Generation
     ⬇
Enhanced Dataset
     ⬇
Ensemble Learning Models
(XGBoost + Random Forest + Gradient Boosting)
     ⬇
Treatment Recommendation Engine
     ⬇
Digital Twin Simulation
     ⬇
Outcome Prediction Dashboard

---

## Technology Stack

| Category         | Technologies                                            |
| ---------------- | ------------------------------------------------------- |
| Frontend         | React.js                                                |
| Backend          | Flask                                                   |
| Machine Learning | XGBoost, Random Forest, Gradient Boosting, Scikit-Learn |
| Deep Learning    | GAN (Generative Adversarial Network)                    |
| Data Processing  | Pandas, NumPy                                           |
| Visualization    | Matplotlib, Seaborn                                     |

---

## Machine Learning Pipeline

### 1. Data Collection

Clinical hypertension dataset containing:

* Demographic information
* Blood pressure measurements
* Medical history
* Treatment records

### 2. Data Preprocessing

* Missing value handling
* Feature engineering
* Normalization
* Outlier detection

### 3. Synthetic Data Generation

A Generative Adversarial Network (GAN) was trained to create realistic synthetic patient profiles for underrepresented clinical scenarios.

Benefits:

* Reduced class imbalance
* Improved model generalization
* Enhanced prediction reliability

### 4. Model Training

Ensemble learning approach using:

* XGBoost
* Random Forest
* Gradient Boosting

### 5. Digital Twin Simulation

The trained models create a virtual patient representation capable of predicting treatment outcomes before intervention.

---

## Application Preview

### Detailed Workflow

<img width="1345" height="690" alt="Workflow" src="https://github.com/user-attachments/assets/3f626b33-9af2-4514-9c13-d1f7afc94ccd" />

---

## Results

### Performance Metrics

| Metric         | Value             |
| -------------- | ----------------- |
| Dataset Size   | 7000+ Records     |
| Model Accuracy | 95.6%             |
| Models Used    | 3 Ensemble Models |
| Synthetic Data | GAN Generated     |
| Deployment     | React + Flask     |

### Model Evaluation

<img width="1596" height="850" alt="1" src="https://github.com/user-attachments/assets/3ef0ada5-f46c-4066-b0ac-183a784cd123" />

<img width="1581" height="863" alt="2" src="https://github.com/user-attachments/assets/9df0bd7c-3958-4ade-a7c3-08bd03989b18" />

<img width="1564" height="854" alt="3" src="https://github.com/user-attachments/assets/2fe23784-b4cf-4cbf-be7a-17051cd7de7d" />

<img width="1570" height="858" alt="4" src="https://github.com/user-attachments/assets/490f53b2-2731-4d93-aeb2-beda642dd6dd" />

<img width="1574" height="841" alt="5" src="https://github.com/user-attachments/assets/3d61e3af-1e92-4252-8eeb-8025be1f42ab" />

<img width="1569" height="852" alt="6" src="https://github.com/user-attachments/assets/776485f1-77de-4dcf-8eda-7d09c0df49da" />

<img width="1571" height="806" alt="7" src="https://github.com/user-attachments/assets/6205fa72-966d-4954-8546-21541a06e6e5" />

<img width="1578" height="800" alt="9" src="https://github.com/user-attachments/assets/6aa75776-45dd-48b7-8402-05aa182b410f" />

<img width="1572" height="847" alt="10" src="https://github.com/user-attachments/assets/960100dd-af47-4a6d-9393-2a46d0cd3525" />

---

## Sample User Workflow

1. User enters patient information.
2. Patient profile is processed by the prediction engine.
3. Synthetic data augmentation enhances model robustness.
4. Ensemble models predict treatment outcomes.
5. Digital Twin simulates potential responses.
6. Recommended treatment strategy is generated.

---

## Research Contribution

This project contributes to Digital Twin Healthcare Systems by integrating:

* Predictive Analytics
* Synthetic Data Generation
* Clinical Decision Support
* Treatment Outcome Simulation

### Publication Status

📄 Research paper currently under review at a Scopus-indexed journal - IAENG

---

## Future Enhancements

* Real-time patient monitoring
* Wearable device integration
* Explainable AI (XAI)
* Reinforcement Learning-based treatment optimization
* Multi-disease Digital Twin framework

---

## Installation

```bash
git clone https://github.com/<username>/digital-twin-hypertension.git

cd digital-twin-hypertension

pip install -r requirements.txt

python app.py
```

---

## Author

**Musti Tanisha Yadav**

Computer Science Engineering
Machine Learning & Full Stack Development

