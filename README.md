# Customer Segmentation Using K-Means Clustering

## 📌 Objective
The goal of this project is to segment customers into different groups based on their annual income and spending behavior using the K-Means clustering algorithm.

---

## 📊 Dataset
The dataset used is **Mall Customers Dataset**, which contains:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## ⚙️ Steps Performed
1. Data Loading
2. Feature Selection (Income & Spending Score)
3. Data Scaling using StandardScaler
4. Finding optimal clusters using Elbow Method
5. Applying K-Means Clustering
6. Visualization of clusters
7. Evaluation using:
   - Silhouette Score
   - Davies-Bouldin Index

---

## 📈 Results
- Customers are grouped into **5 clusters**
- Clusters represent different spending patterns

---

## 🧠 Evaluation Metrics
- **Silhouette Score** → Measures how well clusters are separated (higher is better)
- **Davies-Bouldin Index** → Measures cluster similarity (lower is better)

---

## 🛠️ Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

---

## 📂 Project Files
- `kmeans_model.ipynb` → Main notebook
- `Mall_Customers.csv` → Dataset
- `README.md` → Project description

---

## 📌 Conclusion
K-Means clustering helps identify different types of customers based on their spending behavior. This can be useful for targeted marketing and business strategies.

---

## 🚀 How to Run
1. Open the notebook in Google Colab
2. Upload the dataset
3. Run all cells

---

## 🔗 Submission
GitHub repository link is provided as part of the assignment submission.
