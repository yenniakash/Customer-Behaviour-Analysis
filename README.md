
# Customer Behaviour Analysis using Python

Customer Behaviour Analysis is a data analytics project developed to understand customer purchasing patterns, spending behavior, and retention using an e-commerce dataset. The project performs data preprocessing, feature engineering, customer segmentation, and visualization to generate actionable business insights.

## Project Overview

This project analyzes customer transaction data by:

- Cleaning and preprocessing raw customer data.
- Engineering meaningful customer behavior features.
- Performing RFM (Recency, Frequency, Monetary) analysis.
- Visualizing customer purchasing patterns and retention trends.
- Providing business recommendations based on customer behavior.

## Dataset

**Dataset:** `ecommerce_customer_data_large.csv`

The dataset should contain customer transaction information such as:

- Customer ID
- Purchase Date
- Total Purchase Amount
- Quantity
- Age
- Returns
- Other customer-related attributes

> **Note:** The dataset is not included in this repository due to size/privacy reasons.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

### 1. Data Preprocessing

- Load dataset
- Handle missing values
- Remove duplicate records
- Standardize column names

### 2. Feature Engineering

Generated features include:

- Price per Unit
- High Value Purchase Flag
- Customer Total Spend
- Purchase Frequency
- Average Order Value (AOV)
- Age Group
- Spending Tier
- Return Behavior Flag

### 3. Customer Analytics

- RFM Feature Mapping
- Purchase Frequency Analysis
- Spending Analysis
- Customer Aggregation

### 4. Data Visualization

The project generates a dashboard containing:

- Customer Retention Status Distribution
- Purchase Frequency vs Total Spend
- Average Order Value by Retention Cohort
- Revenue Contribution by Customer Cohort

The dashboard is automatically saved as:

```
purchase_patterns_and_retention_trends.png
```

---

## Output Files and Screenshots

- `cleaned_ecommerce_dataset.csv`
- `purchase_patterns_and_retention_trends.png`
<img width="832" height="453" alt="Screenshot 2026-07-23 001255" src="https://github.com/user-attachments/assets/b5f2e044-d597-4036-8ff2-af097b35e990" />
<img width="836" height="423" alt="Screenshot 2026-07-23 001329" src="https://github.com/user-attachments/assets/7416286c-9909-4a46-ba83-c0fa4b0ea1ac" />
<img width="1032" height="782" alt="Screenshot 2026-07-23 001411" src="https://github.com/user-attachments/assets/cb5493d8-529f-450f-9c58-f9af137e6c9b" />


---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/Customer-Behaviour-Analysis.git

cd Customer-Behaviour-Analysis
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Open the Notebook

Run the notebook using:

- Google Colab
- Jupyter Notebook

Upload the dataset when prompted:

```
ecommerce_customer_data_large.csv
```

---

## Project Structure

```
Customer-Behaviour-Analysis/
│
├── Customer_Behaviour_Analysis.ipynb
├── README.md
├── cleaned_ecommerce_dataset.csv
├── purchase_patterns_and_retention_trends.png
└── ecommerce_customer_data_large.csv (not included)
```

---

## Business Insights

The analysis helps businesses to:

- Identify high-value customers.
- Detect customers at risk of churn.
- Understand customer purchasing behavior.
- Improve customer retention strategies.
- Optimize marketing campaigns through customer segmentation.

---

## Future Improvements

- Interactive dashboard using Plotly or Streamlit
- Customer Lifetime Value (CLV) prediction
- Churn prediction using Machine Learning
- Recommendation System
- Advanced customer segmentation using DBSCAN or Hierarchical Clustering

---

## Author

**Akash Yenni**

GitHub: https://github.com/yenniakash

---

## License

This project is licensed under the MIT License.
````

This README is suitable for a portfolio project and follows common GitHub conventions, making it easy for recruiters and collaborators to understand the project.
