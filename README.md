# Earthquake Damage Detection

## Project Overview
This project performs automated earthquake damage assessment using deep learning and unsupervised learning techniques. MobileNetV2 is used to detect whether a building is damaged or undamaged. For damaged buildings, feature extraction and K-Means clustering are used to classify the damage severity.

## Technologies Used
- Python
- TensorFlow
- Keras
- MobileNetV2
- Google Colab
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

## System Workflow

Input Image
↓
MobileNetV2
↓
Damaged / No Damage
↓
If No Damage → No Damage

If Damaged:
↓
Feature Extraction (Dense Layer - 128 Features)
↓
StandardScaler
↓
K-Means Clustering (4 Clusters)
↓
Low Damage
Moderate Damage
High Damage
Severe Damage

## Methodology
1. Data Collection
2. Data Preprocessing
3. MobileNetV2 Model Training
4. Damage Detection (Damaged / Undamaged)
5. Feature Extraction from Damaged Images
6. Feature Normalization using StandardScaler
7. K-Means Clustering for Damage Severity Classification
8. Damage Assessment
9. Performance Evaluation

## Damage Categories
- No Damage
- Low Damage
- Moderate Damage
- High Damage
- Severe Damage

## Author
Aditi Chand
