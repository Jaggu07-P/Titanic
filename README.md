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


