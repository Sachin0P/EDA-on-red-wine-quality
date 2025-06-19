# 🍷 EDA on Red Wine Quality Dataset

This project performs **Exploratory Data Analysis (EDA)** on the Red Wine Quality dataset. The analysis includes:

- Summary statistics  
- Box plots to explore distributions and outliers  
- Correlation heatmaps to understand relationships between features  
- Graphical representation using `pandas`, `seaborn`, and `matplotlib`

---

## 📂 Files

- `EDA_on_red_wine_quality.ipynb` – Main Jupyter notebook containing the analysis  
- `winequality-red.csv` – Dataset used for the analysis (source: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality))  
- `README.md` – Project overview  

---

## 🧰 Requirements

Install the required libraries before running the notebook:

pip install pandas numpy seaborn matplotlib


🚀 How to Run

    Clone the repo

git clone https://github.com/Sachin0P/EDA-on-red-wine-quality.git
cd EDA-on-red-wine-quality

Open the notebook

    jupyter notebook EDA_on_red_wine_quality.ipynb

    Run each cell in order to perform:

        Dataset loading and preview

        Data cleaning steps (if any)

        Graphical insights using boxplots and heatmaps

📊 Sample Visualizations
🔲 Box Plot 

  ![image](https://github.com/user-attachments/assets/a6e6b749-60f2-4379-8c22-365cf974ca3d)

🔥 Heatmap (Paste image here)

   ![image](https://github.com/user-attachments/assets/3a513781-9082-430c-bcab-eadc5ab47b54)


📌 Key Insights

    Quality is positively correlated with alcohol content.

    Volatile acidity and citric acid show inverse behavior.

    Some features like residual sugar show weak correlation with wine quality.
