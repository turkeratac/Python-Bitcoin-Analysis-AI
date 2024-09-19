# Python Bitcoin Analysis AI
This python AI bot analyzes bitcoin's hourly closes

Project Introduction and Descriptions are Included in the .ipynb File

Kaggle : https://www.kaggle.com/code/turkeratac/bitcoinanalysisai

Dataset : https://www.kaggle.com/datasets/novandraanugrah/bitcoin-historical-datasets-2018-2024/data?select=btc_1h_data_2018_to_2024-09-06.csv

# Which Python libraries did you use in this project?

I used the Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn libraries in my project. These libraries were used for data analysis, model training, and visualization.

# Which models did you use?

I used Linear Regression and Decision Tree for supervised learning, and KMeans and DBSCAN for unsupervised learning.

# What do the differences in results indicate?

Supervised learning models predict a target variable, while unsupervised learning models find structural relationships by grouping data. The performance difference depends on the dataset and problem. Linear Regression was more successful due to the linear nature of the target variable.

#

# Top 10 Highest Bitcoin Opening Prices and Times (2018-2024):

<img width="523" alt="Ekran Resmi 2024-09-18 20 13 57" src="https://github.com/user-attachments/assets/8d9c814e-2179-4bc1-ab47-51fa4f931b3a">

#

# Correlation Matrix

A correlation matrix shows how different variables are related to each other. In Bitcoin analysis, it helps us see which factors, like price and volume, move together or in opposite directions. This is useful for understanding patterns and building better prediction models.

<img width="1097" alt="Ekran Resmi 2024-09-18 14 02 31" src="https://github.com/user-attachments/assets/8ed89f39-53ae-49cf-9f4a-8706b199ace9">

# 

# Unsupervised Learning Algorithms

The K-Means method allows data to be grouped into specific, discrete clusters. Each colored dot represents a data point within a cluster, while the red 'X' marks indicate the centers of these clusters. This clustering is influenced by the choice of the number of clusters, which should be set according to the data structure.

DBSCAN clusters data points based on their density and considers noise and density variations. If your data is very homogeneous or lacks distinct density differences, DBSCAN might create a single large cluster or classify most data points as noise.

As a result, based on the graphs, K-Means can provide better results by partitioning your data into more meaningful and distinct clusters.

<img width="1373" alt="Ekran Resmi 2024-09-15 16 13 17" src="https://github.com/user-attachments/assets/7d2e152b-9f23-4c14-b2a7-e45cee78cd90">

# 

# Supervised Learning Algorithms

After training and testing, Linear Regression has proven to be the best-performing algorithm. Since the model's performance is already very high, there is no need for further optimization or performance enhancement.

<img width="624" alt="Ekran Resmi 2024-09-15 16 13 36" src="https://github.com/user-attachments/assets/a8b2a8e1-a773-4810-b69b-19659e63ef55">

# 

# Loss Calculation for Regression

Model Evaluation - Loss Calculation for Regression

Mean Squared Error (MSE) measures the average of the squared differences between predicted and actual values, giving more weight to larger errors.

Mean Absolute Error (MAE) calculates the average of the absolute differences, providing a more straightforward measure of error without emphasizing large deviations.

<img width="699" alt="Ekran Resmi 2024-09-15 16 14 02" src="https://github.com/user-attachments/assets/3e51a55d-615a-4465-816f-e331e70c1601">
