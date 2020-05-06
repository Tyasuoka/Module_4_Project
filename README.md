# Module_4_Project
# Project Title

**The Project:**
  For my module 4 project I chose to do a quick data analysis over a H1N1 flu vaccination dataset from a Datadriven competition.


**The Goal:**
  The focus of this project was study the behavioral patterns of those who got the vaccinations for the H1N1 virus and try to promote said behaviors to the generl public to follow. 


**The Problem:**

  * Certain behavioral patterns are hard to enforce
  * Not all people believe in the same thing
  * Not all people are capable of following the recommendations


**The Solution:**

  * Create a model that approximates likely behaviors of those who got the vaccinations
  * Promote those behaviors so everyone will be safe from future outbreaks
  * Prepaer for the next pandemic


**The Process**

The plan of attack was to do the following:
1. Explore & Clean data 
2. Model the data
3. Find the feature importances to list out to see which factors were the biggest contributors

***The Data:*** 

The data was provided by the Driven data Competition under the title "Flu Shot Learning: Predict H1N1 and Seasonal Flu Vaccines".

***The Metrics:*** 

The main metric used was ROC_AUC scoring.

***The Models Chosen:*** 

* The baseline model - Random Forest
* Other models used - Gradient Boosting, Logistic Regression

# Conclusion
* The biggest feature importances were the opinions of the individual if the vaccine was effective or not. Some of the other high impacting features were if the individual had health insurance or not and if they had any good behaviors prior to the spread of the virus like washing their hands.

# Future Recommendations
1. Gather more data to further analyze behavioral patterns
2. Apply feature engineering to improve model performance.
3. Take a psychological approach and see if anything changes.


# Repository Guide
***Notebooks***

Data Clean Up With Baseline Model: 

***CSV Files***

Original Data: 
Cleaned Data: 

**Presentation**
https://www.canva.com/design/DAD7cf_pXsc/Ldc6EKvxKc24pvs-FY2_WQ/view?utm_content=DAD7cf_pXsc&utm_campaign=designshare&utm_medium=link&utm_source=homepage_design_menu

# Resources

**The Data: Below is the direct link to our data source.**
https://www.drivendata.org/competitions/66/flu-shot-learning/page/210/


**Models: Below you will find model documentation**

*Random Forest:* https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html

*Decision Tree:*  https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html

*Logistic Regression:* https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html 
  
*Gradient Boost:* https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html
  
*AdaBoost:* https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html
  
 
 # Human Resources
 
 * My Last Data Bender Cohort 02/17/20 classmates 
 
 * Lindsey Berlin DS 02/17/20 Instructor
  
 * Bryan Arnold DS 002/17/20 Instructor
  
  
