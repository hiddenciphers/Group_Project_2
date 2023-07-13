# Cryptocurrency Price Prediction and Backtesting
![ml_brain](resources/img/ml_btc.jpeg)

This repository contains two projects focused on cryptocurrency price prediction and backtesting: an LSTM-based User Interface which can be used to configure the LSTM model architecture & a more simplified Random Forest Regression Model. These projects utilise machine learning techniques to analyse historical cryptocurrency data and make predictions about future price movements.

## LSTM Price Prediction Model

The LSTM (Long Short-Term Memory) price prediction model utilises deep learning to analyse historical price data and forecast future prices of a given cryptocurrency. The model is implemented using Python and TensorFlow, a popular deep learning library. The LSTM architecture is specifically designed to capture long-term dependencies in sequential data, making it well-suited for time series forecasting tasks.

### The main features of the LSTM price prediction model include:

- **Data collection:** The model collects historical price data from the CoinGecko API, allowing it to analyse a wide range of cryptocurrencies.

- **Data preprocessing:** The collected data is preprocessed to remove missing values, normalise the values, and create input-output pairs for training the LSTM model.

- **Model training:** The LSTM model is trained on the preprocessed data, learning patterns and relationships in the historical price data.

- **Model evaluation:** The trained model is evaluated on a test dataset to assess its performance and accuracy in predicting future price movements.

- **Price prediction:** Once trained, the model can be used to make predictions on unseen data, providing insights into potential future price trends.

The LSTM price prediction model offers a powerful tool for cryptocurrency traders and enthusiasts to gain insights into price movements and make informed decisions.

## Random Forest Regression Model

The Random Forest Regression script utilises the Random Forest algorithm to build a regression model for cryptocurrency price prediction. Random Forest is an ensemble learning method that combines multiple decision trees to make predictions. This script is implemented in Python using the scikit-learn library, a popular machine learning toolkit.

### The main features of the Random Forest Regression model script include:

- **Data collection:** The script collects historical price and volume data from the CoinGecko API for a specific cryptocurrency.

- **Feature engineering:** The collected data is processed to create additional technical analysis features, such as moving averages and momentum indicators, which are known to be relevant for price prediction.

- **Data preprocessing:** The collected data is preprocessed by handling missing values, normalising the values, and splitting it into training and testing sets.

- **Model training:** The Random Forest Regression model is trained on the preprocessed data, learning patterns and relationships between the input features and the target variable (price).

- **Model evaluation:** The trained model is evaluated on the testing set to assess its performance and accuracy in predicting cryptocurrency prices.

- **Residual analysis:** The script analyses the residuals (differences between predicted and actual prices) to evaluate the model's performance and identify any systematic errors or anomalies.

The Random Forest Regression model provides a robust approach to cryptocurrency price prediction, leveraging a powerful ensemble learning technique to make accurate predictions.

## Repository Structure

The repository is organised as follows:

- `lstm` - Directory containing all information related to the LSTM project
  - `gif` - Directory containing LSTM project gifs
  - `img` - Directory containing LSTM project images
  - `lstm_analysis` - Directory containing LSTM analysis
  - `README.md`

- `resources` - Directory containing 2 sub-directories
  - `img` - Directory containing all images used in this README
  - `preparation` - Directory containing all information related to the preparation of the project
      
- `rfreg` - Directory containing all information related to the Random Forest Regression project
  - `img` - Directory containing all images in the RFREG directory README
  - `rfreg_analysis` - Directory containing all information regarding the Random Forest Regression analysis
  - `README.md`

- `src` - Directory containing the 2 source code notebook files
  - `LSTM_colab.ipynb` - [LSTM Google Colab Notebook](https://colab.research.google.com/drive/1dMSu6y9V8_WNO6aNxo5J6zQAjie0p0Ip?usp=sharing)
  - `RFREG_colab.ipynb` - [RFREG Google Colab Notebook](https://colab.research.google.com/drive/1gAgP_0-mxlyXMN1fhdp8RUmMCfh8sIwJ?usp=sharing)
  - `README.md`

## Usage

**To use the LSTM price prediction & backtetsing App or the Random Forest Regression Model:**

- Clone this repository to your local machine or utilise the Google Colab shared file links above.

- Open the respective notebook using Jupyter Notebook, [Google Colab](https://colab.google/) or any compatible environment.

- Follow the instructions in the notebook to run the code cells and execute the models. Make sure to have an active internet connection to fetch data from the CoinGecko API.

- Analyse the results, including model performance metrics, plots, and predictions, to gain insights into cryptocurrency price movements.

- Experiment with different parameters, features, or models to further improve the performance and accuracy of the predictions.

- The provided notebooks are well-documented and guide you through the entire process, from data collection and preprocessing to model training and evaluation.

## Dependencies

The projects in this repository require the following dependencies:

- Python 3.7
- TensorFlow
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- ta
- ipywidgets

You can install the required dependencies using pip or any other package management tool.

## Contribution
Contributions to this repository are welcome. If you have any suggestions, bug fixes, or additional features, feel free to open an issue or submit a pull request.

**Happy cryptocurrency price prediction and backtesting!**

![btc_prophet](resources/img/btc_prophet.png)