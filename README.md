# 🛒 Customer Segmentation using RFM Analysis

## 📌 Project Overview
This project focuses on **customer segmentation** using **RFM (Recency, Frequency, Monetary) analysis** on a retail dataset.  
By leveraging **unsupervised learning techniques (K-Means, Hierarchical Clustering)**, we aim to group customers into meaningful clusters to help businesses improve marketing strategies, loyalty programs, and customer targeting.

The dataset contains details about transactions such as invoice numbers, product codes, descriptions, quantities, prices, and customer IDs.

---

##  Dataset Information
The dataset used for this analysis has the following columns:

| Column       | Description |
|--------------|-------------|
| **InvoiceNo** | Invoice number of the transaction |
| **StockCode** | Product code |
| **Description** | Name/description of the product |
| **Quantity** | Quantity of products purchased |
| **InvoiceDate** | Date and time of the transaction |
| **UnitPrice** | Price per product (in local currency) |
| **CustomerID** | Unique customer identifier |
| **Country** | Country where the customer is located |

---

##  Objectives
- Perform **data cleaning and preprocessing** on transactional data.
- Compute **RFM (Recency, Frequency, Monetary) metrics** for each customer.
- Apply **scaling and clustering techniques** to segment customers.
- Visualize clusters and provide **business insights** for marketing teams.

---

##  Tech Stack & Libraries
The project is implemented in **Python** using the following libraries:

- **Data Manipulation:** `numpy`, `pandas`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning & Clustering:** `scikit-learn`, `pyclustertend`
- **Hierarchical Clustering & Distance Metrics:** `scipy`

📌 The list of dependencies can be found in the [Requirements.txt](Requirements.txt) file.

---

## 📊 Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Removing duplicates & invalid entries
   - Converting dates to datetime format

2. **RFM Calculation**
   - **Recency:** Days since the last purchase  
   - **Frequency:** Number of transactions per customer  
   - **Monetary:** Total spending by the customer  

3. **Feature Scaling**
   - Standardizing RFM values for clustering

4. **Clustering**
   - **K-Means Clustering** with Elbow method & Silhouette score
   - **Hierarchical Clustering** with dendrograms

5. **Evaluation & Insights**
   - Cluster profiling
   - Business recommendations based on customer groups

---

## 📈 Visualizations

### 1️⃣ RFM Distribution
Shows how recency, frequency, and monetary values are spread across customers.

![RFM Distribution](images/rfm_distribution.png)

---

### 2️⃣ Elbow Method (K-Means Optimal K)
Helps determine the optimal number of clusters for K-Means.

![Elbow Curve](images/elbow_curve.png)

---

### 3️⃣ Silhouette Score
Evaluates clustering performance for different values of K.

![Silhouette Score](images/silhouette_score.png)

---

### 4️⃣ Hierarchical Clustering Dendrogram
Displays the hierarchical structure of customer clusters.

![Dendrogram](images/dendrogram.png)

---

### 5️⃣ Customer Segmentation Results
Visualization of final customer clusters.

![Customer Clusters](images/customer_clusters.png)

---

## 📈 Results & Insights
- Customers are grouped into clusters such as **high-value customers**, **frequent buyers**, **new/occasional customers**, etc.
- Helps businesses target:
  - Loyalty rewards for high-value customers
  - Engagement campaigns for medium-value customers
  - Retention strategies for at-risk customers

---

## 🚀 How to Run the Project
### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/customer-segmentation-rfm.git
cd customer-segmentation-rfm
```
### 2️⃣ Install dependencies
```bash
pip install -r Requirements.txt
```
### 3️⃣ Run the Jupyter Notebook
```bash
jupyter notebook Customer-Segmentation-RFManalysis.ipynb
```
---

## 📌 Future Work
- Extend segmentation with **deep learning-based clustering**  
- Deploy the model using **Flask/Streamlit** for interactive dashboards  
- Automate RFM updates with **real-time data**  

---

## 👩‍💻 Author
**Kavya Sharma**  
B.Tech CSE (AIML) | Data Science & Machine Learning Enthusiast  

📧 Contact: https://www.linkedin.com/in/thekavyaasharma  
🔗 GitHub: https://github.com/thekavyaasharma 

---

