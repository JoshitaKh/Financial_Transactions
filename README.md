# 📊Financial Transaction Data Analysis Notebook
_End-to-end data analytics project using Kaggle financial transaction dataset_

## 🚀 Project Overview

## Data Source and Description:
The dataset used for this analysis is a synthetic but realistic financial transaction dataset obtained from Kaggle. It contains information about customer transactions, card details, user demographics, merchant categories, and fraud labels. The data is synthetic but created to look like real banking activity from the 2010s.

Overall, the dataset provides a rich, multi-table structure that enables a wide range of analytical goals, including analysing spending trends, understanding customer characteristics, exploring card usage patterns, evaluating merchant categories, and identifying abnormal or high-risk transactions.

## Overview of the data:
This section provides a clear snapshot of the dataset, outlining the key tables it contains and the main attributes within each. This overview helps establish the structure of the data before moving into cleaning and analysis.

Transaction data(transactions_data.csv): Detailed transaction records including amounts, timestamps, and merchant details.

transaction_id: Unique transaction identifier
date: Date of transaction
client_id: Link to the user who made the transaction
card_id: Link to card used
amount: Amount spent
use_chip: Shows if the transaction used a chip card (in-person) or was online.
merchant_id: Link to merchant where card has been used
merchant_city: City of the merchant where customer used the card
merchant_state: State of the Merchant where customer used the card
Zip: Zipcode of the merchant
mcc: Link to Merchant category code
errors: Type of Error while making a transaction
Card Information(cards_dat.csv): Stores information about debit and credit card of customers

card_id: Unique card identifier
client_id: Link to the user who holds the card
card_brand: Records the brand of the card
card_number: Records the card number
expiry_date: Expiry date of the card
CVV: CVV number on the car
num_cards_issued: number of cards issued
has_chip: This shows whether the card has a chip or not
credit_limit: Credit limit of the card
acc_open_date: Account opening date
year_pin_last_changed: Records the year in which PIN was last changed
card_on_dark_web: Indicates whether the card number appears in the dark web marketplaces
Merchant Category Codes(mcc_codes.json): Merchant Category codes- Standard classification codes for business.

mcc: Unique merchant category code
description: Type of Merchant
Fraud Labels(train_fraud_labels.json): Holds Binary classification labels for transactions, which indicate legitimate or fraudulent transactions.

transaction_id: Unique transaction identifier
label: Fraud indicator
User Data(users_data): Records customer details

user_id: Unique user identifier
current_age: User's age
retirement_age: User's retirement age
birth_year: User's year of birth
gender: Gender of the User
address: User's address
latitude: Location latitude
longitude: Location longitude
per_capita_income: Per capita income of the customer
yearly_income: Yearly income of the customer
total_debt: Total debt of the customer
credit_score: Credit score of the customer
num_credit_cards: Number of credit cards a customer holds

##Overall Goal of the Analysis:
The goal of this financial transaction data analysis is to integrate and examine customer, card, merchant, and transaction information to gain a comprehensive understanding of banking behaviour across the 2010s. This includes identifying spending patterns, customer segments, and card-usage trends, as well as detecting unusual or potentially fraudulent activities. By developing a clean, unified dataset and conducting exploratory and focused analyses, the goal is to generate insights that support improved customer profiling, product design, risk management, and informed decision-making within the financial institution.

## 📁 Repository Structure

Financial_Transactions_Analysis/
│
├── data/
│ ├── raw/ # Original dataset (not uploaded)
│ └── processed/ # Cleaned and transformed datasets
│
├── notebooks/
│ └── Financial_Transactions_Analysis.ipynb # Main analysis notebook
│
├── scripts/
│ └── data_cleaning.py
│
├── reports/
│ └── visuals/ # Charts and output plots
│
├── requirements.txt # Dependencies
└── README.md # Project documentation


---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔍 Key Highlights
- Performed detailed exploratory data analysis (EDA)  
- Conducted data cleaning and feature preparation  
- Visualized transaction trends and anomalies  
- Identified spending habits at customer/category/merchant levels  
- Summarized findings with business-friendly insights  

---

## 📈 Key Insights (Examples)
- Transaction volume patterns (daily/weekly/monthly)  
- Distribution of high-value vs low-value transactions  
- Merchant & category-level spending patterns  
- Detection of outliers or unusual transaction behavior  
- User segments based on spending  

---

## 📦 How to Run the Project

### **1. Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/Financial_Transactions_Analysis.git
cd Financial_Transactions_Analysis



