## Women's Shoe Price Data Analysis

The dataset is women's shoe price from Kaggle competitions. Dataset contains 33801 observations and 52 columns.Data include brand,price,merchants variables and other attributes of product. Using these features, the task is to predict the brand name.

### Data acquisition

The dataset is a csv file acquired from Kaggles competition Women's shoe prices.This is a list of 10,000 women's shoes and their product information provided by Datafiniti's Product Database.This is a sample of a large dataset available through Datafiniti.

### Data cleaning

Change all column names and values to lowercase. 
Remove null values using theshhold 0.5.
The data shape before removing null values (33801, 52) and after removing null vlues (33801, 24).
Fill the missing values.
Creating new columns for deeper analysis.

### Data pre-processing

Label encoding to change categorical values to numeric.
Visualizations to explore correaltions between variables.
Checking and removing outliers.
Splitting data set to train and test.70% train data and 30% test data.
normalize the train data set before applying machine learning using the sklearn StandardScaler.

### Machine learning models

Logistic Regression (LR)
Linear Discriminant Analysis (LDA)
K-Nearest Neighbors (KNN)
Classification and Regression Trees (CART)
Gaussian Naive Bayes (NB)
Support Vector Machines (SVM)

### Model Evaluation

Creating a plot of the model evaluation results and compare the spread and the mean accuracy of each model. There is a population of accuracy measures for each algorithm because each algorithm was evaluated 10 times (10 fold cross validation).

### Insights and business recommendations

Brands do not follow any particular price distribution.
Improve cross selling and upselling techniques by creating personalized recommendations.






 


 



