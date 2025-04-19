# 🛍️ Purchase Pattern Clustering

Retail customer analysis and segmentation using RFM modeling, outlier removal, and data visualization.

---

## 📊 Project Overview

This project performs customer segmentation using **RFM (Recency, Frequency, Monetary)** analysis on retail transaction data. The goal is to understand customer value and behavior patterns to help businesses optimize retention, engagement, and marketing strategies.

---

## 🔍 Key Objectives

- Clean and preprocess real-world transactional data
- Engineer features like `SalesLineTotal` and RFM metrics
- Detect and remove outliers using IQR method
- Standard scale features to prepare for clustering
- Apply KMeans to identify meaningful customer segments
- Visualize customer distributions and cluster characteristics

---

## 🛠️ Features

- ✅ RFM metric calculation per customer
- ✅ Outlier handling and reintegration via custom cluster labeling
- ✅ StandardScaler-based feature normalization
- ✅ Elbow method + Silhouette Score for optimal cluster count
- ✅ Violin plots and histogram-based RFM visualizations
- ✅ Final summary plot showing customer distribution per segment and average behavior

---

## 📈 Segment Insights: Cluster-Level Breakdown

This visualization shows the number of customers in each segment, along with the average **Recency**, **Frequency**, and **Monetary Value per £100** across clusters:

- 📊 **Bars** = number of customers in each segment  
- 📉 **Lines** = average value for each RFM metric per segment

![image](https://github.com/user-attachments/assets/702e16b8-af09-4869-b097-16ef22308975)


## 🚀 Future Enhancements

- [ ] Integrate Power BI dashboard for interactive insights
- [ ] Auto-label customer clusters based on behavior rules
- [ ] Add CLTV prediction for marketing prioritization
- [ ] Deploy as a web-based business analytics tool


---

## 📊 Dataset

- **Source:** [UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/ml/datasets/online+retail)  
- Includes transactions from a UK-based online retailer between 2010 and 2011.

---

## 🚀 Future Enhancements

- [ ] Integrate Power BI dashboard for interactive insights
- [ ] Auto-label customer clusters based on behavior rules
- [ ] Add CLTV prediction for marketing prioritization
- [ ] Deploy as a web-based business analytics tool

---

## 📦 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- (Upcoming: Power BI)

---

## 🤝 Credits

This project is adapted from a tutorial by TrentDoesMath(https://www.youtube.com/watch?v=afPJeQuVeuY).  
I used it as a learning exercise(as must be evident from the comments in the source file) and plan to enhance it with Power BI visualizations.

---

## 👤 Author

**Shehjaar Manwati**  
🔗 [LinkedIn](https://www.linkedin.com/in/shehjaar-manwati/)



