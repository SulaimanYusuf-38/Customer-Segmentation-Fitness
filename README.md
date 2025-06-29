# 🧍‍♂️🧍‍♀️ Customer Segmentation for a Fitness Business – K-Means++ and Agglomerative Clustering

This project applies unsupervised machine learning techniques to segment gym members based on demographic and socio-economic attributes. The aim is to derive actionable insights for targeted marketing and customer retention strategies.

## 📌 Objective

Segment gym members into meaningful groups based on age, income, education, occupation, marital status, and settlement type using K-Means++ and Agglomerative Clustering. The goal is to inform personalised marketing and improve customer engagement.

## 📁 Dataset Description

- Records: Gym members with demographic and income attributes
- Features: Age, Income, Gender, Education, Occupation, Marital Status, Settlement Size
- Data Source: University-provided dataset (simulated for academic purposes)

## 🧪 Methodology

### 1. Exploratory Data Analysis (EDA)
- Income distribution is right-skewed, while age is near-normal
- Income increases with age and is influenced by education and occupation
- Correlation analysis reveals strong links between age, income, and other categorical traits

### 2. Data Preprocessing
- Standardised numerical features using Z-score
- Encoded categorical variables for clustering

### 3. Clustering Techniques
- **K-Means++**
  - Optimal K determined using Elbow Method and Silhouette Score
  - Selected K = 3 based on cluster balance and separation
- **Agglomerative Clustering**
  - Ward’s linkage used for hierarchical grouping
  - Also set to K = 3 for comparison

### 4. Segment Naming and Interpretation
- **K-Means++ Segments:**
  - Cluster 0: *Young Budget-Conscious*
  - Cluster 1: *Affluent Professionals*
  - Cluster 2: *Stable Mid-Level Members*

- **Agglomerative Segments:**
  - Cluster 0: *Value-Oriented Members*
  - Cluster 1: *Split Affluent Group*
  - Cluster 2: *Mixed Mid-to-High Earners*

## 📊 Key Findings

- K-Means++ produced more balanced, well-separated clusters suitable for targeted marketing
- Agglomerative Clustering revealed similar patterns but had uneven segment sizes
- Visualisations (scatterplots and cross-tab comparisons) show better clarity with K-Means++

## 📈 Marketing Recommendations

- **Young Budget-Conscious**: Affordable app-based plans, youth brand partnerships, TikTok campaigns
- **Affluent Professionals**: Premium packages, personal tracking dashboards, milestone reminders
- **Stable Mid-Level**: Family plans, wellness perks, challenge-based rewards

## 🔧 Tools Used

- Python (Jupyter Notebook)
- pandas, numpy, scikit-learn
- seaborn, matplotlib

## 👤 Author

**Sulaiman Yusuf Zakaria**  
Master of Business Analytics  
Macquarie University  


---

This project was completed for **BUSA8001 – Applied Predictive Analytics** as Programming Task 2. It demonstrates practical application of clustering techniques to real-world segmentation problems.
