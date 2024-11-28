Anomaly Detection in Clinical Data using Isolation Forest

Overview
This project focuses on detecting anomalies in medical datasets using the Isolation Forest algorithm. The primary objective is to identify irregularities in clinical data for potential use in emergency departments. The dataset includes labeled samples of normal and anomalous data points, and the Isolation Forest is trained and evaluated to distinguish between these classes.

Key Features
Implements Isolation Forest for anomaly detection.
Evaluates performance using precision, recall, and f1-score.
Incorporates preprocessing techniques like scaling and oversampling (SMOTE).
Provides a pipeline for hyperparameter tuning and evaluation.

Dataset
The dataset used in this project is the Medical Anomaly Detection Dataset. It consists of labeled examples of normal and anomalous data points.

Train Folder: Contains "good" examples for training.
Test Folder: Contains both "good" and "bad" examples for evaluation.
Ground Truth Folder: Includes labeled anomalies for validation.

Results
Training Set Evaluation
Metric	Normal (0)	Anomaly (1)	Overall
Precision	0.58	0.48	-
Recall	0.91	0.11	-
F1-Score	0.71	0.18	-
Accuracy	-	-	0.57
Test Set Evaluation
Metric	Normal (0)	Anomaly (1)	Overall
Precision	0.74	0.00	-
Recall	0.82	0.00	-
F1-Score	0.78	0.00	-
Accuracy	-	-	0.64

Technologies and Libraries
Python
scikit-learn: For machine learning and evaluation.
imbalanced-learn: For oversampling (SMOTE).
matplotlib: For visualization.
numpy: For numerical computation.
pandas: For data manipulation.


Installation
Clone the repository:
git clone https://github.com/your-username/anomaly-detection-clinical.git
cd anomaly-detection-clinical
Set up a virtual environment (optional but recommended):


python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
Install dependencies:

pip install -r requirements.txt
Download the dataset from Kaggle and place it in the appropriate folder.