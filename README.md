# Cryptocurrency Market Analysis

## Overview

This project aims to analyze cryptocurrency market data using various data analysis and machine learning techniques. The analysis includes data preprocessing, clustering using K-means algorithm, and dimensionality reduction using Principal Component Analysis (PCA).

## Project Structure

The project is structured as follows:

- **Code:** This directory contains all the Python scripts used for data analysis and modeling.
  - `Crypto_Clustering.ipynb`: Jupyter Notebook containing the code for data preprocessing, clustering, and PCA.
- **Resources:** This directory contains the dataset used for analysis.
  - `crypto_market_data.csv`: CSV file containing cryptocurrency market data.
- **README.md:** This file provides an overview of the project, instructions, and other relevant information.

## Requirements

To run the code in this project, you need the following libraries installed:

- pandas
- hvplot
- scikit-learn

## Usage

1. Clone the repository: 

```
git clone https://github.com/Commando1016/Crypto_Clustering.git
```

2. Navigate to the project directory:

```
cd Crypto_Clustering
```

3. Run the Jupyter Notebook:

```
jupyter notebook code/Crypto_Clustering.ipynb
```

4. Follow the instructions in the notebook to execute each code cell sequentially.

## Results

The project analyzes cryptocurrency market data, clusters cryptocurrencies using the K-means algorithm, and performs dimensionality reduction using PCA. Key findings include:

- Optimal number of clusters determined to be 4 using the elbow method.
- Clustering results visualized using scatter plots, showing distinct clusters of cryptocurrencies.
- PCA performed to reduce the dimensionality of the data, with a total explained variance ratio of approximately 89.5%.

## Conclusion

Cryptocurrency market analysis provides insights into the behavior and trends of various cryptocurrencies. Clustering and dimensionality reduction techniques help in understanding the similarities and differences between cryptocurrencies, aiding in investment decisions and portfolio management.
