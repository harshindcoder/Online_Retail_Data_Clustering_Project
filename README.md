# Online_Retail_Data_Clustering_Project

## Overview
This project performs customer segmentation using K-means clustering on an online retail dataset. The goal is to identify different customer segments based on their purchasing behavior.

## Dataset
The dataset contains transactional data from an online retail store, including fields such as InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country.

## Requirements
- **pandas**: Data manipulation and analysis
- **matplotlib**: Data visualization
- **seaborn**: Statistical data visualization
- **scikit-learn**: Machine learning algorithms
- **openpyxl**: Excel file handling

Install the dependencies using the following command:
```bash
pip install pandas matplotlib seaborn scikit-learn openpyxl
```

## Features
1. **Data Preprocessing**: Handles missing values and removes duplicates.
2. **Feature Engineering**: Creates RFM (Recency, Frequency, Monetary) features.
3. **Outlier Detection**: Uses IQR to remove outliers.
4. **Scaling**: Standardizes features for clustering.
5. **K-means Clustering**: Implements K-means for customer segmentation.
6. **Visualization**: Plots clusters to interpret results.

## Project Workflow
1. **Import Libraries**: Load required Python libraries.
2. **Load Dataset**: Import data from Excel file.
3. **Data Cleaning**: Handle missing values and duplicates.
4. **Feature Engineering**: Calculate RFM metrics for customers.
5. **Outlier Removal**: Detect and remove outliers using the IQR method.
6. **Scaling**: Standardize features for clustering.
7. **K-means Clustering**: Determine the optimal number of clusters using the Elbow method and fit the model.
8. **Visualization**: Plot cluster distributions and interpret results.

## Results
The output includes visualizations of clusters and insights into customer segmentation based on purchasing behavior.

## Future Improvements
- Implementing hierarchical clustering and DBSCAN for comparison.
- Automating identifying customer label for future data by automation.
- Adding dashboards for interactive visualization.

## Resources  
- Online retail mining paper: [https://link.springer.com/article/10.1057/dbm.2012.17](https://link.springer.com/article/10.1057/dbm.2012.17)  
