# Random Forest Regression
![random_forest_logo](img/random_forest_logo.png)

This repository contains a Google Colab notebook that demonstrates the implementation of Random Forest Regression for predicting cryptocurrency prices. The notebook showcases the steps involved in data preprocessing, model training, evaluation, and result interpretation.

## Overview

The Random Forest Regression notebook provides a practical example of using the Random Forest algorithm to predict cryptocurrency prices. It demonstrates how to collect historical price and volume data from the CoinGecko API, preprocess the data, engineer relevant features, and train a Random Forest Regression model using scikit-learn. The notebook also includes visualisations to interpret the results, such as scatter plots, histograms, learning curves, and feature importances.

## Installation

To run the notebook, you can utilise the Google Colab [shared link](https://colab.research.google.com/drive/1gAgP_0-mxlyXMN1fhdp8RUmMCfh8sIwJ?usp=sharing).

You will need the following dependencies:

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- plotly
- ta (Technical Analysis library)

You can install the required dependencies using pip:

```
!pip install pandas numpy matplotlib scikit-learn plotly ta
```

## Dataset

The notebook utilises historical price and volume data from the CoinGecko API. It retrieves data for a specified cryptocurrency and time period, considering daily intervals. The dataset includes columns such as timestamp, price, volume, daily change, market cap, and various technical analysis features.

## Notebook Content

The Random Forest Regression notebook consists of the following sections:

- **Data Retrieval:** Fetching historical price and volume data from the CoinGecko API.

- **Data Preprocessing:** Cleaning the data, handling missing values, and feature engineering.

- **Exploratory Data Analysis:** Visualising the relationships between variables.
Model Training: Splitting the data into training and testing sets, preprocessing features, and training a Random Forest Regression model.

- **Model Evaluation:** Calculating performance metrics such as MSE, RMSE, MAE, and R-squared.

- **Interpretation of Results:** Explaining how to interpret the learning curve plot, residual plot, histogram of residuals, scatter plot, and feature importances plot.

## Results

The Random Forest Regression model demonstrates strong performance on the cryptocurrency price prediction task. The evaluation metrics indicate a low mean squared error (MSE), root mean squared error (RMSE), and mean absolute error (MAE). Additionally, the R-squared score suggests a high proportion of variance in the target variable predictable from the features.

The accompanying visualisations, such as scatter plots, histograms, learning curves, and feature importances, provide insights into the relationships between variables and the importance of different features in the model's predictions.

## Contributing
Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License
The Random Forest Regression notebook is released under the Group 1 License. You are free to use, modify, and distribute the code for personal and commercial purposes.

