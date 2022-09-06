# Predicting-customer-churn-for-Model-Fitness

## Project Description
Model Fitness, a gym lost 26.5% of its customers in the present month. If the gym don't balance out this share by acquiring new customers, the company will become less profitable. As such, it is a no-brainer to develop strategies to prevent customer churn as well as possible. 

Model Fitness has digitized a number of its customer profiles. Your task as a data analyst is to:
* analyze the customer profiles and come up with a customer retention strategy.
* identify target groups.
* suggest measures to cut churn.

The very first step in this endeavour is to single out the warning signs that a customer will be lost.

A straightforward approach to solving problems like this is using modern Machine Learning techniques. In this report, I will guide the reader through the development of a classification model that enables Model Fitness to predict the probability of a customer to churn in the upcoming month. In the next step, I will divide our customers into five clusters which will allow us to develop group-based countermeasures based on the customers' specific risk profiles. Finally, I will present a set of possible actions that can be taken to reduce customer churn to a minimum.

## Data Description
`Churn` — the fact of churn for the month in question  
Current dataset fields: User data for the preceding month  
`gender`  
`Near_Location` — whether the user lives or works in the neighborhood where the gym is located  
`Partner` — whether the user is an employee of a partner company (the gym has partner companies whose employees get discounts; in those cases the gym stores information on customers' employers)  
`Promo_friends` — whether the user originally signed up through a "bring a friend" offer (they used a friend's promo code when paying for their first membership)  
`Phone` — whether the user provided their phone number  
`Age`  
`Lifetime` — the time (in months) since the customer first came to the gym

## Libraries Used
Pandas, Numpy, Matplotlib, Seaborn, Scipy, Sklearn, LogisticRegression, RandomForestClassifier, GradientBoostingClassifier, KMeans, Scikitplot 
