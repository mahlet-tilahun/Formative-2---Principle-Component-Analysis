# Formative Assignment 1 – Principal Component Analysis (PCA)

## Course: Advanced Linear Algebra

This project implements **Principal Component Analysis (PCA) from scratch**, focusing on eigenvalues, eigenvectors, covariance, and explained variance. The goal is to reduce dimensionality while preserving as much variance as possible.

The dataset used is Africanized (malaria-related), contains **missing values**, and includes **non-numeric columns**, which are handled appropriately before applying PCA.

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
