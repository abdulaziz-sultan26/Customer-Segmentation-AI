# Customer Segmentation using K-Means Clustering 📊

## 1. Project Overview
This project focuses on segmenting mall customers into distinct groups based on their purchasing behavior and demographic characteristics. Using unsupervised machine learning (K-Means Clustering), we identify patterns that enable businesses to develop targeted marketing strategies and optimize resource allocation.

## 2. Dataset Information
The project utilizes the **Mall Customers Dataset**.
* **Total Records:** 200 customers
* **Key Features:** * `Age`: Customer age (18-70 years)
    * `Annual Income (k$)`: Annual income in thousands of dollars
    * `Spending Score (1-100)`: Score assigned based on customer behavior and spending nature

> [!NOTE]  
> Data Source: [Kaggle - Mall Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

## 3. Technical Implementation
* **Algorithm:** K-Means Clustering.
* **Feature Selection:** Based on Annual Income and Spending Score.
* **Evaluation:** Used the **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters.
* **Stack:** Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn).

## 4. Project Structure
```text
├── data/               # Dataset files
├── notebooks/          # Jupyter Notebook (marketing.ipynb)
├── docs/               # Project documentation and reports
├── requirements.txt    # Required libraries
└── README.md           # Project overview (this file)
5. Key Findings
Segment Analysis: The model successfully identified distinct customer segments (e.g., High Income/Low Spenders vs. High Income/High Spenders).

Targeting: Recommendations were developed for each segment to improve customer retention.

6. Detailed Report
For a deep dive into the methodology, exploratory data analysis (EDA), and business recommendations, please refer to the full technical report located in the docs folder:
👉 View Technical Report (PDF)

7. How to Run
Clone this repository:

Bash
git clone [https://github.com/YOUR_USERNAME/Customer-Segmentation-AI.git](https://github.com/YOUR_USERNAME/Customer-Segmentation-AI.git)
Install dependencies:

Bash
pip install -r requirements.txt
Run the notebook:

Bash
jupyter notebook notebooks/marketing.ipynb

Developed by: Abdulaziz Almaafry

Information Technology Student - Taiz University