## How to Run

To run the code in this project using Google Colab, follow these steps:

1. Open Google Colab ([colab.research.google.com](https://colab.research.google.com)).
2. Create a new notebook or download and open an existing notebook.
3. Import or install the necessary libraries.
4. Run the notebook to display output.

# Libraries required
!pip install pandas numpy seaborn matplotlib mlxtend<br>
from sklearn.preprocessing import Normalizer<br>
from sklearn.cluster import KMeans<br>
from sklearn.metrics import accuracy_score, confusion_matrix<br>
from sklearn.decomposition import PCA<br>
import pandas as pd<br>
import numpy as np<br>
import seaborn as sns<br>
import matplotlib.pyplot as plt<br>
from adjustText import adjust_text<br>
from collections import Counter<br>

# Masters Project Overview
This project is a part of the Masters Project for Baylor University. This project analyzes hormone and immune biomarkers to predict future drinking patterns for Non Human Primates (NHPs)

# Primates Analysis
This project analyzes hormone and immune data from primates to study the effects of alcohol consumption on the endocrine and immune systems. It includes data distribution analysis, correlation analysis, and K-Means clustering.

## Data Distribution
The initial data analysis includes the examination of age, drinking category, and sex distributions of the NHPs.

## Correlation Analysis
The correlation analysis investigates the relationships between different biomarkers using a correlation heatmap. Highly correlated pairs of features are identified and highlighted.

## K-Means Clustering
K-Means clustering is performed on the data to identify distinct clusters based on selected biomarkers. The clusters are visualized using PCA projection and annotations for modified ID, sex, and drinking category. Misclassified points are marked with cross symbols. The accuracy of the clustering is evaluated, and feature importances are presented.

## Confusion Matrix
A confusion matrix is generated to assess the performance of the K-Means clustering. The matrix provides insights into the correct and misclassified predictions.

## File Structure
- `data_path`: Path to the data file used for analysis.
- Libraries: Importing necessary libraries for data analysis, visualization, and machine learning.
- Data Distribution: Analyzing the distributions of age, drinking category, and sex of NHPs.
- Correlation Analysis: Investigating the correlation between biomarkers using a heatmap.
- K-Means Clustering: Performing K-Means clustering on the data and visualizing the results using PCA.
- Confusion Matrix: Evaluating the performance of the clustering using a confusion matrix.

Please refer to the code and comments for detailed information on the implementation and specific steps.
