# 🧠 Brain Stroke Prediction with AI

## 🚀 Introduction

Strokes are among the leading causes of long-term disability and mortality worldwide. Early detection is crucial for effective intervention and improved patient outcomes. This project leverages machine learning algorithms to predict the risk of stroke based on various health parameters, aiming to assist healthcare professionals in proactive decision-making.

## 📂 Table of Contents

- [Introduction](#-introduction)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Dataset](#-dataset)
- [Model Training](#-model-training)
- [Evaluation](#-evaluation)
- [Future Work](#-future-work)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Features

- 🔍 **Predictive Analysis**: Estimates the likelihood of a stroke based on user input.
- 📊 **Risk Factor Evaluation**: Analyzes key risk factors such as age, medical history, and lifestyle choices.
- 🧠 **Machine Learning Models**:
  - 🤖 Artificial Neural Networks (ANN)
  - 🌳 Decision Trees
  - 📈 Naive Bayes
- 🌐 **Web Application**: User-friendly interface for easy interaction and prediction.

## 🛠️ Technologies Used

- **Programming Language**: 🐍 Python
- **Machine Learning Libraries**: TensorFlow, scikit-learn
- **Web Framework**: Flask
- **Database**: SQLite
- **Data Visualization**: Matplotlib, Seaborn

## 🛠️ Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/bhaveshpatil093/Brain-Stroke-Prediction-with-AI.git
   cd Brain-Stroke-Prediction-with-AI
   ```

2. **Create and activate a virtual environment**:

   ```bash
   python3 -m venv env
   source env/bin/activate
   # On Windows, use 'env\Scripts\activate'
   ```
   
3. **Install the required dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up the database**:

   ```bash
   python initialize_database.py
   ```
   
## ▶️ Usage
After installation, you can run the application locally:

1. **Start the Flask application**:

   ```bash
   flask run
   ```
   
2. **Access the application**:

Open your web browser and navigate to `http://127.0.0.1:5000/`.

3. **Use the application**:

- Input the required health parameters.
- Click on the 'Predict' button to receive the stroke risk assessment

## 📄 Dataset
The model is trained on the Healthcare Dataset Stroke Data, which includes the following features:

- **id**: Unique identifier
- **gender**: Gender of the patient
- **age**: Age of the patient
- **hypertension**: 0 if no hypertension, 1 if hypertension is present
- **heart_disease**: 0 if no heart disease, 1 if heart disease is present
- **ever_married**: Marital status
- **work_type**: Type of occupation
- **Residence_type**: Urban or Rural
- **avg_glucose_level**: Average glucose level in blood
- **bmi**: Body Mass Index
- **smoking_status**: Smoking status
- **stroke**: 1 if the patient had a stroke, 0 otherwise

## 🧠 Model Training
The project explores three machine-learning algorithms:

- **Artificial Neural Networks (ANN)**: Implemented using TensorFlow.
- **Decision Trees**: Implemented using scikit-learn.
- **Naive Bayes**: Implemented using scikit-learn.

**Training Process**:

1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
2. **Model Training**: Each algorithm is trained on the preprocessed data.
3. **Validation**: Models are validated using cross-validation techniques.

## 📊 Evaluation
The models are evaluated based on the following metrics:

- **Accuracy**: Proportion of correctly predicted instances.
- **Precision**: Proportion of correct identifications.
- **Recall**: Proportion of actual positives that were identified correctly.
- **F1 Score**: Harmonic mean of precision and recall.

**Results**:

- **ANN**: Accuracy - 95%, Precision - 94%, Recall - 96%, F1 Score - 95%
- **Decision Trees**: Accuracy - 92%, Precision - 90%, Recall - 93%, F1 Score - 91%
- **Naive Bayes**: Accuracy - 88%, Precision - 85%, Recall - 89%, F1 Score - 87%

*Note: These results are hypothetical and should be updated based on actual model performance.*

## 🔮 Future Work
- **Real-Time Data Integration**: Incorporate real-time patient data for dynamic risk assessment.
- **Model Optimization**: Explore advanced algorithms and hyperparameter tuning to improve accuracy.
- **Mobile Application**: Develop a mobile app to increase user accessibility.
- **Clinical Trials**: Collaborate with healthcare institutions for real-world testing and validation.

## 🤝 Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make and commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.
   
Please ensure your code adheres to the project's coding standards and includes appropriate tests.

## 📝 License
This project is licensed under the MIT License. See the `LICENSE` file for details.

**We are committed to advancing stroke prediction and contributing to proactive healthcare solutions!**
