# 🛍 Customer Segmentation using K-Means Clustering

## 📌 Overview
This project applies **K-Means clustering** to segment customers based on their **Annual Income** and **Spending Score**.  
By grouping customers with similar purchasing behavior, businesses can target specific groups with customized strategies, improving **sales** and **satisfaction**.

---

## 📂 Dataset
**Source:** Mall Customers.csv  

**Features Used:**  
- **Annual Income (k$)** – Income level of customers  
- **Spending Score (1–100)** – Spending behavior score assigned by the mall  

---

## ⚙️ Methodology
- **Data Preprocessing** – Handling missing values, selecting relevant features  
- **Choosing k (Elbow Method)** – Identifying the optimal number of clusters  
- **Applying K-Means** – Training the model to segment customers  
- **Visualization** – Plotting results to understand cluster patterns  

---

## 📊 Visualizations
- **Elbow Method Plot:** Shows the optimal number of clusters (k) by observing the point where the WCSS curve bends.  
- **Customer Clusters Plot:** Displays customers grouped into distinct segments, making it easier to identify patterns and differences.  

---

## 💡 Insights
- **Optimal Clusters:** The elbow method suggests the ideal k for meaningful segmentation.  
- **Distinct Groups:** Customers with similar spending habits and annual incomes are grouped together.  
- **Business Impact:** Enables targeted marketing strategies, personalized offers, and improved customer satisfaction.  

---

## 🛠 Technologies Used
- **Python**  
- **Pandas**, **NumPy** (Data manipulation)  
- **Matplotlib**, **Seaborn** (Visualization)  
- **Scikit-learn** (Machine Learning)  

---

## ▶️ Open in Google Colab
Click the button below to open and run this notebook in Google Colab:  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Pooja-Pj205/Customer-Segmentation-Analysis/blob/main/Segment_Predict.ipynb)

---

## 🚀 Future Enhancements
- Include more features like **Age**, **Gender**, and **Purchase History**  
- Try other clustering algorithms (**DBSCAN**, **Hierarchical Clustering**)  
- Deploy as an interactive dashboard for real-time customer segmentation  
