Project Title: Titanic Dataset - Data Preprocessing and Outlier Handling

Description:
This project focuses on preprocessing the Titanic dataset. The notebook performs data cleaning, encoding, standardization, and outlier detection/treatment using boxplots and IQR method.

Key Steps Covered:

Importing and inspecting the dataset

Handling missing values using median (for numerical) and mode (for categorical)

Label encoding of categorical columns

Feature scaling using StandardScaler

Outlier detection using boxplots and the IQR method

Outlier treatment by replacing with median

Visualizations using Matplotlib

Dataset Used:
Titanic-Dataset.csv (assumed to be stored locally at Downloads/archive (3)/)

Libraries Used:

pandas

numpy

matplotlib

scikit-learn

How to Run:
Clone the repository or download the notebook.
Ensure the Titanic dataset CSV is placed at the correct file path or update the path in the code.
Install the required libraries (if not already installed):
pip install pandas numpy matplotlib scikit-learn
Run the notebook in a Jupyter environment:
jupyter notebook Task1.ipynb
Output:
A cleaned, encoded, and scaled dataset
Box plots for numerical features before and after outlier treatment
# Titanic Data Analysis – Exploratory Data Analysis (EDA)

This project performs exploratory data analysis (EDA) on the Titanic dataset using Python libraries such as Pandas, Seaborn, and Matplotlib. The goal is to uncover insights into passenger demographics, survival rates, and relationships between features.

---

## 📊 Tasks Performed

### 1. Summary Statistics
- Computed mean, median, mode, standard deviation, min, max, and quartiles.
- Identified missing values and feature types.

### 2. Visualizations
- **Histograms:** Distribution of Age and Fare.
- **Boxplots:** Age and Fare across Passenger Classes.
- **Barplots:** Survival rates by Class and Gender.
- **Heatmap:** Correlation matrix for numeric features.
- **Pairplot:** Relationships among Age, Fare, Class, and Survival.

### 3. Feature Relationships
- Strong negative correlation between `Pclass` and `Fare`.
- Moderate relationship between `Fare` and `Survived`.

---

## 🔍 Key Insights

### ✅ Patterns, Trends, and Anomalies

| Feature   | Pattern / Trend | Anomaly |
|-----------|-----------------|---------|
| **Age**   | Most passengers between 20–40 | Some aged 70+ (outliers) |
| **Fare**  | Right-skewed; most < $100 | Outliers > $500 |
| **Pclass**| 3rd class had more passengers | Low fare in 1st class (possible discounts) |

---

## 🧠 Feature-Level Inferences

| Feature   | Inference |
|-----------|-----------|
| **Age**   | Children had higher survival rates; older adults less likely to survive. |
| **Fare**  | Higher fare generally correlated with survival; 1st class fares highest. |
| **Pclass**| Strong indicator of survival; 1st class had the highest rate. |
| **Sex**   | Females had significantly higher survival rates than males. |

---

## 🛠️ Tools Used

- **Python 3.x**
- **Pandas**
- **Seaborn**
- **Matplotlib**

---

## 📁 Files

- `Titanic-Dataset.csv` – Input dataset
- `Task_1.ipynb` – EDA Notebook
- `README.md` – This file

---

## 📌 How to Run

1. Clone the repo
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn


