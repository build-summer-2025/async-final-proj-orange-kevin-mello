# async-final-proj-orange-kevin-mello
Breast Cancer Final Proj




Breast Cancer Awareness – Machine Learning Project Overview

This project demonstrates the application of Machine Learning techniques, specifically the Random Forest algorithm, to predict breast cancer classifications. It also emphasizes Breast Cancer Awareness by presenting results in an intuitive way using a Confusion Matrix visualization and themed graphics.

Key Components

Machine Learning: Leveraging classification algorithms for medical diagnosis.

Random Forest: A powerful ensemble method for improved accuracy and robustness.

Confusion Matrix: A performance metric visualization for classification models.

Awareness Design: Breast cancer awareness elements integrated into visuals.

Features

Trains a Random Forest Classifier on a breast cancer dataset.

Evaluates the model using:

Accuracy

Precision

Recall

F1 Score

Displays results with a confusion matrix.

Includes breast cancer awareness themed graphics for presentations.

Example Results

Accuracy: 96.49%

True Positives (TP): Correctly predicted malignant tumors.

False Negatives (FN): Missed malignant tumors (critical to minimize).

True Negatives (TN): Correctly predicted benign tumors.

False Positives (FP): Incorrectly predicted malignant tumors.

📂 Project Structure breast-cancer-awareness-ml/ │ ├── data/ │ └── breast_cancer.csv # Dataset │ ├── images/ │ ├── confusion_matrix.png # Confusion matrix awareness image │ ├── thank_you.png # Thank you image (ML + Awareness) │ ├── notebooks/ │ └── breast_cancer_analysis.ipynb # Jupyter notebook for model training │ ├── README.md # Project documentation └── requirements.txt # Dependencies

🛠️ Installation git clone https://github.com/yourusername/breast-cancer-awareness-ml.git cd breast-cancer-awareness-ml pip install -r requirements.txt

Usage

Run the notebook or script to train and evaluate the model:

jupyter notebook notebooks/breast_cancer_analysis.ipynb

Visuals

Confusion Matrix with Breast Cancer Awareness Theme

Thank You Graphic (Machine Learning + Random Forest + Awareness)

Why This Matters

Early detection of breast cancer can save lives. Combining AI-powered solutions with awareness campaigns can help bridge the gap between technology and health.
