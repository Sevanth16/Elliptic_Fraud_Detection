# Graph-Based Financial Fraud Detection using Elliptic++ Dataset

## Project Overview

Financial fraud detection is a critical challenge in cryptocurrency networks due to the complex relationships between transactions and wallet addresses. Traditional machine learning models analyze transactions independently and often fail to capture hidden network structures used by fraudsters.

This project leverages graph analytics and machine learning on the Elliptic++ cryptocurrency dataset to identify illicit transactions, detect fraud rings, and analyze suspicious transaction communities.

The solution combines graph-based feature engineering, community detection, fraud classification, and business intelligence dashboards to provide actionable fraud insights.


## Dataset

Dataset Used: Elliptic++

The Elliptic++ dataset is a large-scale cryptocurrency transaction network designed for fraud detection research.

### Dataset Statistics

* 203,769+ transactions
* 800,000+ wallet addresses
* 165+ transaction features
* Directed transaction graph
* Fraud, Legitimate, and Unknown transaction labels

### Class Labels

* Class 1 → Fraudulent Transaction
* Class 2 → Legitimate Transaction
* Class 3 → Unknown Transaction


## Tech Stack

| Component | Technology |
|------------|------------|
| Programming Language | Python |
| Data Processing | Pandas |
| Graph Analytics | NetworkX |
| Machine Learning | XGBoost |
| Graph Neural Networks | GraphSAGE |
| Visualization | Power BI |
| Development Environment | VS Code |

## Project Workflow

1. Data Collection (Elliptic++)
2. Data Cleaning and Preprocessing
3. Graph Construction
4. Graph Feature Engineering
5. Community Detection
6. Fraud Ring Identification
7. XGBoost Fraud Classification
8. GraphSAGE Modeling
9. Power BI Dashboard Development
10. Model Evaluation and Insights

## Graph Features Engineered

The following graph-based features were extracted from the transaction network:

* Degree Centrality
* PageRank
* In Transaction Degree
* Out Transaction Degree
* Community Membership

These features provide network-level information that improves fraud detection compared to traditional transaction-based models.

## Power BI Dashboard

The dashboard contains:

### Page 1: Executive Summary
- Total Transactions
- Fraud Transactions
- Fraud Rate
- Class Distribution

### Page 2: Fraud Analytics
- Degree vs PageRank Analysis
- Top Fraud Nodes
- Suspicious Transaction Investigation

### Page 3: Community Detection
- Fraud Ring Analysis
- Community Risk Scores
- High-Risk Communities

### Page 4: Model Performance
- Accuracy
- Precision
- Recall
- F1 Score
- Model Comparison

## Key Results

* Identified 4,545 fraudulent transactions.
* Constructed a large-scale transaction graph from cryptocurrency data.
* Detected suspicious transaction communities using graph analytics.
* Engineered graph-based features including Degree Centrality and PageRank.
* Developed machine learning models for fraud classification.
* Built an interactive Power BI dashboard for fraud investigation and monitoring.


## Project Structure

Elliptic_Fraud_Detection/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Graph_Features.ipynb
│   ├── 03_XGBoost.ipynb
│   └── 04_GraphSAGE.ipynb
│
├── dashboard/
│   └── Elliptic_Fraud_Detection.pbix
│
├── models/
│   ├── xgboost_model.pkl
│   └── graphsage_model.pth
│
└── README.md

## Dashboard Screenshots

### Executive Summary
![Executive Summary](images/executive_summary.png)

### Fraud Analytics
![Fraud Analytics](images/fraud_analytics.png)

### Community Detection
![Community Detection](images/community_detection.png)
