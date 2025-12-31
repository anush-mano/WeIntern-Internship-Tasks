📌 *Task Description*
*Customer Segmentation using Clustering* - Use K-Means clustering to group customers based on purchasing behavior from Mall Customers dataset.

*Challenges Tackled:*
✅ Feature scaling using **StandardScaler**  
✅ Optimal k selection using **Elbow Method** (k=4)  
✅ 2D scatter plots + **PCA visualization**  
✅ Cluster profiling & business insights  

---

### 🧠 **Project Overview**
Complete unsupervised learning pipeline implemented:

1. **Dataset**: Mall Customers (200 customers × 5 features)  
2. **Features**: Annual Income (k$), Spending Score (1-100)  
3. **Preprocessing**: StandardScaler for feature normalization  
4. **Clustering**: K-Means with optimal k=4 (determined via Elbow Method)  
5. **Visualizations**:  
   - 2D scatter plots (Income vs Spending Score)  
   - Cluster centers marked  
   - 2D PCA visualization  
6. **Results**: 4 distinct customer segments identified with business insights

**Cluster Profiles:** [file:75]
Cluster 0: Low Income (26k$), Low Spending (21) - Conservative
Cluster 1: High Income (87k$), Low Spending (19) - Conservative Elite
Cluster 2: Low Income (48k$), High Spending (56) - Targeted Promoters
Cluster 3: High Income (87k$), High Spending (82) - Ideal Customers

text

---

### 🗂️ **Files Included**
- `MallCustomers.csv` — Customer dataset  
- `week2_customer_segmentation.ipynb` — Complete analysis notebook [file:75]  
- `customer_segments_results.csv` — Clustered dataset with predictions  

---

### 🛠 **Tech Stack**
**Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn**

---

### 🚀 **How to Run**
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook week2_customer_segmentation.ipynb

text

**Expected Output:**
- Elbow plot showing optimal k=4  
- 2D/PCA cluster visualizations  
- Cluster summary table  
- Business insights for marketing strategy  

---

**Key Learnings:**
- Importance of feature scaling for K-Means  
- Elbow method for hyperparameter tuning  
- PCA dimensionality reduction for visualization  
- Business interpretation of unsupervised clusters 

