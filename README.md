# Data Analytics Projects
This repository contains three comprehensive data analytics projects, each addressing a different dataset and set of analytical tasks. Below are detailed summaries and insights for each project.

# Employee Churn Prediction
## Objective
Develop a classification model to predict employee churn based on various attributes like age, gender, credit score, and more. The goal is to understand the factors that influence employee turnover and to create a model that can accurately predict if an employee will leave the company.

## Dataset
The dataset includes attributes such as:
- CustomerId
- Surname
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited

## Steps Performed
- Data Exploration and Cleaning:
    - Checked for null values and duplicates.
    - Performed descriptive statistics to understand the data distribution.
- Exploratory Data Analysis (EDA):
    - Analyzed the distribution and relationships between variables.
    - Visualized key patterns and correlations using plots and charts.
- Feature Engineering:
    - Encoded categorical variables using one-hot and label encoding.
    - Scaled numerical features to ensure they are on a comparable scale.
- Model Training and Evaluation:
    - Trained various machine learning models: Random Forest, Logistic Regression, SVM, and KNN.
    - Evaluated models based on accuracy and F1-score.
    - Selected the best model (Random Forest) based on performance metrics.

# Hotel Reviews Sentiment Analysis
## Objective
Perform NLP preprocessing on hotel review texts to predict their star ratings. The goal is to understand customer sentiments and identify the most influential words and phrases that determine review ratings.

## Dataset
The dataset includes:
- Review: Text of the review.
- Rating: Star rating given by the customer (1 to 5).
  
## Steps Performed
- Data Cleaning and Preprocessing:
    - Removed non-alphanumeric characters and lowercased the text.
    - Tokenized the text, removed stop words, and applied lemmatization.
- Feature Extraction:
    - Used TF-IDF to transform text data into numerical features.
- Model Training and Evaluation:
    - Trained multiple classification models: Random Forest, Logistic Regression, SVM, and Naive Bayes.
    - Evaluated models using accuracy and F1-score.
    - Identified Logistic Regression as the most effective model for this task.

# Bestselling Books Analysis
## Objective
Analyze the dataset of bestselling books to uncover patterns and insights regarding user ratings, genres, and other key attributes. Additionally, build a regression model to predict user ratings based on features like reviews, price, year, and genre.

## Dataset
The dataset includes attributes such as:
- Name
-Author
- User Rating
- Reviews
- Price
- Year
- Genre
  
## Steps Performed
- Data Exploration and Cleaning:
    - Checked data types and null values.
    - Provided a statistical summary of the data.
- Exploratory Data Analysis (EDA):
    - Analyzed the distribution of user ratings, prices, and reviews.
    - Visualized user ratings by genre and trends over the years.
    - Explored relationships between reviews, user ratings, and genres.
- Data Visualization:
    - Created histograms for the distribution of ratings, prices, and reviews.
    - Used boxplots to compare user ratings by genre.
    - Visualized trends in bestselling books by year and genre.
    - Plotted scatter plots to analyze reviews vs. user ratings and prices.
- Regression Analysis:
    - Mapped genres to numerical values.
    - Built and evaluated a linear regression model to predict user ratings.
    - Interpreted the coefficients and visualized actual vs. predicted ratings.


# Dependencies
Ensure you have the following libraries installed:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- nltk (for NLP processing)
- text processing libraries (like re for regex operations)
