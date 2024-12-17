# Lung Cancer Prediction
## Introduction 
Lung cancer is one of the leading causes of cancer-related deaths worldwide, primarily due to its late diagnosis and limited early detection methods. Early prediction and prevention of lung cancer can significantly improve patient outcomes and reduce mortality rates. Our group focus on three parts for this project. First, analyzing the association between different factors with lung cancer risk. Second, developing a predictive model for assessing lung cancer risk. Third, find the contribution of different variables to lung cancer

## Dependencies
-   Python **3.6+**

## Simplified Process
Step 1: Data acquisition
-   Study population was generated from patients with lung cancer, which included 1000 observations each for 24 variables(Kaggle.com).

Step 2: Data pre-processing
-   Detecting NA value and outliers using Z-score.
-   Assign the categorical variable risk level to 0, 1, 2.
   
Step 3: Data visualization
-   To effectively identifiy relationships within the data itself, a heatmap of all 24 features within the data is created.
-   Draw Lowess Plot and violin plot to more intuitively discover the relationship between covariates and independent variables.

Step 4: Prepare for machine learning
-   Divide the data set into two parts, 70% for training and 30% for testing, and set random state to 40.
-   Discovered that the output numbers of three levels are close to each other. Level (0,1,2) corresponding to (258,221,221) total 700, which means the
    training set is balanced.

Step 5: Create and train Multinomial Logistic Regression
-   Multinomial Logistic Regression is a statistical classification technique used to predict
    categorical dependent variables with more than two possible outcomes. It is an extension of
    logistic regression, which is typically used for binary classification problems.
-   Evaluate and Visulization
  <img src="C:/Users/zyq11/Desktop/Bios 625/MR_CI.png">
  




