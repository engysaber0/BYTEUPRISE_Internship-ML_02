# BYTEUPRISE_Internship-ML_02
Build a model that analyzes factors such as genre, director, and actors using regression techniques to tackle the problem. Rating Prediction project provides an opportunity to delve into data analysis, preprocessing, feature engineering, ML modeling techniques. 
STEPS OF TASK:.............................

Data Loading and Preprocessing:

Loading the dataset


Handling missing values


Encoding categorical variables


Normalizing numerical features


Data Splitting:


Train-test split



Feature Engineering:

Feature creation
Feature transformation
Model Selection and Training:

Linear Regression
Decision Trees
Random Forest
Model Evaluation:

Mean Squared Error (MSE)
Mean Absolute Error (MAE)
R-squared (R²)
Predictions:

Making predictions on the test set
Visualization:

Plotting actual vs. predicted values
List of the techniques USED in the TASK:.........

Data Loading and Preprocessing

Loading Data:
pd.read_csv (Loading the dataset)
Dropping unnecessary columns (e.g., 'overview', 'user_id')
Handling Missing Values:
dropna (Removing missing values)
SimpleImputer (Filling missing values)
Encoding Categorical Variables:
LabelEncoder (Encoding categorical features)
Converting categorical variables to codes (astype('category').cat.codes)
Normalization:
Standardization or normalization steps (though not explicitly shown, it's common in preprocessing)
Data Splitting

Train-Test Split:
train_test_split from sklearn.model_selection
Feature Engineering

Feature Creation and Transformation:
Handling outliers using IQR (Interquartile Range)
Transforming categorical features using LabelEncoder
Imputing missing values using SimpleImputer
Model Selection and Training

Models Used:
LinearRegression from sklearn.linear_model
DecisionTreeRegressor from sklearn.tree
RandomForestRegressor from sklearn.ensemble
KNeighborsRegressor from sklearn.neighbors
Model Evaluation

Evaluation Metrics:
mean_squared_error (MSE)
mean_absolute_error (MAE)
r2_score (R²)
Predictions

Making Predictions:
predict method of the model
Visualization

Plotting and Visualization:
Histograms and KDE plots (sns.histplot)
Box plots (sns.boxplot)
Line plots (sns.lineplot)
Bar plots (sns.barplot)
Pie charts and count plots (sns.countplot, plt.pie)
WordCloud for text data visualization
