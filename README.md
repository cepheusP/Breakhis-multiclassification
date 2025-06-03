other codes link: https://drive.google.com/file/d/1_o0R8piLugM-TN1DdX9n6nHhXzA9QOsO/view?usp=sharing
# Utilization of Machine Learning and Deep Learning Techniques for Image Classification in BreaKHis  
**Authors:** Ahmed Tamer, Pınar Yılmaz  

## 🧠 Project Overview

Breast cancer is one of the most prevalent causes of cancer-related deaths among women globally. While histopathological image analysis remains the diagnostic gold standard, the process is labor-intensive and subject to human error. This study aims to **accelerate breast cancer diagnosis** by leveraging both **Machine Learning (ML)** and **Deep Learning (DL)** techniques to classify histopathology images from the [BreaKHis dataset](https://www.kaggle.com/datasets/ambarish/breakhis).

The performance of several state-of-the-art deep learning architectures was compared to that of traditional machine learning models using handcrafted features extracted from segmented images.

## 📁 What’s Included

We have uploaded all relevant **Jupyter Notebooks** used in this project for reproducibility and further development.

You will find notebooks covering:
- Preprocessing and segmentation of histopathological images
- Feature extraction using PFTAS and GLCM
- Classification using ML models (SVM, Random Forest, K-NN, XGBoost)
- Deep learning model training and evaluation (InceptionResNetV2, ResNet152V2, InceptionV3, VGG16, Xception)
- Performance analysis and result visualization

## 🧪 Summary of Results

| Model                         | Accuracy (at 200x) |
|------------------------------|--------------------|
| **InceptionResNetV2**        | **90%**            |
| XGBoost (with PFTAS features)| 87%                |
| Other DL models              | 80–89%             |
| Other ML models              | ~80–85%            |

## 🔍 Key Insights

- **Deep Learning** outperforms traditional methods, with **InceptionResNetV2** achieving the highest accuracy.
- **XGBoost** combined with **PFTAS** features offers a strong alternative, highlighting the relevance of optimized traditional ML techniques.
- Results indicate the potential for **hybrid approaches** in CAD (Computer-Aided Diagnosis) systems.

## 📚 Keywords

`Breast cancer`, `Histopathology`, `Image classification`, `Machine Learning`, `Deep Learning`, `BreaKHis`, `Medical imaging`, `PFTAS`, `XGBoost`, `CNN`

