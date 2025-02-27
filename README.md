# House-Price-Prediction-using-Linear-Regression-

Data Loading and Preprocessing:
Loads the dataset (e.g., Housing.csv).
Checks for missing values and handles them.
Encodes categorical variables into numerical format using LabelEncoder.

Data Visualization:
Creates scatter plots to visualize relationships between features (e.g., number of bedrooms, area, stories, bathrooms) and house prices.
Plots a histogram to show the distribution of house prices.
Generates a correlation heatmap to understand relationships between all features.

Model Building:
Splits the dataset into training and testing sets using train_test_split.
Builds a Multi Linear Regression model using LinearRegression from sklearn.

Model Evaluation:
Predicts house prices on the test set.
Evaluates the model using metrics like R-squared (R²), Mean Absolute Error (MAE), and Mean Squared Error (MSE).

Feature Importance:
Displays the importance of each feature in predicting house prices using regression coefficients.

Insights:
Provides insights into which features are most influential in predicting house prices based on the model's coefficients and correlation analysis.
