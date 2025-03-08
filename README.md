Zomato Bangalore - EDA, Geospatial Insights, and Predictions

Overview

This project performs Exploratory Data Analysis (EDA) and geospatial visualization on the Zomato Bangalore dataset to analyze restaurant distribution, popularity, and customer preferences. Using GeoPandas, we mapped high-density restaurant areas and customer hotspots. Additionally, we developed an interactive heatmap and a predictive model using Optuna to estimate restaurant ratings.

Key Features

Data Preprocessing:

 - Handled null values and outliers to clean the dataset.
 - Extracted latitude and longitude from addresses using geocoding for geospatial visualization.

Geospatial Analysis:

 - Used Folium to create interactive maps to visualize hotspots of restaurants.
 - GeoPandas played a crucial role in exploring geographical distributions.

Data Visualization:

 - Implemented various charts and graphs to extract meaningful insights from the dataset.
 - Chose visualizations that best fit the dataset to make strong inferences.

Machine Learning Model

 - Regression Model: Predicts the rating of a particular restaurant.

Feature Engineering:

 - Converted necessary categorical columns into numeric values.
 - Applied StandardScaler for feature scaling.
 - Feature Selection: Used Lasso Regression to select important features.

Model Optimization:

 - Implemented Optuna for hyperparameter tuning.
 - Used Random Forest and XGBoost models.

Performance: Achieved an R² score of 0.9259.

Technologies & Libraries Used

 - Python
 - Pandas, NumPy (Data preprocessing)
 - Matplotlib, Seaborn (Visualization)
 - GeoPandas, Folium (Geospatial analysis)
 - Scikit-learn (ML modeling & preprocessing)
 - Optuna (Hyperparameter tuning)
 - XGBoost, Random Forest (Machine Learning models)

Geospatial Analysis:

 - Identified key restaurant hotspots in Bangalore.
 - Interactive maps helped locate high-density areas.

Machine Learning Model:

 - Achieved high accuracy with an R² score of 0.9259.
 - XGBoost and Random Forest performed well after hyperparameter tuning.

Future Improvements

 - Enhance dataset by incorporating real-time reviews.
 - Deploy the model as an API for real-time rating prediction.
 - Experiment with deep learning models for better accuracy.

Contributing

Feel free to fork the repository and submit pull requests to improve the project!

License

This project is open-source and available under the MIT License.
