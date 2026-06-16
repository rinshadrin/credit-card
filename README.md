Credit Card Customer Segmentation
This project analyzes credit card customer data and groups customers based on their spending and interaction behavior. The goal is to identify customer segments using unsupervised machine learning techniques.
![Credit Card Project Banner](image.jpg)
Project Overview
Credit card companies serve customers with different financial behavior. This project uses clustering methods to segment customers based on:
Average credit limit
Number of credit cards
Bank visits
Online visits
Calls made to the bank
Customer segmentation helps businesses understand customer groups and improve marketing, service, and product planning.
Dataset
File used:
`credit_card_customer_data.csv`
Dataset shape:
`660 rows × 7 columns`
Columns:
Column	Description
Sl_No	Serial number
Customer Key	Unique customer ID
Avg_Credit_Limit	Average credit limit of the customer
Total_Credit_Cards	Total number of credit cards held
Total_visits_bank	Total visits made to the bank
Total_visits_online	Total online visits
Total_calls_made	Total calls made to the bank
Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
SciPy
Scikit-fuzzy
Tabulate
Project Workflow
Import required libraries
Load the dataset
Check dataset information
Perform data preprocessing
Scale the data
Apply PCA for dimensionality reduction
Build clustering models
Compare clustering performance using Silhouette Score
Visualize customer segments
Clustering Models Used
K-Means Clustering
Hierarchical Clustering
DBSCAN
Fuzzy C-Means Clustering
Model Performance
Clustering Method	Silhouette Score
K-Means	0.629629
DBSCAN	0.645365
Hierarchical Clustering	0.637757
Fuzzy C-Means	0.370152
Best performing model:
`DBSCAN`
DBSCAN achieved the highest silhouette score in this project.
Key Insights
Customers show different patterns based on credit limit and service usage.
Clustering helps separate customers into meaningful groups.
DBSCAN gave the best score among the tested methods.
PCA helped reduce dimensions and made clustering visualization easier.
How to Run This Project
Clone the repository
```bash
git clone https://github.com/your-username/credit-card-customer-segmentation.git
```
Open the project folder
```bash
cd credit-card-customer-segmentation
```
Install required packages
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy scikit-fuzzy tabulate
```
Open the Jupyter Notebook
```bash
jupyter notebook
```
Run the notebook file
```text
Credit Card.ipynb
```
Repository Structure
```text
credit-card-customer-segmentation/
│
├── Credit Card.ipynb
├── credit_card_customer_data.csv
├── image.jpg
└── README.md
```
Conclusion
This project successfully segments credit card customers using clustering algorithms. DBSCAN performed best based on silhouette score. The results help understand customer behavior and support better decision making for credit card services.
Author
Muhammed Rinshad
Data Science and AI Graduate
