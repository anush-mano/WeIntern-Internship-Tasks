📌 **Task Description**  
**Customer Segmentation using K-Means Clustering** - Analyze Mall Customers dataset to identify distinct customer groups based on Annual Income and Spending Score for targeted marketing strategies.

**Challenges Tackled:**
✅ Data loading & exploratory analysis  
✅ Feature selection & **StandardScaler** preprocessing  
✅ Optimal k selection using **Elbow Method** (k=4)  
✅ K-Means clustering implementation  
✅ **2D + PCA visualizations** with cluster centers  
✅ Business insights & cluster profiling  

---

### 🧠 **Project Overview**
Complete unsupervised machine learning pipeline for customer segmentation:

1. **Dataset**: Mall Customers (200 customers × 5 features)
2. **Features Used**: 
   - Annual Income (k$): 15-137k
   - Spending Score (1-100): 1-99
3. **Preprocessing**: StandardScaler for feature normalization
4. **Clustering**: K-Means (optimal k=4 via Elbow Method)
5. **Visualizations**:
   - Elbow plot for optimal k selection
   - 2D scatter plots (Income vs Spending)
   - PCA 2D visualization
   - Cluster centers overlay
6. **Results**: 4 actionable customer segments with business insights

**Cluster Profiles:** 
Cluster 0: Low Income (₹26k), Low Spending (21) - Conservative
Cluster 1: High Income (₹87k), Low Spending (19) - Conservative Elite
Cluster 2: Low Income (₹48k), High Spending (56) - Targeted Promoters
Cluster 3: High Income (₹87k), High Spending (82) - Ideal Customers


---

### 🗂️ **Files Included**
- `week2_customer_segmentation.ipynb` — Complete analysis notebook [file:75]  
- `MallCustomers.csv` — Customer dataset (auto-loaded)  
- `customer_segments_results.csv` — Clustered results with predictions  

---

### 🛠 **Tech Stack**
Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn


---

### 🚀 **How to Run**
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook week2_customer_segmentation.ipynb


**Expected Output:**
1. Dataset shape: `(200, 5)` customers
2. Elbow plot → **Optimal k=4**
3. Cluster distribution: `[23, 38, 100, 39]`
4. 2D/PCA visualizations with **cluster centers**
5. **Business insights** for marketing strategy
6. Results saved as `customer_segments_results.csv`

---

### 📊 **Key Results**

Cluster Insights:
​

Cluster 0 (23 customers): Conservative - Low budget, low spenders

Cluster 1 (38 customers): Conservative Elite - High income, careful spenders

Cluster 2 (100 customers): Targeted Promoters - Low income, high spenders ⭐

Cluster 3 (39 customers): Ideal Customers - High income, high spenders 💎


---

### 🎯 **Business Applications**
- **Targeted Promotions**: Focus on Cluster 2 (100 customers) - high spenders despite low income
- **Premium Services**: Cluster 3 (Ideal) - ready for luxury offerings
- **Budget Products**: Cluster 0 - price-sensitive customers
- **Relationship Building**: Cluster 1 - high-value careful spenders

---

**Key Learnings:**
- Feature scaling is **mandatory** for K-Means 
- Elbow method for **hyperparameter tuning**
- PCA for **visualization** of clusters
- Translating clusters into **business strategy**
