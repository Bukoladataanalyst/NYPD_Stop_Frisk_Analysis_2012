# NYPD_Stop_Frisk_Analysis_2012

🗽 NYC Stop, Question, and Frisk Data Analytics (2012)

This project analyzes the New York City Police Department’s 2012 Stop, Question, and Frisk (SQF) dataset using the CRISP-DM framework to uncover insights about fairness, effectiveness, and operational patterns in policing.

🧭 Objectives

Examine patterns in stop-and-frisk encounters for fairness and effectiveness.

Identify relationships between demographic, temporal, and behavioral variables.

Build and evaluate predictive models to estimate the likelihood of force usage.

🧰 Tools & Techniques

Languages: Python, SQL

Libraries: pandas, scikit-learn, mlxtend, matplotlib

Visualization: Power BI, Python

Machine Learning: Logistic Regression, Random Forest, KNN

Association Rule Mining: Apriori

Clustering: K-Means

📊 Summary of Analytical Insights
Method	Tools	Key Insight
Visualization	Power BI, Python	Stops concentrated in night hours, 75th precinct
Association Rules	Python (Apriori)	(Male, CS_LKOUT) → (CS_CASNG) Lift = 2.0
Clustering	K-Means	3 clusters by time & demographic
Prediction	Random Forest	Best ROC-AUC = 0.725
🧠 Key Findings

90% of stops involved males; over half involved Black individuals.

Stop frequency was highest at night and concentrated in specific precincts.

Behavioral cues such as “furtive movement” and “lookout” were top correlates of force usage.

The Random Forest model achieved the best performance, accurately predicting force application likelihoods.
