## **Intent to buy Lead Prediction**

## Project Overview
There are various marketing touchpoints or paths a buyer encounter on their path to purchase. In fact, according to Flaherty, T. (2023) “there are on average 27 different communication touch points before a deal is won”. This becomes even more difficult when dealing with an account (company) rather than an individual. Marketing is responsible for running various campaigns across multiple channels to generate leads that potentially get converted into won opportunities by Sales. How can marketing as a function effectively measure its value contribution to the organisation in an industry where 78% of generated revenue comes from existing client's through (cross sell and upsell) Flaherty, T. (2023)?

Why Machine Learning

Currently the industry wide adopted process is as shown below.

Marketing is responsible for lead generation and nurturing.
Manual Lead scoring-based system to apportion points to leads based on engagement levels.
Sales to receive leads from that achieved a scoring threshold from marketing.
Sales to create opportunities and close deals.
This is a linear process that does not consider existing client’s and that around 82% of buying decisions are made up of buying groups (3 or more making buying decisions for a business) thereby underestimating marketing value contribution (Flaherty, 2023).

A model that predicts purchase intent from downstream marketing activities and customer segment is needed to attribute multiple marketing effort against an opportunity.

## Context & DATA
X Education, an online course provider for industry professionals, attracts numerous visitors daily who explore their offerings. These potential customers, or leads, are sourced from various marketing channels like websites and search engines. Upon showing interest, such as filling out a form or watching videos, they are classified as leads. However, the current lead conversion rate of around 30% is unsatisfactory. To enhance efficiency, the company aims to pinpoint "Hot Leads" with higher conversion potential. By prioritizing communication with these leads, they anticipate boosting the conversion rate closer to 80%. This entails implementing a lead scoring model to identify the most promising leads for targeted engagement.

This model underwent training using an existing lead scoring dataset https://www.kaggle.com/datasets/amritachatterjee09/lead-scoring-dataset, comprising 9240 record and 37 columns. It encompasses 14 characteristics associated with health and sleep, including data on race/ethnicity, gender, and age. For further specifics, please refer to the Data Sheet.

## MODEL 
We have trained a Decision tree classifier, Random Forest classifier and adaboost classifier. These machine learning algorithm are supervised learning suitable for classification problems such as this. They are versatile, simple and easy to interpret.

In initial tests, the Decision tree model performed best out of the 3 model with an accurary of 80.3% on the validation set.

## RESULTS
After training three classifiers – Decision Tree, Random Forest, and AdaBoost – and evaluating them on the validation set, the following results were obtained:

Decision Tree Classifier: Achieved the highest performance with an accuracy score of 80.3% on the validation set.
Random Forest Classifier: Yielded an accuracy score of 77% on the validation set.
AdaBoost Classifier: Showed a performance close to the Decision Tree Classifier, with an accuracy score of 79% on the validation set.
Overall, the Decision Tree Classifier outperformed the other models, demonstrating its effectiveness in this particular task.

<img width="416" alt="image" src="https://github.com/jsphlaw/leadmanagement/assets/167654027/8697aa37-c3d8-4915-88d3-5e0ffe8376fc">


You can include images of plots using the code below:
![Screenshot](image.png)

## (OPTIONAL: CONTACT DETAILS)
If you are planning on making your github repo public you may wish to include some contact information such as a link to your twitter or an email address. 

