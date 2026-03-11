# Exploratory Data Analysis and Feature Engineering: Iris Dataset

## 📌 Project Overview
This project focuses on performing comprehensive Exploratory Data Analysis (EDA) on the classic Iris dataset. The primary objective is to investigate the structural relationships between morphological features and identify statistical anomalies (outliers) using advanced data visualization techniques.

## 📊 Dataset details
* **Source:** Built-in Seaborn `iris` dataset.
* **Features:** Sepal Length, Sepal Width, Petal Length, Petal Width (measured in cm).
* **Target:** Iris Species (Setosa, Versicolor, Virginica).

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn

## 🔬 Methodology
1. **Data Ingestion & Integrity Check:** Loaded the dataset and verified structural integrity (150 rows, 0 missing values).
2. **Distribution Analysis:** Plotted histograms with Kernel Density Estimates (KDE) to understand the frequency distributions of individual morphological traits.
3. **Bivariate Analysis:** Generated hue-mapped scatter plots to evaluate the linear separability of species based on petal and sepal dimensions.
4. **Outlier Detection:** Utilized box plots and the Interquartile Range (IQR) method to isolate mathematical outliers, specifically within the `sepal_width` feature.

## 💡 Key Insights
* **Feature Importance:** Petal dimensions (length and width) exhibit a significantly higher variance between species compared to sepal dimensions, making them far superior predictors for classification algorithms.
* **Class Separability:** *Iris Setosa* forms a strictly linearly separable cluster, whereas *Versicolor* and *Virginica* show marginal dimensional overlap.

## 👩‍💻 Author
**Eshaal Hammad**
* **Email:** eshaalhammad234@gmail.com
