# Explainable_AI_for_Multi_Class_Chest_X-Ray_Diagnosis

##  Overview

A deep learning-based medical imaging system for detecting chest diseases such as **Pneumonia** and **Tuberculosis** from X-ray images. The project implements an end-to-end workflow including preprocessing, CNN model training, evaluation, and explainable AI visualization using **Grad-CAM**.

---

## Features

* Built a custom **CNN architecture** using TensorFlow/Keras for chest X-ray classification.
* Applied **data augmentation** techniques to improve model generalization.
* Used **Batch Normalization, Dropout, and L2 Regularization** for robust training.
* Handled dataset imbalance using **class weighting**.
* Integrated training optimization methods:

  * Early Stopping
  * ReduceLROnPlateau
  * Model Checkpointing
* Evaluated performance using:

  * Confusion Matrix
  * Classification Report
  * Accuracy/Loss Curves
* Implemented **Grad-CAM Explainability** for visual interpretation of predictions.
* Saved trained models for deployment and inference.

---

## Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy & Pandas
* Matplotlib & Seaborn
* Scikit-learn

---

## Highlights

* Developed a complete medical image classification pipeline.
* Improved reliability of predictions using explainable AI techniques.
* Focused on healthcare-oriented computer vision applications.

---

## Future Improvements

* Deploy the model using Flask/Streamlit.
* Extend support for additional chest diseases.
* Integrate transfer learning models such as ResNet or EfficientNet.
* Improve explainability using advanced visualization methods.

---
