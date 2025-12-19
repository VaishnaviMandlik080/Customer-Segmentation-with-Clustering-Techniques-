# Customer-Segmentation-with-Clustering-Techniques-
This project segments customers into distinct groups using unsupervised learning techniques like K-Means and Hierarchical Clustering to understand customer behavior and support targeted marketing strategies.


##  Dataset Used
- Customer dataset containing features such as:
  - Customer ID
  - Age
  - Gender
  - Annual Income
  - Spending Score / Purchase Behavior

---

##  Techniques & ML Concepts Covered

### **1. Data Preprocessing**
- Handling missing values
- Feature scaling (StandardScaler / MinMaxScaler)
- Encoding categorical variables

### **2. Clustering Algorithms**
- K-Means Clustering
- Hierarchical Clustering
- DBSCAN (optional)

### **3. Cluster Evaluation**
- Elbow Method
- Silhouette Score
- Dendrogram analysis

### **4. Visualization**
- 2D and 3D cluster plots
- Customer distribution across clusters
- Feature-wise cluster comparison

---

##  Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn
- SciPy

---

##  Project Workflow
1. Load customer dataset  
2. Perform Exploratory Data Analysis (EDA)  
3. Scale and preprocess data  
4. Apply clustering algorithms  
5. Determine optimal number of clusters  
6. Visualize and interpret customer segments  

---

##  Evaluation Metrics
- Silhouette Score
- Inertia (K-Means)
- Visual cluster separation

---

##  Project Structure
Customer-Segmentation/
│-- customer_data.csv
│-- customer_segmentation.ipynb
│-- README.md

---

##  Outcome
- Identified distinct customer groups based on behavior
- Enabled data-driven customer targeting
- Demonstrated practical use of unsupervised learning techniques

---

##  Future Enhancements
- Add PCA for dimensionality reduction
- Use real-time customer data
- Deploy segmentation dashboard using Streamlit
- Combine clustering with predictive models
