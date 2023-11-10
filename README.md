# Fetal-Health-Classification-with-Pyspark

## Overview
This project analyzes fetal health data using Apache Spark to demonstrate data processing and machine learning techniques. The analysis includes data preprocessing, sampling methods, and decision tree optimization.

## Data Source
The data is loaded into a Spark DataFrame from a table named `fetal_health`. The schema of the data is printed at the beginning of the analysis to understand the structure.

## Methods
The following methods are applied in the analysis:
- **Oversampling**: To address potential class imbalance, oversampling techniques are tested.
- **Random Sampling**: Random sampling methods are explored for creating balanced datasets.
- **Decision Tree Pruning**: Decision tree models are pruned to optimize performance.
- **Randome Forest**: Random Forest model is also tested to compare the results with Decision Tree.


## Results
Results from each method are documented in the notebook. The notebook includes:
- Counts of observations by `fetal_health` category.
- Comparisons of model performance with different sampling techniques.
- Evaluation of decision tree performance before and after pruning.


## Usage
To run this analysis, you will need:
- Apache Spark environment.
- Access to the `fetal_health` table or a similar dataset.

## Requirements
- PySpark
- Additional Python libraries used in the analysis.

## Acknowledgements
Ayres de Campos et al. (2000) SisPorto 2.0 A Program for Automated Analysis of Cardiotocograms. J Matern Fetal Med 5:311-318 [link](https://onlinelibrary.wiley.com/doi/10.1002/1520-6661(200009/10)9:5%3C311::AID-MFM12%3E3.0.CO;2-9)
