# Alibaba Group Holding Ltd (BABA) | Stock Market Prediction

**This is still draft repositories, I working on code and other things outside Github.<br>
I'm sorry for the inconvenience from unfinished page.

## Table of Contents

- **1.** [Installation](#installation)
- **2.** [Project Motivation](#motivation)
- **3.** [File Descriptions](#desc)
- **4.** [Results](#results)
- **5.** [Acknowledgments](#acknow)

## 1. Installation <a name="installation"></a>

I developed this project using Python 3.11.3 and list libraries that I've been used are:

    - pandas
    - numpy
    - matplotlib.pyplot
    - sklearn.preprocessing.MinMaxScaler
    - tensorflow
    - tensorflow.keras.callbacks.EarlyStopping
    - sklearn.metrics.mean_squared_error
    - sklearn.metrics.mean_absolute_error
    - sklearn.metrics.r2_score
    - sklearn.metrics.mean_absolute_percentage_error

These libraries have been used for various purposes throughout the project, including data analysis, visualization, model training, and evaluation.

## 2. Project Motivation <a name="motivation"></a>

In this stock price prediction project for Alibaba Group Holding Ltd (BABA). I aim to forecast the future stock prices based on historical data. By utilizing a LSTM (Long Short-Term Memory) neural network model, we can make predictions and evaluate the accuracy of the model's performance. Here are the key questions to address:

- Q1: How accurately can we predict BABA stock prices using the available data?
- Q2: How well does the predictive model perform in identifying upward or downward trends in stock prices?
- Q3: Can we optimize the predictive model to improve its accuracy and reliability?

To measure success of this project, I'll consider following criteria:

- Clear answers to all questions listed related to BABA stock price prediction.
- Development machine learning model that can predict BABA stock prices based on available data.
- Improvement on predictive model to achieve better accuracy in predicting stock prices.
- Evaluation model performance in identifying BABA stock prices.
- Summarize model effectiveness and recommendations to improve the prediction accuracy.

By obtain valuable insights and develop reliable predictive model, we'll aim to make informed decisions in forecasting stock prices.

## 3. File Descriptions <a name="desc"></a>

- Jupyter Notebook that contain work related for this project was uploaded using `.ipynb` file.
- If you would like to access the datasets to explore more analysis & improve model performance, you can find `BABA.csv` file.
- To access all details about project workspace and datasets that I mentioned above, you can find `Stock_Market_Prediction.ipynb`.

## 4. Results <a name="results"></a>

**Q1: How accurately can we predict Baba stock prices using the available data?**

The LSTM predictive model displayed promising accuracy in predicting Baba stock prices. The evaluation metrics, such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE), showed relatively low errors, indicating that the model's predictions were close to the actual stock prices. Additionally, the high Coefficient of Determination (R^2) suggested that approximately **92.48%** of the variance in the actual stock prices could be explained by the predicted prices. This indicates that the model performed well in capturing the underlying patterns in the stock price data.

**Q2: How well does the predictive model perform in identifying upward or downward trends in stock prices?**

The model's directional accuracy which measures the percentage of correctly predicted upward or downward trends in stock prices, was around **60.24%**. This shows that the model's able to identify correct direction of stock price movement about **60.24%** of the time, there is still room for improvement in this aspect. Enhancing the model's directional accuracy could be achieved through further fine-tuning and optimization of the LSTM architecture or incorporating additional features that may better capture market trends.

**Q3: Can we optimize the predictive model to improve its accuracy and reliability?**
​
Yes, we can optimize the predictive model to further improve its accuracy and reliability. There are several approaches to achieve this:
​
- Fine-tuning hyperparameters: Tuning hyperparameters such as the number of LSTM layers, number of units per layer, dropout rate, and learning rate can lead to improved model performance.
​
- Feature engineering: Selecting and engineering relevant features that better capture the dynamics of stock prices could enhance the model's predictive capabilities.
​
- Data augmentation: Expanding the dataset by augmenting existing data or incorporating external data sources can provide the model with more diverse patterns and trends, leading to better predictions.
​
- Model ensembling: Combining predictions from multiple models or using ensemble techniques, such as stacking or bagging, can improve the overall predictive power.
​
By continuously testing and improving these aspects, we can make the LSTM predictive model better at forecasting Baba stock prices.

## 5. Acknowledgments <a name="acknow"></a>

- The Datasets used in this project's provided by [Steven Van Ingelgem](https://www.kaggle.com/datasets/svaningelgem/nyse-100-daily-stock-prices?select=BABA.csv).
- This project's completed by Bernhard A. Alphama.
