# Car Price Prediction: End-to-End ML Project 🚗

This repository contains the work completed during the 5-day intensive workshop on **"Machine Learning: From Basics to Deployment"** conducted by **Innomatics Research Labs**.

The project focuses on predicting car prices based on various features using a Linear Regression model, deployed as a functional web application via Streamlit.

## 📌 Project Overview
The goal of this project was to understand the full machine learning lifecycle:
1.  **Data Acquisition:** Working with raw vehicle data.
2.  **Exploratory Data Analysis (EDA):** Visualizing trends and correlations.
3.  **Data Preprocessing:** Cleaning and feature engineering.
4.  **Model Building:** Training a Linear Regression model.
5.  **Deployment:** Creating an interactive UI for real-time predictions.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Deployment:** Streamlit
* **Environment:** Jupyter Notebook / VS Code

## 📊 The ML Process
![ML Process](ml_process.png)
*Visualizing the workflow from data ingestion to model deployment.*

## 🧹 Key Insights from Data Cleaning
During the EDA phase, significant effort was put into data cleaning to ensure model accuracy.
![Data Cleaning](Data_Cleaning.png)

## 🚀 How to Run the App
To run the Streamlit app locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Yogi1107/Innomatics-Workshop.git](https://github.com/Yogi1107/Innomatics-Workshop.git)
   cd Innomatics-Workshop
   ```

2. Install dependencies:

```bash
pip install -r requirements.txt
(Note: Ensure you create a requirements.txt file with streamlit, pandas, and scikit-learn)
```

3. Launch the app:

```bash
streamlit run app.py
```

📂 Repository Structure
Car Price Prediction.ipynb: The main notebook containing analysis and model training.
app.py: The Streamlit application script.
linear_model.pkl: The serialized trained model.
car_data.xlsx: The raw dataset used for training.
feature_importance.xlsx: Analysis of which features impact price the most.


Workshop conducted by: Innomatics Research Labs 
Developed by: Yogiraj Bhilare

---

### **One quick suggestion:**
To make your repository truly "one-click" ready for others, I recommend creating a small text file named **`requirements.txt`** in your repo with these three lines:
```text
streamlit
pandas
scikit-learn
openpyxl
```
