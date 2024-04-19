# CS361: Crop Recommendation System

**ML-PRAG**  
**Ajay Durgesam(210101038)  Arani Rajesh Kumar(210101020)  Gaurav(210101040)  Pratham(210101079)**

**Abstract:**  
Agricultural automation, essential in modern farming. Due to less space of domestic lands, it has become an important area of choosing the most suitable crops based on prevailing factors in the selected area. In the context of India, where agriculture contributes significantly to GDP and employs a large workforce, our research aligns with the goal of assisting farmers. By considering factors like soil nutrients, pH, humidity, and rainfall, various machine learning models including Decision Tree(DT), Support vector Machine (SVM), Logistic Regression(LR), and Gaussian Naïve Bayes(GNB) are employed to recommend crops that align with the dynamic nature of environmental factors. The model achieves high accuracy through trained sub-models, predicting the most suitable crops based on site-specific parameters. 

## Introduction

**Motivation-** Agriculture is a vital sector for the Indian economy and human survival, but it faces many challenges due to climate change, production loss, and farmer distress. Therefore, it is important to find ways to help farmers make informed decisions about their crops and increase their profitability and sustainability.

**Target problem-** The main problem addressed is how to recommend the most suitable crop for a given agricultural land based on various input parameters such as soil quality, weather, and crop yield.

**Major challenges-** 

- **Data availability and quality:** Lack of reliable and comprehensive data on crop production and environmental conditions in different regions and seasons of India..
- **Model accuracy and efficiency:** There are many factors that affect product quality and performance, and it is difficult to capture their complex interactions and differences using simple models. In addition, models must be able to handle large and diverse datasets and provide fast and accurate predictions..

## Methods

### Exploratory Data Analysis
we will start with EDA which is the initial phase of analysis which makes us understand the structure and pattern of the dataset.This also address data cleaning issues and explores the relationship between the variables.Overall this provides a foundation for further analyses.

### Data Preprocessing
After gaining insights from EDA,Data Preprocessing is conducted to identify and rectify errors or inconsistencies in dataset. This process includes handling missing values, addressing outliers, and ensuring data accuracy, quality and reliability.

### Feature Extraction
In this step, we choose the most relevant features (parameters) from the dataset to be used further. Feature Selection aims to improve the model's performance, reduce complexity by focusing on the most informative features. This include statistical tests, model-based methods, or algorithms that evaluate the contribution of each feature to the overall predictive performance.

### Machine Learning Algorithms
We will apply different ML Algorithms and compare their accuracies.These include:

#### Decision Tree
Mainly used for classification and regression tasks, providing a visual and interpretable representation of decision-making processes.

#### Support Vector Machine (SVM)
Primarily employed for classification tasks, aiming to find an optimal hyperplane for effective separation.

#### K-Nearest Neighbors (KNN)
Mainly employed for classification and regression tasks, relying on the proximity of data points in the feature space to make predictions.

#### Gaussian Naive Bayes
Commonly utilized for classification tasks, also in natural language processing and spam filtering, assuming independence between features.

### Hyperparameter Tuning
In this phase,we will systematically explore various hyperparameter configurations for each machine learning algorithm to optimize their performance. This involves leveraging techniques such as grid search or random search to find the most suitable hyperparameter values, enhancing the models' effectiveness in making accurate predictions.

### Result and Analysis
To compare the performance we will use different metrics such as Accuracy,Precision,F-measure and Recall.A comparative analysis will be conducted to evaluate the Performance of the models.The confusion matrix used to determine the performance of the classification models for a given set of test data.

## Intended Experiments

### Data Collection and Preprocessing
Our focus is on thoroughly understanding the dataset by using statistical methods and visualizations. Identify and address missing values, ensuring data completeness, and handle outliers. Additionally, key relationships between features will be visually explored for better understanding of Dataset.

### Model Selection
Implement Decision trees, SVM, Gaussian Naive Bayes and KNN.

### Model Evaluation
Divide the data into training and testing sets to evaluate the performance of the model.A comparative analysis will be conducted to evaluate the Performance of the models.

### Hyperparameter Tuning
Optimize hyperparameters using grid search or randomized search.
