# SpaceX Falcon 9 first stage Landing Prediction
Project background

➢ Space X advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars

➢ Other providers cost more than 165 million dollars each, much of the savings is because Space X can reuse the first stage. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. The goal of the project is to create a machine learning model to predict if the first stage will land successfully

Questions to be answered:

- How do variables such as payload mass, launch site, number of flights, and orbits affect the success of the first stage landing?
  
- Does the rate of successful landings increase over the years?
  
- What is the best algorithm that can be used for binary classification in this case?
  
Methodology:

1- Data Collection  

2- Perform data wrangling

3- Perform exploratory data analysis (EDA) 

4- Perform predictive analysis using classification models

5- Model Evaluation

Technologies Used

	• Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
 
	• Machine Learning: Logistic Regression, DecisionTree, Kneighbours,SVM
 
	• Google Colab
 
Conclusions:

• The larger the flight amount at a launch site, the greater the success rate at a launch site.

• Launch success rate started to increase in 2013 till 2020.

• Orbits ES-L1, GEO, HEO, SSO, VLEO had the most success rate.

• KSC LC-39A had the most successful launches of any sites.

• The Decision tree classifier is the best machine learning algorithm for this task
