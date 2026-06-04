# -Credit-Card-Fraud-Dete-ction-System
Project Overview

This project focuses on analyzing credit card transaction data to identify fraudulent activities, understand transaction patterns, and assess transaction risk levels. The project uses data preprocessing, exploratory data analysis (EDA), visualization, and Machine Learning techniques to gain insights into fraud detection.

The dataset used is the popular Credit Card Fraud Detection dataset from Kaggle.

🎯 Objectives
Load and analyze credit card transaction data
Clean and preprocess the dataset
Perform exploratory data analysis (EDA)
Visualize fraud and normal transaction patterns
Categorize transactions based on risk levels
Build a Linear Regression model for transaction amount prediction
Evaluate model performance
Generate interactive dashboards
Export the cleaned dataset
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Scikit-Learn
KaggleHub
Google Colab
📂 Dataset Information

Dataset: Credit Card Fraud Detection Dataset

The dataset contains anonymized credit card transactions made by European cardholders.

Features
Feature	Description
Time	Seconds elapsed between transactions
V1 - V28	Anonymized transaction features
Amount	Transaction amount
Class	Transaction class (0 = Normal, 1 = Fraud)

📂 Dataset Source

This project uses the Credit Card Fraud Detection Dataset from Kaggle.

Dataset Link:

Credit Card Fraud Detection Dataset (Kaggle)

Dataset Details
Total Transactions: 284,807
Fraud Transactions: 492
Normal Transactions: 284,315
Fraud Rate: 0.172%
Features: Time, Amount, V1–V28 (PCA-transformed features), Class
Source: Machine Learning Group, Université Libre de Bruxelles (ULB) and Worldline.

⚙️ Project Workflow
1. Dataset Loading
Downloaded dataset directly from Kaggle using KaggleHub.
Loaded the CSV file into a Pandas DataFrame.
2. Data Preprocessing
Checked dataset structure and information.
Identified missing values.
Removed duplicate records.
Generated descriptive statistics.
3. Exploratory Data Analysis (EDA)

Performed analysis on:

Fraud vs Normal Transaction Distribution
Transaction Amount Distribution
Transaction Amount Boxplots
Fraud vs Transaction Amount Comparison
Time vs Transaction Amount Relationship
Correlation Heatmap
4. Risk Analysis

Transactions were categorized into risk levels based on amount:

Transaction Amount	Risk Level
Less than ₹100	Low Risk
₹100 - ₹999	Medium Risk
₹1000 and above	High Risk
5. Machine Learning Model

Implemented a Linear Regression Model.

Input Feature
Time
Target Variable
Amount
6. Model Evaluation

Performance was measured using:

R² Score
Mean Squared Error (MSE)
7. Visualization Dashboard

Interactive dashboards were created using Plotly:

Fraud vs Normal Transactions (Pie Chart)
Transaction Amount Distribution
Time vs Amount Scatter Plot
Risk Level Distribution
8. Fraud Investigation

Filtered and analyzed:

High-Risk Fraudulent Transactions
Fraud transaction patterns
Risk-level distribution among fraudulent transactions
9. Data Export

The cleaned dataset was exported as:

cleaned_creditcard_dataset.csv
📊 Visualizations Included
Static Visualizations
Count Plot of Fraud vs Normal Transactions
Histogram of Transaction Amounts
Amount Boxplots
Fraud vs Amount Analysis
Time vs Amount Scatter Plot
Correlation Heatmap
Risk Level Distribution
Interactive Visualizations
Pie Chart
Histogram
Scatter Plot
Bar Chart
📈 Key Insights
Fraudulent transactions represent only a very small portion of total transactions.
Most transactions fall into the Low Risk category.
Transaction amount distributions are highly skewed.
Fraudulent transactions can occur across different transaction amounts.
Risk categorization helps identify transactions that require additional review.
Data visualization provides a clear understanding of transaction behavior.
🚀 How to Run the Project
Clone the Repository
git clone https://github.com/your-username/credit-card-fraud-detection.git

cd credit-card-fraud-detection
Install Required Libraries
pip install pandas numpy matplotlib seaborn plotly scikit-learn kagglehub
Run the Program
python credit_card_fraud_detection.py

Or run the notebook directly in Google Colab.

📁 Project Structure
📦 Credit-Card-Fraud-Detection
│
├── credit_card_fraud_detection.ipynb
├── cleaned_creditcard_dataset.csv
├── README.md
│
└── visualizations/
    ├── fraud_distribution.png
    ├── amount_distribution.png
    ├── heatmap.png
    └── risk_analysis.png


📊 Sample Output
<img width="567" height="473" alt="image" src="https://github.com/user-attachments/assets/d0572141-d6b2-4152-9d17-9b03118fdb35" />
<img width="849" height="435" alt="image" src="https://github.com/user-attachments/assets/b703621e-31f8-4c66-8e74-e7161a9742f3" />
<img width="713" height="456" alt="image" src="https://github.com/user-attachments/assets/cb886ec6-0d2f-40b0-936d-ff0c9333bc4b" />
<img width="1153" height="511" alt="image" src="https://github.com/user-attachments/assets/04691a71-fe2f-4ba8-9254-b719529b2481" />
<img width="645" height="468" alt="image" src="https://github.com/user-attachments/assets/5182001e-f5ee-4da5-b657-ed35335e3f56" />
<img width="1147" height="468" alt="image" src="https://github.com/user-attachments/assets/d6b2f2e6-d2ca-4e1d-aa7a-326025f52dcb" />
<img width="1123" height="484" alt="image" src="https://github.com/user-attachments/assets/f6130499-5dce-4d9a-819c-c7c36436fcb7" />


The project generates:

Fraud detection statistics
Risk level analysis
Machine Learning predictions
Interactive dashboards
Transaction insights
Cleaned dataset export

👨‍💻 Author

Veeramanikandan.S

Student Project – Credit Card Fraud Detection and Transaction Risk Analysis using Python, Data Analytics, and Machine Learning.
