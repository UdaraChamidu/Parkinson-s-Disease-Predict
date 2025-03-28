# Parkinson's Disease Classification Model

This repository contains a machine learning model for classifying Parkinson's Disease using the **K-Nearest Neighbors (KNN) algorithm**.

## 📌 Project Overview
Parkinson’s disease is a neurodegenerative disorder affecting movement. Early diagnosis is crucial for managing the disease effectively. This project applies **KNN** to classify patients based on biomedical voice measurements.

## 📊 Dataset
- The dataset is stored in `data.csv`.
- It contains multiple biomedical voice measurements.
- Features include frequency variations, amplitude, and jitter measurements.

## 🛠️ Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/parkinsons-classification.git
   cd parkinsons-classification
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook 2021E049_Lab01.ipynb
   ```

## 🔍 Model Implementation
- The dataset is loaded and preprocessed.
- Features are scaled using **StandardScaler**.
- The model is trained using **K-Nearest Neighbors (KNN)**.
- Cross-validation is used to evaluate model performance.

## 📈 Results & Evaluation
- The model initially showed **100% accuracy**, indicating possible **overfitting**.
- Cross-validation scores suggest an average accuracy of **98.97%**.
- Regularization techniques and feature selection are suggested to improve generalization.

## 🚀 Future Improvements
- Implement feature selection to remove irrelevant data.
- Tune hyperparameters for better generalization.
- Compare with other ML models (SVM, RandomForest).

## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Feel free to open issues or pull requests to improve this model!

---
**Author:** Udara Chamidu

