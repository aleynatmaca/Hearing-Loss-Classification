# Hearing-Loss-Classification
# 🩺 Audiogram-Based Hearing Loss Classification

This project is a machine learning model designed to classify the type of hearing loss (Sensorineural, Conductive, or Normal) based on pure-tone audiometry thresholds. 

As a multidisciplinary project, it bridges the gap between clinical audiology and computer engineering, demonstrating how AI can assist in medical diagnostic processes.

## 🛠️ Technologies Used
* **Python**
* **Pandas:** Used for structuring and preprocessing the audiogram dataset.
* **Scikit-Learn:** Used for building and training the classification model.
* **Algorithm:** Decision Tree Classifier (chosen for its explainability in medical decision-making).

## 📊 How It Works
The model takes input features representing air-conduction hearing thresholds at specific frequencies (500Hz, 1000Hz, 2000Hz, and 4000Hz). Based on the patterns learned from the training data, it predicts the corresponding clinical diagnosis. 

*Example Input:* `[50, 55, 60, 65]` (Thresholds in dB HL)
*Model Output:* `['Sensorinoral']`

*Note: This repository currently includes a foundational script with sample data to demonstrate the algorithmic approach. It can be scaled with larger clinical datasets (e.g., Kaggle data) for higher accuracy.*
