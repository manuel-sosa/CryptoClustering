<p align="center">
  <img width="600" height="400" src="https://github.com/manuel-sosa/CryptoClustering/crypto_image.jpg">
</p>

# :money_with_wings: Module 19 Challenge - "Clustering Crypto" 

It is a comprehensive project focused on applying unsupervised learning techniques, specifically clustering, to analyze and predict cryptocurrency market behaviors. The challenge revolves around the hypothesis that cryptocurrencies can be grouped based on their 24-hour and 7-day price changes, using data-driven insights to uncover underlying patterns in the market.

<p align="center">
  <img width="600" height="400" src="https://github.com/manuel-sosa/CryptoClustering/elbow_curve.png">
</p>


## :bar_chart: Objectives: 

- **Data Preparation:** Load and prepare a dataset of cryptocurrency market data for analysis. This involves normalizing the data using StandardScaler to ensure that the model is not biased by the scale of the data.
- **Optimal Cluster Identification:** Utilize the elbow method to determine the optimal number of clusters (k) for the K-means clustering algorithm, based on the scaled dataset. This step is crucial for understanding the inherent groupings in the data without imposing assumptions.
- **K-means Clustering:** Apply the K-means algorithm to segment the cryptocurrencies into clusters. This process is performed twice: first on the original scaled data and then on the data transformed by Principal Component Analysis (PCA).
- **Dimensionality Reduction:** Implement PCA to reduce the dimensionality of the dataset while retaining the essence of the information. This step aims to optimize the clustering process and potentially reveal more defined groupings.
- **Visualization and Analysis:** Generate visualizations to compare the clusters formed from the original data and the PCA-reduced data. This includes creating scatter plots and elbow plots to visually assess the cluster groupings and the optimal number of clusters.
- **Evaluation:** Assess the impact of dimensionality reduction on clustering outcomes and the overall performance of the K-means algorithm. Analyze the explained variance by the principal components and discuss the implications for the clustering results.

## :chart_with_upwards_trend: Deliverables: 
- A Jupyter Notebook containing all the code, comments, and analysis. The notebook should systematically follow the steps outlined in the challenge, providing insights at each stage of the process.
- Visualizations to support the analysis, including elbow plots for determining the optimal k and scatter plots to visualize the clusters.
- A README file that summarizes the project, its objectives, methodologies, and key findings. This document should provide a clear overview of the challenge and serve as an entry point for anyone reviewing the project on GitHub.

## :wrench: Skills and Tools::hammer: 
- Python: For all data processing, analysis, and modeling tasks.
- Pandas and NumPy: For data manipulation and numerical operations.
- Matplotlib and hvPlot: For creating visualizations.
- scikit-learn: For implementing standard scaling, K-means clustering, and PCA.

## :mag_right: Project Significance: 
This challenge is designed to demonstrate proficiency in unsupervised learning techniques and their application to real-world datasets. It offers an opportunity to explore the dynamics of the cryptocurrency market through a data science lens, providing valuable insights into how cryptocurrencies can be categorized based on their performance metrics.
