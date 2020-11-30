# MindCare-Self-Harm-Prediction-Model

MindCare is my Final Year Undergraduate Research Based project which used Machine Learning to predict Self-Harm tendencies among Institute going students.
This project will only focus on the Machine Learning Implementation of the project. 
![Main Web Page](https://octodex.github.com/images/yaktocat.png)

## OverView
 Psychological Disorders like self-harm and depression are very common among the people in the age range of 15-30 years. The host category of this age range is mainly the institute going students as it affects their lifestyle and the efficiency of the students to perform well on academic fronts. If the situation persists, they might even commit suicide if they are not diagnosed at an early stage. Machine learning is a powerful tool for predicting such medical situations. Hence the research focuses on predicting whether an institute going student shows any self-harm tendencies. The dataset of 353 students was considered and analyzed for predicting the performance of the techniques used. This research has further applied seven machine learning algorithms and has compared their results on the dataset collected. Out of the seven, the best working algorithm considered on the dataset is the Random Forest Algorithm and hence the model was trained on it. In the model, the researcher's has considered twenty-five attributes out of which it has been reduced to thirteen attributes using random forest classifier feature importance method. Further using Stratified K Fold on the dataset the research has sampled the training data. In the end, fine-tuning the hyperparameters using Grid Search CV the classifier model is trained
For detailed information kindly refer the published Implementation Research Based Paper of this project.
<br><br>
[Trishala Ahalpara et al. ‘Self-Harm Prediction Model Using Machine Learning Technology’- 
 International Journal of Future Generation Communication and Networking Vol. 13, No. 1s, (2020), pp. 200-- 214]( http://sersc.org/journals/index.php/IJFGCN/article/view/17800)

## Technologies
* Jupyter Notebook- 6.0.2
* Python- 3.7.1
## Data Collection
In order to understand the roots and causes of self-harm tendencies there are various categories of attributes considered and types of questions asked based on demographic, personal, present and past experiences. The dataset collected for this research is based on the survey conducted among students in the age range of 15 to 30 years old. 

## Table of contents
1) Algorithms Experimented on Data Set
  * Data Cleaning
  * Feature Encoding
  * Gaussian Naive Bayes 
  * Stochastic Gradient Descent (SGD)
  * Logistic Regression 
  * K Nearest Neighbour  (KNN)
  * Decision Tree Classifier
  * Random Forest Classifier
  * Support Vector Machine (SVM)
  * Performance of Each Algorithm
2) Implementation using Machine Learning (MindCare_ML_code.ipynb)
  * Data Cleaning
  * Feature Encoding
  * Training the data set using Random Forest Classifier	 
  * A) Using Grid Search CV for best hyperparameters.<br>
  * B) Fine Tuning using Feature Importance to find out important features<br>
  * C) Selection Model for considering new case with curated features.<br>
  * D) Training a new Random Forest Classifier on the curated features.<br>
  * Confusion Matrix
  * Extra Trees Classifier Implementation
3) Data Visualization
  * ScatterPlot
  * Categorical Scatter Plot
  * Bar Charts
  * Cross Tab Bar Chart
  * Heat Map
  * Feature Importance Horizontal Bar Chart
  * Random Decision Tree Visualization
4) Manual Input Implementation 
![Main Web Page](https://octodex.github.com/images/yaktocat.png)
