🌍 Earthquake Damage Detection
Project Overview

This project focuses on automatically assessing earthquake damage using deep learning and unsupervised learning techniques. It first uses MobileNetV2 to determine whether a building is damaged or not. If damage is detected, the system further analyzes the image to estimate the severity level using clustering methods.

Instead of relying only on manual inspection, this approach helps in faster and more consistent damage evaluation, which can be useful in disaster response scenarios.

Technologies Used
Python
TensorFlow & Keras
MobileNetV2
Google Colab
OpenCV
NumPy
Matplotlib
Scikit-learn
System Workflow

Input Image
↓
MobileNetV2
↓
Damaged / No Damage

If No Damage → Output: No Damage

If Damaged →
↓
Feature Extraction (128-dimensional dense features)
↓
StandardScaler (normalization)
↓
K-Means Clustering (4 groups)
↓
Damage Level Prediction:

Low Damage
Moderate Damage
High Damage
Severe Damage

Methodology
Collect and organize the dataset
Preprocess and prepare images for training
Train MobileNetV2 for binary classification (damaged vs undamaged)
Predict whether a building is damaged
Extract meaningful features from damaged images
Normalize features for better clustering
Apply K-Means to group damage severity levels
Interpret clusters as damage categories
Evaluate model performance
Damage Categories
No Damage
Low Damage
Moderate Damage
High Damage
Severe Damage
Author

Aditi Chand
