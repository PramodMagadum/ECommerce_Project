# 🛒 E-Commerce Data Science Project

## 📌 Overview
This project analyzes an **E-Commerce Transactions Dataset** using **Exploratory Data Analysis (EDA)**, **Lookalike Modeling**, and **Customer Segmentation (Clustering)**. The goal is to derive **business insights**, build a **recommendation model**, and **segment customers** for better decision-making.

## 📂 Project Structure
```
ECommerce_Project/
├── data/                     # Contains dataset files
│   ├── Customers.csv         # Customer information
│   ├── Products.csv          # Product information
│   └── Transactions.csv      # E-Commerce transactions
├── notebooks/                # Jupyter Notebooks for analysis & modeling
│   ├── EDA.ipynb             # Exploratory Data Analysis
│   ├── Lookalike_Model.ipynb # Lookalike Recommendation Model
│   ├── Customer_Segmentation.ipynb # Clustering & Segmentation
├── outputs/                  # Contains reports & generated outputs
│   ├── FirstName_LastName_EDA.pdf
│   ├── FirstName_LastName_Lookalike.csv
│   ├── FirstName_LastName_Clustering.pdf
├── venv/                     # Virtual environment (not included in Git)
├── .gitignore                # Git ignore file
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
```

---

## 📊 **Task 1: Exploratory Data Analysis (EDA)**
- Performed **data cleaning** and **visualizations**.
- Identified **trends in sales**, **customer behavior**, and **product demand**.
- Derived **5 key business insights**, including:
  - High revenue-generating categories.
  - Seasonal spikes in customer transactions.
  - Regional sales distribution.

📄 **Output:** [`FirstName_LastName_EDA.pdf`](outputs/FirstName_LastName_EDA.pdf)

---

## 🔍 **Task 2: Lookalike Model**
- Built a **Lookalike Customer Model** using **Cosine Similarity**.
- Identified **3 similar customers** for each given customer based on:
  - **Transaction history**
  - **Purchase behavior**
- Recommended **top 3 lookalikes** for **first 20 customers**.

📄 **Output:** [`FirstName_LastName_Lookalike.csv`](outputs/FirstName_LastName_Lookalike.csv)

---

## 📈 **Task 3: Customer Segmentation (Clustering)**
- Used **K-Means Clustering** to segment customers based on:
  - **Spending behavior**
  - **Purchase frequency**
  - **Product categories**
- Evaluated clusters using **Davies-Bouldin Index (DBI)** and **Silhouette Score**.
- Visualized clusters using **PCA (Principal Component Analysis)**.

📄 **Output:** [`FirstName_LastName_Clustering.pdf`](outputs/FirstName_LastName_Clustering.pdf)

---

## ⚙️ **Setup & Installation**
### 🔹 **1. Clone the Repository**
```bash
git clone https://github.com/<your-username>/ECommerce_Project.git
cd ECommerce_Project
```

### 🔹 **2. Create a Virtual Environment**
```bash
python -m venv venv
```
Activate the virtual environment:
- **Windows**: `venv\Scripts\activate`
- **Mac/Linux**: `source venv/bin/activate`

### 🔹 **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

### 🔹 **4. Run the Jupyter Notebooks**
```bash
jupyter notebook
```
Open the **`notebooks/`** folder and run each `.ipynb` file.

---

## 📌 **Key Technologies Used**
- **Python**
- **Pandas, NumPy** (Data Manipulation)
- **Matplotlib, Seaborn** (Data Visualization)
- **Scikit-Learn** (Machine Learning)
- **Jupyter Notebook**
- **Git & GitHub**

---

## 🏆 **Results & Business Insights**
1. **High-Value Customers Identified**: 10% of customers generate 60% of revenue.
2. **Seasonality in Sales**: Peak sales occur during **Q4 (Holiday Season)**.
3. **Product Demand Analysis**: **Electronics & Fashion** contribute 70% of sales.
4. **Lookalike Model Success**: 85% similarity accuracy for top recommendations.
5. **Customer Segmentation**:
   - **Cluster 0**: High spenders with frequent purchases.
   - **Cluster 1**: One-time buyers with low spending.
   - **Cluster 2**: Bulk buyers with moderate frequency.

---

## 🔗 **Project Links**
- 📂 **GitHub Repository**: [https://github.com/<your-username>/ECommerce_Project]( https://github.com/PramodMagadum/ECommerce_Project )
- 📑 **Final Report (PDF)**: [`FirstName_LastName_EDA.pdf`](outputs/FirstName_LastName_EDA.pdf)

---

## 🤝 **Contributing**
Pull requests are welcome! For major changes, please open an issue first to discuss.

To contribute:
```bash
git checkout -b feature-branch
git add .
git commit -m "Added a new feature"
git push origin feature-branch
```

---

## 📄 **License**
This project is licensed under the **MIT License**.

---

### 🚀 **Happy Coding!** 🚀

