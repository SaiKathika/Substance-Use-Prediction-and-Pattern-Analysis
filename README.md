# Substance-Use-Prediction-and-Pattern-Analysis

## Overview

This project focuses on analyzing patterns and predicting substance use using both unsupervised and supervised machine learning techniques. The main objectives of this project are:
- To reduce the dimensionality of the dataset using PCA.
- To apply KMeans clustering to identify distinct groups within the dataset.
- To evaluate and predict substance use patterns using classification models.

## Features
- **Dimensionality Reduction**: Utilized Principal Component Analysis (PCA) for reducing high-dimensional data into components.
- **Clustering**: KMeans clustering was applied on PCA-reduced data to uncover hidden patterns.
- **Supervised Learning**:
  - Random Forest
  - Decision Tree
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
- **Data Processing**: Includes preprocessing steps such as handling missing values, encoding, and feature scaling.
- **Evaluation**: Performance metrics include accuracy, precision, recall, and F1-score for supervised models.

---

## Installation

### Prerequisites
- Ensure you have Python 3.8 or higher installed on your machine.<br/>
- [Download the dataset](https://www.samhsa.gov/data/data-we-collect/nsduh/datafiles?year=2017&data_collection=1137)

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/SaiKathika/Substance-Use-Prediction-and-Pattern-Analysis.git
   cd Substance-Use-Prediction-and-Pattern-Analysis

2. Install the required Packages:
   ```bash
   pip install -r requirements.txt

3. Download the dataset using the above link

4. Run Supervised Models
   With Sampling
   ```bash
   python classification_with_sampling.ipynb
   ```
   Without Sampling
   ```bash
   python classification_without_sampling.ipynb
   ```

5. Run Unsupervised Models
   1. Data Processing
      ```bash
      python 1_Data_Processing.ipynb
      ```
   2. KNN Imputation (To Handle missing values)
      ```bash
      python 2_KNN_Imputation.ipynb
      ```
   3. Apply PCA and PCA with KMeans on the data
      ```bash
      python 3_PCA_KMeans.ipynb

           
