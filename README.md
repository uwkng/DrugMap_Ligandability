# DrugMap Ligandability Prediction – AI for Accelerated Drug Discovery

## Project Overview
This project explores the **ligandability** of molecular structures using the **DrugMap_Ligandability dataset**.  
By leveraging **Machine Learning (ML) and Deep Learning (DL)**, we aim to predict which molecules are potentially relevant for drug discovery.  

## Importance of the Project
- 90% of drug candidates fail in clinical trials due to inefficiency or toxicity (Source: ASBMB, 2022).
- AI-driven drug discovery can reduce development time by 40% (Source: BCG, 2023).
- Potential cost savings in the billions, by prioritizing high-potential compounds early in the process.

## Project Goals
- Analyze molecular properties and identify key features
- Train multiple ML and DL models to predict ligandability
- Optimize predictions via hyperparameter tuning and feature engineering
- Provide insights for AI-driven pharmaceutical research

This is a **student project** conducted by a team of four as part of an academic exploration into ML/DL applications in molecular analysis.

---

## Methods & Technologies

### Exploratory Data Analysis (EDA)
- Data cleaning and feature visualization
- Identification of key molecular descriptors

### Feature Engineering
- Selection of high-impact molecular properties
- Scaling and normalization for ML modeling

### Model Development (ML & DL Approach)
We compared four ML models and one Deep Learning model:

| Model | Technology | Purpose |
|------------|----------------|---------------|
| Gradient Boosting Classifier | scikit-learn | Decision trees for feature selection |
| Random Forest Classifier | scikit-learn | Ensemble learning for robust predictions |
| Extra Trees Classifier | scikit-learn | Variability and redundancy analysis |
| LightGBM | LightGBM | Scalable gradient boosting optimization |
| Deep Learning (ANN) | TensorFlow/Keras | Multi-layer neural networks for feature extraction |

### Model Optimization & Evaluation
- Hyperparameter tuning (GridSearchCV & RandomizedSearchCV)
- Feature drop analysis to reduce overfitting
- Metrics: Accuracy, Precision, ROC-AUC, F1-Score

### Results
- Random Forest achieved the highest accuracy (~72%)
- The Deep Learning model improved accuracy by 7% after optimization

## Dataset & Sources
**Dataset:** [DrugMap_Ligandability Dataset – Hugging Face](https://huggingface.co/datasets/ymanasa2000/DrugMap_Ligandability)  
**Content:** Molecular properties for ligandability prediction  

**Key References:**  
Wellcome Trust, BCG. (2023). Potential time and cost savings through AI usage in drug discovery worldwide as of 2023, by scenario. Statista. Statista Inc.. Accessed: March 01, 2025. https://www.statista.com/statistics/1428349/ai-usage-in-drug-discovery-time-and-cost-savings-worldwide/

Sun, D. (2022). 90% of drugs fail clinical trials. [online] www.asbmb.org. Accessed: March 01, 2025. 
https://www.asbmb.org/asbmb-today/opinions/031222/90-of-drugs-fail-clinical-trials.

---

## Original Dataset
- **Source:** https://huggingface.co/datasets/ymanasa2000/DrugMap_Ligandability
- **Content:** Molecular properties for ligandability prediction

---

## Installation & Usage:
Ensure you have Python **3.8** and the required dependencies installed.

## Setup
Clone this repository:
```bash
git clone https://github.com/your_username/DrugMap_Ligandability_Prediction.git
cd DrugMap_Ligandability_Prediction
