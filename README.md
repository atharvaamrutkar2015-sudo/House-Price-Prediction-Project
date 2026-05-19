# House Price Prediction Project

This project is a simple machine learning project where I built a system that can predict house prices based on different property details. The main goal of this project was to understand the complete machine learning workflow starting from data cleaning to final prediction.

In this project, I used a house dataset containing features like city, property type, number of bedrooms, bathrooms, garage capacity, floor area, lot area, furnishing status, condition of the property, and many other details. Using these features, the model predicts the estimated selling price of the house.

I started the project with data cleaning and preprocessing. I checked the dataset shape, column names, datatypes, null values, and overall dataset information. Missing values were handled properly, and incorrect datatypes were fixed before moving further.

After preprocessing, I performed Exploratory Data Analysis (EDA) to better understand the dataset. I used different graphs and visualizations like histograms, heatmaps, scatter plots, and boxplots to understand feature relationships, correlations, outliers, and the distribution of house prices.

Then I performed feature engineering by creating some new useful features such as:

* Total Area
* Total Bathrooms
* House Age

Categorical columns were converted into numerical form using encoding techniques so that the machine learning model could understand the data properly. Feature scaling was also applied before training the model.

For model building, I used Linear Regression from Scikit-learn. The dataset was divided into training and testing sets, and the model was trained using the processed data. After training, the model was able to predict house prices successfully.

One of the best parts of this project is that I also created a simple user input prediction system. The user can enter property details such as city, bedrooms, bathrooms, floor area, garage capacity, furnishing status, etc., and the model predicts the estimated house price based on those inputs.

This project helped me understand:

* Data preprocessing
* Handling missing values
* EDA techniques
* Feature engineering
* Feature scaling
* Encoding categorical data
* Regression models
* Model prediction workflow

Technologies used in this project:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

This project was built for learning and practice purposes to improve my understanding of machine learning and data science concepts.
