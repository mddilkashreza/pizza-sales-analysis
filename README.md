# 🍕 Pizza Sales Data Science Project

This project analyzes pizza delivery performance to uncover factors that impact delivery time, efficiency, and delays using Python and Scikit-learn.  

It follows a full end-to-end data science workflow — from cleaning and visualization to machine learning model training and evaluation.  

---

## 🔍 Project Workflow

### 1️⃣ Data Cleaning & Preparation
- Checked for missing values, duplicates, and data types  
- Handled outliers using the IQR method  
- Encoded categorical variables (e.g., Pizza Size, Payment Method)  
- Scaled numeric features for model readiness  

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualized patterns between delivery time, pizza size, and traffic  
- Used boxplots, histograms, and heatmaps for correlation analysis  
- Identified factors causing delays during peak hours or weekends  

### 3️⃣ Machine Learning
- Built a **Decision Tree Regressor** to predict delivery duration  
- Evaluated using **R² Score**, **RMSE**, and **Visual Comparison**  
- Discussed insights and improvement ideas (Random Forest, XGBoost)  

---

## 📂 Folder Structure


---

## 🧠 Tools & Libraries Used

| Purpose | Library |
|----------|----------|
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Environment | Jupyter Notebook, VS Code |

---

## 🚀 Future Enhancements
- Add Random Forest and XGBoost models  
- Perform hyperparameter tuning  
- Create a Streamlit or Flask dashboard for live delivery predictions  
- Compare performance across restaurants and traffic levels  

---

## 📊 Sample Visualization

*(Add an image if you saved one, e.g. `delivery_boxplot.png`)*  
```markdown
![Delivery Boxplot](data/delivery_boxplot.png)
---

## 👨‍💻 Author

**Name:** Dilkash  
**Location:** Budapest, Hungary 🇭🇺  
**Focus Areas:** Data Science | Full-Stack Development | AI Agentic Systems  

📫 **Connect with me:**  
- [LinkedIn](https://www.linkedin.com/in/mddilkashreza/)  
- [GitHub](https://github.com/mddilkashreza)
💬 How to Run This Project

Clone this repo:

git clone https://github.com/mddilkashreza/pizza-sales-analysis.git
cd pizza-sales-analysis


Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn


Open the notebook:

jupyter notebook notebooks/pizza_sales_analysis.ipynb


✨ This project was built as part of my data science learning journey — combining Python, EDA, and Machine Learning to analyze real-world delivery performance.


---

## ✅ **Now You Should:**
1. Open your `pizza-sales-analysis` folder in **VS Code**  
2. Add the above text to a new file named **`README.md`**  
3. Save it (Ctrl + S)  
4. Run:
   ```bash
   git add .
   git commit -m "Added README and final structure"
   git push