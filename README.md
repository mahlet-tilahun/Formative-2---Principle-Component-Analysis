# Formative Assignment 1 – Principal Component Analysis (PCA)


This project implements **Principal Component Analysis (PCA)**, focusing on eigenvalues, eigenvectors, covariance, and explained variance. The goal is to reduce dimensionality while preserving as much variance as possible.

The dataset used in this project is an Africanized malaria-related dataset containing epidemiological and socio-economic indicators across multiple regions. It consists of **more than 10 features**, including both **numeric and non-numeric variables**, and originally contained **missing (NaN) values**.

Non-numeric columns (such as categorical identifiers) were excluded prior to PCA, while missing values in numeric features were handled using **mean imputation**. This preprocessing ensured compatibility with linear algebra operations while preserving the statistical properties of the data.
---

## Project Structure

.
├── PCA_Formative_Assignment_Aligned.ipynb
├── DatasetAfricaMalaria.csv
└── README.md

---

## Requirements

- Python 3.x  
- NumPy  
- Pandas  
- Matplotlib  

Install dependencies using:

```bash
pip install numpy pandas matplotlib
```

##Methodology

- Load the dataset and identify numeric and non-numeric columns.

- Handle missing values using mean imputation.

- Standardize the data using NumPy​

- Compute the covariance matrix.

- Perform eigendecomposition.

- Sort eigenvalues and eigenvectors in descending order.

- Compute explained variance and dynamically select principal components.

- Project the data onto the selected principal components.

- Visualize the data before and after PCA.

## Output

- Reduced-dimensional dataset

- Explained variance ratios

- Visual comparison of data before and after PCA
