# 🏥 Diabetes Prediction Model

Welcome to the **Diabetes Prediction Model** repository! This project is a machine learning-based system that predicts whether a patient is diabetic based on medical data. 🔬💉

## 📌 Project Overview
This project utilizes **supervised learning** techniques to classify individuals as diabetic or non-diabetic based on their medical history. It includes:
- Data preprocessing and exploratory data analysis (EDA).
- Machine learning model training and evaluation.
- Web-based deployment using Flask.

## 📂 Repository Structure
```
📦 Diabetes Prediction Model
├── Diabetes Prediction Model.ipynb    # Jupyter Notebook with ML model
├── diabetes.csv                       # Dataset file
├── trained_model.sav                  # Saved trained ML model
├── web.py                              # Flask web app for model deployment
```

## ⚙️ Installation & Setup
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Diabetes-Prediction.git
   cd Diabetes-Prediction
   ```

2. **Install required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
   Open **Diabetes Prediction Model.ipynb** and execute the cells to train and test the model.

## 📊 Dataset Details
- The dataset **diabetes.csv** contains medical records of patients.
- Features include **Glucose levels, BMI, Blood Pressure, Insulin, Age**, etc.
- The target variable indicates **whether the patient has diabetes (1) or not (0).**

## 🧠 Model Summary
- **Algorithm Used**: Random Forest Classifier (can be changed)
- **Input Features**: Medical parameters from dataset
- **Target Output**: Diabetic (1) or Non-Diabetic (0)
- **Performance Metrics**: Accuracy, Precision, Recall, F1-score

## 🚀 Running the Web Application
This project includes a **Flask-based web application** that allows users to input medical data and get predictions.

1. **Run the web app**:
   ```bash
   python web.py
   ```
2. **Access the web app**:
   Open `http://127.0.0.1:5000/` in your browser.
3. **Make Predictions**:
   - Enter medical details in the form.
   - Click the **Predict** button to see if the patient is diabetic.

## 📈 Results & Performance
- Achieved **high accuracy** on the test dataset.
- Used various ML techniques like feature scaling, hyperparameter tuning.
- Possible improvement: Use **Deep Learning (ANN/CNN)** for better results.

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

## 📬 Contact
For any queries, reach out via GitHub issues or email me at [hanumeshgupta2907@gmail.com](mailto:hanumeshgupta2907@gmail.com).
