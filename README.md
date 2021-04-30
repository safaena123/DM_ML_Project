# Data Mining and Machine Learning Project

In this project, we used the techniques learned throughout the data mining and machine learning courses and applied them to the Hotel dataset. We included in the Github repository the datasets used and notebooks containing the code for the models.

**Dataset Description:**

One of the hotels (H1) is a resort hotel and the other is a city hotel (H2). The dataset has 31 variables describing the 40,060 observations of H1 and 79,330 observations of H2. Each observation represents a hotel booking. Since this is hotel real data, all data elements pertaining hotel or costumer identification were deleted.

---
## Project Phases:
### Phase 1: Data Preprocessing: 
+ We used pandas to construct new features and turn categorical variables into dummy variables.
+ We created a dataset "hotel_data.csv" ready for the machine learning algorithms
### Phase 2: Exploratory Data Analysis:
+ We used pandas to create summary statistics of date variables, categorical variables and then numeric and integer variables.
+ We created a plot of the distribution of hotel type and cancellations, then a plot of the distribution of cancellations and number of adults
### Phase 3: Classification:
+ We trained three classification models; logistic regression, support vector machine and K nearest neighbors to predict cancellations. 
+ KNN had the best performance with an accuracy score of 96% and 96% precision.
### Phase 4: Clustering using K-Means:
+ We used K-Means algorithm for customer segmentation using three variables to see which segment presents more potential profit for the hotel. The number of clusters that gave the best silhouette score is 4.
