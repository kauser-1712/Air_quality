# **Breathing the City: An In-depth Exploration of Delhi's Air Quality**
**Project Summary:**
- Data Preprocessing: We initiated the project by loading the air quality dataset, featuring essential parameters such as 'co', 'no', 'no2', 'o3', 'so2', 'pm2_5', 'pm10', 'nh3', and the target variable 'AQI'. The data preprocessing phase involved handling missing values, ensuring correct data types, and standardizing or scaling numerical features when needed. Additional features like 'Day_of_Week' were created from the 'date' column to explore weekly patterns in air quality.

- Data Visualization: Our exploration continued with data visualization techniques. We gained insights into the distribution of air quality parameters, AQI values, and potential relationships between features and the target variable. Various visualization methods, including histograms, scatter plots, box plots, and time series plots, were employed to uncover temporal patterns. Correlation analysis identified potential predictors for AQI.

- Linear Regression Model: For AQI prediction, we constructed a linear regression model using air quality parameters as input features. The data was split into training and testing sets to evaluate model performance. Post-training, the model's effectiveness was assessed using key metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score. The model demonstrated an R2 score of approximately 0.8551, indicating its ability to explain around 85.51% of the variance in AQI values.

**What's Next?**

While the linear regression model presents promising results, avenues for improvement exist. Potential enhancements include further feature selection or engineering, exploration of more sophisticated models, implementation of cross-validation techniques, and a thorough assessment of model assumptions. These steps aim to refine the model's accuracy and robustness, contributing to a more comprehensive understanding of Delhi's air quality.
