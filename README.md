# Data Science Salary Analysis with KNN and K-means Clustering
<img width="316" alt="submission_5282_5143_coverImage_en_US" src="https://github.com/user-attachments/assets/3fc86cc8-38d2-4655-9fdc-982554e8f91d">

## Overview
This project analyzes data science job salaries using two key machine learning techniques: **K-nearest neighbors (KNN)** for salary prediction and **K-means clustering** for identifying salary clusters. The aim is to gain insights into the factors influencing salary levels and to discover distinct salary patterns within the dataset.
Checkout the publication here: https://doi.org/10.37934/arca.35.1.1020

## Dataset
We used a publicly available dataset from Kaggle that contains data on data science job salaries:
- **Dataset**: [Data Science Job Salaries](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries/data)
  
This dataset includes information such as job title, company location, experience level, and salary in USD.

## Methodology
The analysis consists of two main approaches:

1. **K-Nearest Neighbors (KNN) for Salary Prediction**:
   - **Objective**: Predict salary levels based on job-related features.
   - **Description**: KNN is a supervised learning algorithm that identifies the K most similar data points to a given observation. By considering features like job title, experience level, and company location, KNN predicts the salary level based on the majority class of its neighbors.

2. **K-Means Clustering for Salary Segmentation**:
   - **Objective**: Identify distinct salary clusters within the dataset.
   - **Description**: K-means is an unsupervised learning algorithm that groups data points with similar characteristics into clusters. By applying this method, we aim to uncover hidden salary segments, offering deeper insights into how salaries are distributed across various job profiles.

## Key Findings
The project provides several valuable insights:

1. **Salary Prediction with KNN**:
   - By utilizing KNN, we can estimate salary levels based on features such as job title, experience level, and location. This analysis is useful for individuals and companies seeking to understand which factors most significantly affect salary variations in the data science field.
   
2. **Salary Clusters with K-means**:
   - K-means clustering reveals distinct salary groups, helping to identify patterns within the salary data. This clustering analysis provides insights into the typical salary ranges and their distribution across different job categories, levels of experience, and geographical regions.

## Visualization
The project includes several visualizations, such as:
- Heatmaps showing correlations between job features and salaries.
- Clustering visualizations highlighting the distinct salary groups.
- Salary distribution plots based on KNN and K-means outputs.


## Future Work
- **Model Improvement**: Further refinement of the KNN model using feature selection or hyperparameter tuning could enhance salary prediction accuracy.
- **Additional Analysis**: Applying other clustering algorithms or regression models (e.g., Decision Trees, Random Forest) to deepen the understanding of salary factors.

## How to Run
1. Clone the repository:
   ```
   git clone https://github.com/Chanzwastaken/DataScienceSalariesWithKNNClassificationAndKMeansClustering.git
   ```
2. Install the necessary dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```
   jupyter notebook
   ```
4. Run the analysis in the `ds_salaries_Final_Project.ipynb` file.

## Citation
If you use this project in your research, please cite the following publication:
- **Publication**: [Leveraging Correlation and Clustering: An Exploration of Data Scientist Salaries](https://doi.org/10.37934/arca.35.1.1020)
