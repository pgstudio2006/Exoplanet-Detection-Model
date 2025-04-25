
# 🌌 Exoplanet Detection Using Light Curve Data

This project explores the use of **Machine Learning**—specifically **CNN** and **Transformer-based models**—for the detection of exoplanets using light curve data collected by NASA's **Kepler** and **TESS** space telescopes.

## 📚 Overview

Exoplanet detection is one of the most exciting frontiers in modern astronomy. By analyzing subtle dips in a star’s brightness (light curves), we aim to identify the presence of exoplanets transiting across the star.

This repository contains:
- A complete ML pipeline for preprocessing, training, and evaluation
- Implementation of both CNN and Transformer models
- Performance comparisons and evaluation metrics
- A dashboard for visualizing predictions

---

## 🎯 Objective

- Preprocess light curve data for model training.
- Train and fine-tune a **Convolutional Neural Network (CNN)** based on Google’s baseline model.
- Design and implement a **custom Transformer-based model** to capture long-term dependencies.
- Evaluate models using metrics like **Precision**, **Recall**, **F1-Score**, and **Accuracy**.
- Build a dashboard for result visualization.

---

## 🛠 Workflow

1. **Data Preprocessing**
   - Remove noise and outliers
   - Normalize flux values
   - Format input for model compatibility

2. **Modeling**
   - CNN: Fine-tuned for pattern recognition in light curves
   - Transformer: Custom architecture using attention for sequential data

3. **Evaluation**
   - Compared using standard metrics: precision, recall, F1-score, accuracy

4. **Deployment**
   - Interactive dashboard for insights and visualizations

---

## 📊 Datasets

- **Kepler** and **TESS** light curve data from NASA
- Features: Time vs Flux (brightness)
- Challenges:
  - Noisy data
  - Few positive samples (imbalanced dataset)

---

## ⚙️ Performance Summary

| Metric      | CNN Model     | Transformer Model | Traditional Methods |
|-------------|---------------|-------------------|---------------------|
| Precision   | High          | High              | Lower               |
| Recall      | High          | High              | Lower               |
| F1-Score    | Improved      | Improved          | Less optimal        |
| Accuracy    | ~92%          | ~92%              | ~85%                |

---

## 🚧 Challenges

- Handling noisy and imbalanced data
- Stabilizing the Transformer model during training
- Generalizing to unseen light curves

---

## 🚀 Conclusion

This project showcases how Machine Learning can dramatically accelerate the search for exoplanets, blending astrophysics with cutting-edge AI to expand our understanding of the universe.

---

## 👨‍💻 Contributors

- **Parthrajsinh Gohil** (KU2407U067)  
- **Shailja Jagani** (KU2407U492)  
- **Vraj Savani** (KU2407U702)  

---
