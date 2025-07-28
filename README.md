# ANN_Churn_Project

Sure, Harsh! Here's a polished and visually engaging README for your **Artificial Neural Network Churn Prediction Project**, complete with icons and structure to make it pop on GitHub:

---

# 🔍 ANN Churn Prediction Project

Welcome to the **Customer Churn Prediction** project using an **Artificial Neural Network (ANN)**! This repository demonstrates how deep learning can be applied to predict customer churn in a banking dataset.

## 📁 Project Structure

```
📦 ANN_Churn_Project
 ┣ 📄 Churn_Modelling.csv
 ┣ 📄 app.py
 ┣ 📄 experiments.ipynb
 ┣ 📄 prediction.ipynb
 ┣ 📄 model.h5
 ┣ 📄 requirements.txt
 ┣ 📄 scaler.pkl
 ┣ 📄 label_encoder_gender.pkl
 ┣ 📄 onehot_en_geo.pkl
 ┗ 📄 README.md
```

## 🧠 Model Overview

- Built using **Keras** with **TensorFlow** backend
- Input features include demographics, account info, and activity
- Output: Binary classification (Churn or Not)
- Achieves high accuracy on test data

## 📊 Dataset

- Source: `Churn_Modelling.csv`
- Contains 10,000+ customer records
- Features include:
  - Age, Gender, Geography
  - Credit Score, Balance, Tenure
  - Number of Products, Has Credit Card, Is Active Member

## 🚀 How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/Harshjais12/ANN_Churn_Project.git
   cd ANN_Churn_Project
   ```

2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the prediction notebook or `app.py` for inference

## 🧪 Notebooks

- `experiments.ipynb`: Model training and evaluation
- `prediction.ipynb`: Load model and make predictions

## 🛠️ Tools & Libraries

- 🐍 Python
- 📘 Pandas, NumPy
- 🔍 Scikit-learn
- 🔮 TensorFlow, Keras
- 📊 Matplotlib, Seaborn

## 📦 Model Artifacts

- `model.h5`: Trained ANN model
- `scaler.pkl`: Feature scaler
- `label_encoder_gender.pkl`: Label encoder for gender
- `onehot_en_geo.pkl`: One-hot encoder for geography

## 📈 Performance

- Accuracy: ~85% on test set
- Precision/Recall: Balanced for churn detection

## 🙌 Author

Made with ❤️ by [Harsh Jaiswal](https://github.com/Harshjais12)

---

Would you like me to help you add this directly to your repo or customize it further with badges and visuals?
