# SpaceX Falcon 9 first stage Landing Prediction
**Project background**

SpaceX’s Falcon 9 rocket launches cost around $62 million, significantly lower than other providers who charge over $165 million per launch. This cost-saving is primarily due to SpaceX’s ability to reuse the 
first stage of the rocket. By predicting whether the first stage will land successfully, we can better estimate the launch cost. This project aims to create a machine learning model to predict if the first stage will land successfully.

**Questions to be Answered**

How do variables like payload mass, launch site, number of flights, and orbits affect the success of the first stage landing?

Has the rate of successful landings increased over the years?

What is the best algorithm for binary classification in this scenario?

**Methodology**

Data Collection: Gather and prepare relevant data.

Data Wrangling: Clean and preprocess the data for analysis.

Exploratory Data Analysis (EDA): Analyze data trends and relationships.

Predictive Analysis: Apply classification models to predict the landing success.

Model Evaluation: Assess the performance of the models.

**Technologies Used**

Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Machine Learning: Logistic Regression, Decision Tree, K-Nearest Neighbors (KNN), Support Vector Machine (SVM)

Google Colab: For running the code and analysis

**Conclusions**

The larger the number of flights at a launch site, the higher the success rate at that site.

The success rate of launches started to increase from 2013 to 2020.

Orbits such as ES-L1, GEO, HEO, SSO, and VLEO had the highest success rates.

Kennedy Space Center (KSC) LC-39A had the most successful launches among all sites.

Decision Tree Classifier was identified as the best algorithm for this binary classification task.


