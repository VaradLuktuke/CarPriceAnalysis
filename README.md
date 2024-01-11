# CarPriceAnalysis
### Abstract
The goal of this project is to predict car prices using machine learning techniques and evaluate the quality of the data using statistical tests. To achieve the goal, we will be using a dataset that contains information on various car features such as fuel type, mileage, and horsepower. We will preprocess the data, select relevant features, and then train and evaluate multiple machine-learning models. We applied statistical techniques and machine learning algorithms to identify the most important factors that influence car prices and developed a model that can predict the price of a car based on these factors. Our analysis showed that features such as fuel type, mileage, and horsepower are significant determinants of car prices. We will use statistical tests to determine the quality of the data and ensure the validity of our model.

### Introduction
As car and racing enthusiasts, we are particularly interested in analyzing and predicting car prices using statistical and machine-learning techniques. The automobile industry is a fascinating field that combines cutting-edge technology, engineering, and design. Pricing is a crucial factor in the industry, and predicting car prices accurately can be challenging due to the various factors that can affect them. We believe that by using machine learning and statistical techniques, we can develop models that can accurately predict car prices, providing valuable insights for both buyers and sellers.

In this project, we will be using a publicly available dataset containing information on various car features such as make, model, year of production, mileage, engine size, transmission type, fuel type, and other features. Our aim is to identify the most important factors that influence car prices and develop a model that can accurately predict the price of a car based on these factors.

##### Prior Research
There have been numerous studies on car price prediction using machine learning and statistical techniques. These studies have shown that features such as mileage, age, make, model, and engine size are essential determinants of car prices. Several machine learning algorithms, such as linear regression, decision trees, and random forests, have been used to develop predictive models. Additionally, statistical tests such as regression analysis, ANOVA, t-tests, and correlation analysis have been used to evaluate the quality of the data and the validity of the models.

##### Data Collection
We will be using a publicly available dataset containing information on various car features. The dataset was collected from various sources and contains data on thousands of cars from different manufacturers and models.

##### Data Preprocessing
To prepare the data for analysis, We will preprocess the data by removing missing values, outliers, and irrelevant features. We will also scale the data to ensure that the features are on the same scale and are comparable.

##### Feature Selection
We will select the most relevant features for our model using techniques such as correlation analysis, feature importance, and dimensionality reduction. We will identify the features that have the most significant impact on car prices excluding irrelevant features.

##### Machine Learning
We will train and evaluate multiple machine learning models such as linear regression, decision trees, and random forests. We will use cross-validation and hyperparameter tuning techniques to optimize the models' performance and ensure that they are not overfitting the data.

##### Statistical Tests
We will use statistical tests such as regression analysis, ANOVA, t-tests, and correlation analysis to evaluate the quality of the data and the validity of our models. These tests will help us identify any issues with the data and ensure that our models are accurate and reliable.





### Modelling
After conducting an exploratory data analysis (EDA), we recognized the significance of reducing the dimensions of the model by employing various model selection techniques. The inclusion of all predictors could lead to dimensionality problems, thus it is crucial to select only the most significant features for any machine learning project. In this project, we utilized three different models, including the full model with all predictors, the Recursive Feature Elimination (RFE) model, and the Akaike Information Criterion- Bayesian Information Criterion (AIC-BIC) model. However, while generating diagnostic plots, we identified a violation of assumptions. To overcome this issue, we conducted further investigations and concluded that Log transformation was the solution. Upon implementing Log transformation, we were pleased to discover that the assumptions were met, and we proceeded with the prediction phase of our model.
