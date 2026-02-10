# customer
Internship project applying K-Means clustering with visualizations for HR insights-Customer Segmentation.
# AENEXZ_Project

## 📌 Overview
This internship project applies **K-Means clustering** to perform **customer segmentation** using the *Mall_Customers* dataset. The goal is to generate actionable HR and business insights by grouping customers based on their **annual income** and **spending score**, supported by clear visualizations.

---

## ⚙️ Workflow

1. **Data Loading**
   - Upload `Mall_Customers.csv` into the notebook.
   - Read dataset using `pandas`.

2. **Feature Selection**
   - Focus on `Annual Income (k$)` and `Spending Score (1-100)`.

3. **Data Preprocessing**
   - Standardize features using `StandardScaler`.

4. **Clustering**
   - Apply **K-Means** with `n_clusters=5` and `k-means++` initialization.
   - Assign cluster labels to each customer.

5. **Visualizations**
   - **Scatter Plot**: Distribution of customers across clusters.
   - **Bar Chart**: Number of customers per cluster.
   - **Pie Chart**: Percentage distribution of clusters.
   - **Heatmap**: Gender distribution across clusters.
   - **Cluster Summary**: Mean values of age, income, and spending score per cluster.

6. **Outputs**
   - Saved plots: `scatter.png`, `heatmap.png`, `pei.png`, `box.png`.
   - Tabular summaries for HR/business interpretation.


## 📊 Insights
- Identifies distinct customer groups based on spending behavior and income.
- Highlights demographic patterns (e.g., gender distribution across clusters).
- Provides HR and business teams with segmentation for **targeted strategies**.


## 🛠️ Technologies Used
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **Google Colab** for execution
- **K-Means clustering** for segmentation


## 🚀 How to Run
1. Open the notebook `AENEXZ_Project.ipynb` in Google Colab.
2. Upload the dataset `Mall_Customers.csv`.
3. Run all cells sequentially.
4. Review generated plots and cluster summaries.



## 📂 Repository Structure
├── AENEXZ_Project.ipynb   # Main notebook
├── Mall_Customers.csv     # Dataset
├── scatter.png            # Cluster scatter plot
├── heatmap.png            # Gender vs Cluster heatmap
├── pie.png                # Cluster distribution pie chart
├── box.png                # Additional visualization
- [Internship Project Report (PDF)](./docs/AENEXZ%20Internship%20Project%20Report.pdf)

## ✨ Applications
- HR analytics for workforce/customer segmentation.
- Business strategy for targeted marketing.
- Data-driven decision-making in customer relationship management. 




