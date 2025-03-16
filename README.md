# Fraud Detection Using Random Forest and SMOTE-Based Oversampling

## Overview
This project implements a **fraud detection model** using **Random Forest** while addressing class imbalance through **SMOTE-based oversampling**. The model is trained on the **Credit Card Fraud Detection dataset** from Kaggle and achieves high accuracy in detecting fraudulent transactions.

## Table of Contents
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Model Training & Evaluation](#model-training--evaluation)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Dataset
- The dataset contains transactions labeled as fraud or non-fraud, with a significant class imbalance.
- **Feature scaling** was applied using **StandardScaler** to enhance model performance.

## Technologies Used
- **Programming Language:** Python
- **Libraries & Frameworks:**
  - **Scikit-Learn** (Model Training & Evaluation)
  - **Pandas** (Data Handling)
  - **Seaborn & Matplotlib** (Visualization)
  - **Imbalanced-learn (SMOTE)** (Handling Class Imbalance)

## Model Training & Evaluation
- **Data Preprocessing:**
  - Split data into **training (80%)** and **testing (20%)** sets.
  - Applied **SMOTE** to balance the dataset.
- **Model Training:**
  - Used **Random Forest Classifier** with 100 estimators.
- **Evaluation Metrics:**
  - **Precision:** 87%
  - **Recall:** 83%
  - **Accuracy:** 99.96%
- **Confusion Matrix:**
  - True Positives (Fraud Detected Correctly): **81**
  - True Negatives (Non-Fraud Detected Correctly): **56852**
  - False Positives: **12**
  - False Negatives: **17**

## Results
- Achieved **99.96% accuracy** with **87% precision** and **83% recall** for fraud detection.
- Visualized model performance using **confusion matrix** and **classification report**.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/fraud-detection.git
   ```
2. Navigate to the project directory:
   ```sh
   cd fraud-detection
   ```
3. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the main script to train and evaluate the model:
   ```sh
   python fraud_detection.py
   ```
2. View the results in the terminal or check the generated confusion matrix visualization.

## License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
