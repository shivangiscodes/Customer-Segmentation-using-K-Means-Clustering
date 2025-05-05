# 🧠 Customer Segmentation Using Clustering

This project demonstrates unsupervised machine learning techniques to segment customers based on their behavior and demographic data. The goal is to help businesses personalize their marketing strategies and product offerings based on meaningful customer clusters.

![Customer Segmentation](https://github.com/KarnikaKapoor/Files/blob/main/Colorful%20Handwritten%20About%20Me%20Blank%20Education%20Presentation.gif?raw=true)

## 📌 Project Overview

Customer segmentation divides a customer base into groups of individuals that are similar in specific ways relevant to marketing. In this project, clustering algorithms are applied to customer data from a grocery firm's database to identify key segments.

## 🔍 Key Features

* **Data Preprocessing**: Handled missing values, label encoding, and feature scaling.
* **Dimensionality Reduction**: Applied PCA for visualization and performance enhancement.
* **Clustering Techniques**:

  * K-Means with Elbow Method for optimal cluster selection.
  * Hierarchical Agglomerative Clustering.
* **Evaluation & Visualization**:

  * 2D and 3D visualizations using matplotlib and seaborn.
  * Cluster interpretability using PCA plots and heatmaps.

## 🛠️ Libraries Used

* `pandas`, `numpy`, `matplotlib`, `seaborn`
* `scikit-learn`, `yellowbrick`
* `PCA`, `KMeans`, `AgglomerativeClustering`

## 📁 Dataset

The dataset used is the **Marketing Campaign** dataset, which includes customer demographics, purchasing behavior, and campaign responses.

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/shivangiscodes/Customer-Segmentation-using-K-Means-Clustering.git
   cd customer-segmentation
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook Customer-Segmentation-using-K-Means-Clustering.ipynb
   ```

## 📈 Output

The final output includes customer segments visualized in 2D and 3D space, helping interpret how different groups behave and respond.

