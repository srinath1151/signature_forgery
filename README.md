# ✍️ Signature Forgery Detection using Siamese Neural Network

This project is aimed at detecting forged signatures using a Siamese Neural Network trained on the CEDAR dataset. It leverages deep learning techniques to compare genuine and forged signatures and classify them effectively.

---

## 🚀 Project Overview

- **Goal**: Classify whether a signature is genuine or forged.
- **Approach**: Siamese Neural Network to compare pairs of signature images.
- **Dataset**: [CEDAR Signature Dataset](http://www.iapr-tc11.org/mediawiki/index.php/CEDAR_Signature_Database)

---
## 📊 Evaluation Metrics

The model is evaluated using the following metrics:

- ✅ Accuracy  
- ✅ Precision  
- ✅ Recall  
- ✅ F1 Score

These metrics help ensure the model performs well even on imbalanced data (e.g., few forged samples compared to genuine).

---

## 🔍 Tools & Libraries Used

- Python 3.11+
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Streamlit (for UI)

---

## 💡 Deployment Plan

A **Streamlit web application** is in development to provide a user-friendly interface where users can upload two signature images and get real-time predictions.

---

## 📈 Future Improvements

- Improve model robustness with data augmentation and larger datasets.
- Experiment with different deep learning architectures (e.g., Triplet Loss, Contrastive Loss with ResNet).
- Add signature localization/cropping using object detection.
- Deploy via Docker or Hugging Face Spaces.

---
