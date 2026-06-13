# INEGI Household Clustering Analysis

## Overview

This project applies unsupervised machine learning techniques to analyze socioeconomic patterns in Mexican households using data obtained from INEGI.

The workflow includes data acquisition, cleaning, preprocessing, dimensionality reduction through Principal Component Analysis (PCA), cluster identification using K-Means, and interpretation of the resulting household segments.

The objective is to transform high-dimensional socioeconomic data into actionable insights that can support data-driven decision-making and population segmentation.

---

## Dataset

The data used in this project was obtained from the National Institute of Statistics and Geography (INEGI) of Mexico.

The dataset contains socioeconomic indicators related to household characteristics, expenditure, education, and living conditions.

---

## Methodology

The analysis follows the following steps:

1. Data acquisition from INEGI.
2. Data cleaning and preprocessing.
3. Feature selection and normalization.
4. Dimensionality reduction using Principal Component Analysis (PCA).
5. Determination of the optimal number of clusters using:

   * Elbow Method
   * Silhouette Score
   * Calinski-Harabasz Index
6. Household segmentation using K-Means clustering.
7. Cluster profiling and interpretation.
8. Data visualization and result analysis.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Key Findings

The analysis identified groups of households with distinct socioeconomic characteristics. These segments reveal differences in factors such as income, education, expenditure patterns, and living conditions.

The results demonstrate how unsupervised learning techniques can uncover meaningful structures within large socioeconomic datasets.

---

## Potential Applications

* Public policy design
* Social program targeting
* Market segmentation
* Resource allocation
* Socioeconomic research
* Data-driven decision-making

---

## Future Work

Possible improvements include:

* Evaluation of alternative clustering algorithms.
* Geographic analysis of the identified segments.
* Incorporation of additional socioeconomic indicators.
* Development of interactive dashboards for result exploration.

---

## Author

Abraham Nava

Data Science and Physics Student at UNAM

