Tumor Detection
Overview

Machine learning project to classify tumors as Malignant (M) or Benign (B) using the Breast Cancer dataset.
Performed EDA, preprocessing, Random Forest training, and evaluation in Jupyter Notebook.

Steps

Cleaned dataset (removed id, extra columns, handled missing values)

EDA: count plot, correlation heatmap, feature analysis

Preprocessing: encoding, scaling, train-test split

Trained Random Forest Classifier

Evaluated with accuracy, confusion matrix, ROC curve

Saved model with joblib

Results

Accuracy: 95–98%

ROC-AUC: ~0.99

Random Forest performed strongly in tumor classification

Run
git clone https://github.com/your-username/Tumor-Detection.git
cd Tumor-Detection
pip install -r requirements.txt
jupyter notebook Tumor_Detection.ipynb
