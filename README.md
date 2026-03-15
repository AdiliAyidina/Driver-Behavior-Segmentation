# Driver-Behavior-Segmentation
Applied K-Means Clustering to segment driver behavior using Python. Developed a risk-profiling model that categorizes drivers into four groups—from 'Safe Urban' to 'Extreme Risk'—by optimizing $k$ via Elbow and Silhouette methods. Provides actionable insights for fleet safety and insurance risk assessment.

# Driver Behavior Segmentation: A Machine Learning Approach

## 📌 Project Overview
This project applies **Unsupervised Machine Learning** to identify distinct driving patterns within a transport dataset. By analyzing variables such as mean distance driven per day and the percentage of time spent speeding, I developed a clustering model that segments drivers into four risk-based profiles.

## 🎯 Objective
The goal is to provide a data-driven framework for insurance companies or fleet managers to identify high-risk behaviors and optimize safety protocols.

## 🛠️ Technical Workflow
- **Data Preprocessing:** Handled scaling and normalization for distance and speed metrics.
- **Model Selection:** Implemented **K-Means Clustering**.
- **Optimization:** Utilized the **Elbow Method** and **Silhouette Coefficient** to determine the optimal number of clusters ($k=4$).
- **Visualization:** Created scatter plots to visualize cluster boundaries and behavioral centroids.

## 📊 Key Findings: Driver Profiles
1. **Low-Risk Urban (Cluster 0):** Short distances, low speed. Typical city commuters.
2. **Impatient Urban (Cluster 2):** Short distances but high speeding frequency. High collision risk in cities.
3. **Professional Long-Distance (Cluster 1):** High daily mileage but controlled speed. Reliable, rational drivers.
4. **Extreme Risk (Cluster 3):** High mileage combined with critical speeding (>70%). The primary threat to road safety.

## 💻 Tech Stack
- **Python** (Pandas, NumPy)
- **Scikit-learn** (K-Means, Metrics)
- **Matplotlib & Seaborn** (Data Visualization)

## 🚀 How to Use
1. Ensure you have `scikit-learn` and `pandas` installed.
2. Run the Jupyter Notebook `driver behavior segmentation.ipynb` to see the step-by-step logic from raw data to the final four-cluster model.

---
**Contact:** [Your Name] | [Your LinkedIn Link]
