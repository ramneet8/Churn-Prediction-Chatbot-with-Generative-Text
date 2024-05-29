# Churn-Prediction-Chatbot-with-Generative-Text
About Develop a chatbot that leverages customer data analysis and generative text to proactively reduce customer churn for a telecom company.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Detailed Steps](#detailed-steps)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to develop a chatbot that leverages customer data analysis and generative text to proactively reduce customer churn for a telecom company. The chatbot predicts the likelihood of a customer churning and generates personalized messages to retain the customer.

## Features
- Predict customer churn using Random Forest machine learning model.
- Generate personalized messages using GPT-3.5-Turbo.
- Integrate prediction and generative text models into a chatbot interface.

## Dataset
The dataset used in this project is the Telco Customer Churn Dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Telco+Customer+Churn).

### Dataset Columns:
- `Call Failure`: Number of call failures.
- `Complains`: Binary (0: No complaint, 1: Complaint).
- `Subscription Length`: Total months of subscription.
- `Charge Amount`: Ordinal attribute (0: Lowest amount, 9: Highest amount).
- `Seconds of Use`: Total seconds of calls.
- `Frequency of Use`: Total number of calls.
- `Frequency of SMS`: Total number of text messages.
- `Distinct Called Numbers`: Total number of distinct phone calls.
- `Age Group`: Ordinal attribute (1: Younger age, 5: Older age).
- `Tariff Plan`: Binary (1: Pay as you go, 2: Contractual).
- `Status`: Binary (1: Active, 2: Non-active).
- `Churn`: Binary (1: Churn, 0: Non-churn) - Class label.
- `Customer Value`: The calculated value of the customer.

## Requirements
- Python 3.7+
- pandas
- scikit-learn
- openai
- textstat
- joblib

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Ramneet-08/Churn-Prediction-Chatbot-with-Generative-Text
   cd Churn-Prediction-Chatbot-with-Generative-Text

## Install the required packages:
pip install -r requirements.txt

## Set up OpenAI API key:
Obtain an API key from OpenAI.

## Set the API key as an environment variable:
export OPENAI_API_KEY='your-api-key'

1. Data Preprocessing
Load and preprocess the dataset.
Handle missing values and convert categorical variables.
2. Feature Engineering
Create new features to enhance model performance.
3. Model Training
Train a churn prediction model (e.g., RandomForestClassifier) and evaluate its effectiveness using metrics like accuracy and F1-score.
4. Generative Text Integration
Use GPT-3 to craft personalized messages based on customer profiles and churn risk.
5. Chatbot Development
Develop a basic chatbot interface that interacts with the churn prediction and generative text models.
6. Evaluation
Assess the model's accuracy.
Evaluate the quality (clarity, persuasion) and personalization of generated messages.
Consider the overall user experience and ease of interaction with the chatbot prototype.


License
This project is licensed under the MIT License - see the LICENSE file for detail