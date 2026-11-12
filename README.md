# 📊 Customer Churn Prediction using Deep Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-ANN-success.svg)

## 📝 Overview
This project features a Deep Learning model built with **TensorFlow and Keras** to predict customer churn. By analyzing customer behavior metrics such as tenure, monthly charges, contract length, and support calls, this Artificial Neural Network (ANN) identifies the probability of a customer canceling their service. 

Identifying at-risk customers early empowers businesses to take proactive steps to improve retention and overall customer satisfaction.

## ✨ Features
- **Custom Synthetic Dataset:** Dynamically generates a realistic 1,000-row dataset mimicking telecom/subscription customer behavior.
- **Robust Preprocessing:** Handles feature scaling using Scikit-Learn's `StandardScaler` for optimized neural network performance.
- **Deep Learning Architecture:** Implements a multi-layer Artificial Neural Network (Input, Hidden layers with ReLU, and Output layer with Sigmoid).
- **Real-Time Predictions:** Accepts new customer profiles and instantly outputs a churn probability percentage.
- **Training Visualization:** Automatically plots training and validation accuracy/loss curves using Matplotlib.

## ⚙️ Tech Stack
- **Python** 
- **TensorFlow & Keras** (Deep Learning framework)
- **Pandas & NumPy** (Data manipulation and dataset generation)
- **Scikit-Learn** (Train-test splitting and feature scaling)
- **Matplotlib** (Data visualization)

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/thuvara23/customer-churn-ann.git
   cd customer-churn-ann
   ```

2. **Install the required dependencies:**
   Make sure you have Python installed. Then, run the following command to install the required libraries:
   ```bash
   pip install numpy pandas tensorflow scikit-learn matplotlib
   ```

## 💻 Usage

Run the main Python script to generate the dataset, train the model, and view the visualizations:

```bash
python chum.py
```

**What happens when you run the script?**
1. A synthetic dataset is generated and previewed in the console.
2. The data is split into training (80%) and testing (20%) sets and scaled.
3. The ANN model trains for 20 epochs, displaying progress.
4. The model evaluates on the test set, outputting an overall Accuracy Score.
5. A sample "New Customer" profile is evaluated, predicting their likelihood to churn.
6. A Matplotlib window opens displaying the Training Accuracy and Loss graphs.

## 📂 File Structure
- `chum.py`: The main Python script containing data generation, preprocessing, model building, and visualization logic.

## 🧠 Future Improvements
- Test the model on a real-world dataset (e.g., the Telco Customer Churn dataset from Kaggle).
- Implement Hyperparameter tuning (GridSearch or Keras Tuner) to optimize layer sizes and learning rates.
- Build a front-end web interface using Streamlit or Gradio to make predictions interactively.
