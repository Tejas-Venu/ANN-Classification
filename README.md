# 🧠 ANN Classification – Customer Churn Prediction  

This project implements an **Artificial Neural Network (ANN)** for **binary classification** to predict **customer churn** based on demographic and account information. The model was trained on the **Churn Modelling dataset** and deployed with a simple **Streamlit web app** for real-time predictions.  

## 🚀 Features  
- Preprocessing with **label encoding, one-hot encoding, and feature scaling**.  
- ANN built using **TensorFlow/Keras** with hidden layers and ReLU activation.  
- Model trained and saved as `model.h5` for reproducibility.  
- **Pickled encoders** (`label_encoder_gender.pkl`, `onehot_encoder_geo.pkl`, `scaler.pkl`) for consistent inference.  
- Interactive **Streamlit web app (`app.py`)** for making predictions.  
- Experiments and evaluation available in Jupyter notebooks.  

## 🛠 Tech Stack  
- **Language**: Python  
- **Libraries**: TensorFlow, Keras, Scikit-learn, Pandas, NumPy, Matplotlib, Streamlit  
- **Model**: Artificial Neural Network (ANN)  
- **Deployment**: Streamlit Web App  

## 📊 Dataset  
The dataset used is **Churn Modelling.csv**, which contains customer information such as:  
- Geography  
- Gender  
- Age  
- Balance  
- Credit score  
- Estimated salary  
- Tenure  
- Number of products  
- Whether the customer exited (target variable)  

## ⚡ Setup Instructions  
1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/ANN-Classification.git
   cd ANN-Classification
   ```

2. Create and activate a virtual environment:
   ```bash
    python -m venv venv
    source venv/bin/activate   # Linux/Mac
    venv\Scripts\activate      # Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## 📈Model Performance
- Training/validation loss and accuracy curves available in experiments.ipynb.
- Predictions and evaluation shown in predictions.ipynb.
- Accuracy metrics were calculated.
