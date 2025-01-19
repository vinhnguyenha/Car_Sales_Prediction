# Enhancing Car Price Prediction with Supervised Machine Learning Regression Models 💻📖 📈

## 1. Project Overview
### 1.1 Objective:

<p>- The primary goal of this forecasting problem is to predict future car sales prices in the USA using <b>supervised machine learning regression models </b>. </p> 

<p>By analyzing historical sales data based on car features, we aim to develop accurate regression models that can effectively estimate car prices. </p>

### 1.2 Purposes of Sales Prediction:

<p>- Predict future sales performance to understand potential revenue. </p>
<p>- Enables better decision-making, resource allocation, and strategic planning.</p>
<p>- Informed decisions on launching new products, entering new markets, and hiring staff. </p>
<p>- Inventory Management: Predict demand to maintain adequate inventory levels. (e.g: during Sep-Dec, there is a high demand of customers in buying Toyota )</p> 
<p>- Marketing: Plan marketing efforts and budget based on sales predictions.</p>
<p>- Evaluate performance by comparing forecasted sales with actual results in order to adjust strategies and tactics to align more closely with market realities.</p>

### 1.3 A Brief On Improving Prediction Performance & Evaluation Criteria

<p>- <b>To achieve reliable and robust prediction performance, ensuring the dataset is clean and well-prepared is significant</b>. Data cleaning involves handling missing values, removing outliers, and normalizing data. Missing values can bias predictions, so techniques like imputation that handle missing data are essential. Outliers, which can skew results and affect model accuracy, need to be identified and removed. Data normalization, scaling features to a consistent range, is also crucial as it improves the model’s performance and convergence. </p>

<p>- <b>Feature engineering is another critical aspect that significantly influences prediction performance. This includes feature selection, where the most relevant features are chosen to enhance model performance and reduce overfitting</b>. Techniques such as correlation analysis, mutual information are used for this purpose. Additionally, feature transformation involves creating new features from existing data to better capture underlying patterns, such as polynomial features or interaction terms. Encoding categorical variables into numerical formats using methods like one-hot encoding or ordinal encoding is also necessary for machine learning algorithms to process the data effectively. </p>

<p>- <b>Finally, hyperparameter tuning is essential for optimizing the model’s performance</b>. GridSearchCV systematically explores a range of hyperparameter values to find the optimal combination, fine-tuning the model to improve its predictive capabilities. Evaluating the model using <b>Mean Absolute Percentage Error (MAPE) ensures accurate and reliable performance metrics</b>. </p>

## 2. Notebook Structure

- **Car Sales Prediction.ipynb** - This is where all codes for the main part of the analysis and regression machine learning models are.

- **train.csv** and **test.csv** - The datasets used in this project

- **data_dict.csv** - A csv file to define column in train and test datasets

- **States_shapefile folder** - **Only States_shapefile.shp** inside the folder used in this project. This file contains the actual map shapes for visualizing states in the USA.
