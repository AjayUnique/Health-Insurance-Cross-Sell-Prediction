# Health-Insurance-Cross-Sell-Prediction

## Problem Statement
Today, cars have grow to be a key device for land transportation, and their use as a method of residing is converting extra and extra. Cars are a not unusual place weapon and feature a break in that injuries as a result of banks are at the upward thrust together, ensuing in a huge boom in harm to lifestyles and property. Due to the fast increase of vehicles, coverage has grow to be a key enterprise goal of coverage organizations. It is important to enlarge new contracts with the aid of using obtaining new clients to boom enterprise performance. As dating promoting will become very essential, the acquisition of coverage and the preservation of rules with the aid of using present clients is a essential achievement element withinside the coverage industry. In the lengthy run, minimizing the conversion of present clients to different coverage organizations may be a advantageous trouble that will increase the earnings of organizations.
Coverage is an arrangement with the aid of using which an organization undertakes to offer a warranty of emolument for a chosen loss, damage, illness, or death in reciprocation for the price of a chosen top class. A top class is a sum of profit that the client needs to pay usually to an insurance organization for this warranty.

The dataset consists of these important features: -
1. ID: Unique ID for the customer
2. Gender: Gender of the customer
3. Age: Age of the customer
4. Driving License: whether the Customer has DL
5. Region Code: Unique code for the region of the customer
6. Previously Insured: Whether Customer already has Vehicle Insurance
7. Vehicle Age: Age of the Vehicle
8. Vehicle Damage: Whether a customer got his/her vehicle damaged in the past.
9. Annual Premium: The amount customer pays yearly for Insurance.
10.Policy Sales Channel: Anonymized Code for the channel of outreaching out to the customer i.e. Different Agents, Over Mail, Over Phone, In Person, etc.
11.Vintage: Number of Days, Customer has been associated with the company.
12.Response: 1: Customer is interested, 0: Customer is not interested

## Introduction
Cross-Selling is a brand new advertising method primarily based totally on information analysis, which located that exceptional desires exist as well, who can end up clients and meet their desires via income of diverse associated offerings or products.
We are utilizing the Logistic Regression algorithm, RandomForest algorithm and XGBClassifier for building different prediction models, RandomForest algorithm build nodes based on certain decision and hence can be very useful for random data that has no specific distribution. Logistic Regression is a parametric algorithm and hence certain properties are to be verified for good results. The Random Forest engenders decision trees on randomly selected data samples, gets predictions from each tree, and selects the best solution by means of voting. Here we have features like age, driving license, and vehicle age which is going to give a relationship with the response variable.

## Steps involved
## Exploratory Data Analysis
Exploratory data analysis (EDA) is utilized by statistics scientists to investigate and inspect statistics units and summarize their major characteristics, frequently using statistics visualization methods. It enables decide how exceptional to govern statistics reassets to get the solutions you need, making it less complicated for statistics scientists to find out patterns, spot anomalies, take a look at a hypothesis, or take a look at an assumption. 
* The number of male is greater than 200000 and The number of female is close to 175000. 
* The number of male is interested which is greater than 25000 and The number of female is interested which is below 25000.
* Male category is slightly greater than that of female and chances of buying the insurance is also little high.
* Young people below 30 are not interested in vehicle insurance. 
* Customers with vehicle age 1- 2 years are more likely to interested as compared to the other two. 

## Feature Engineering
Feature engineering is the method of selecting, manipulating, and reworking uncooked statistics into functions that may be utilized in supervised gaining knowledge. For the system to gain knowledge of carrying out nicely on new tasks, higher functions might also additionally want to be designed and trained. As you could know, a "feature" is any measurable enter that may be utilized in a predictive model - it may be the color of an item or the sound of a person's voice. Feature engineering, in reality, put, is the act of changing uncooked observations into preferred functions through the usage of statistical or system-gaining knowledge of approaches.

## Model building, Predictions, and Forecasting
## 1. Logistic Regression
Logistic regression is a sort of easy system learning that plays regression estimation on proportional, proportional, or specific data. Compared to more superior type and regression techniques, it's miles primarily based totally on a totally easy theory, however, probabilistic evaluation is viable for specific data. In different words, it's miles viable to expect the prevalence of a particular occasion via way of means of the use of an unbiased variable that has an immediate effect on the established variable. Using Logistic Regression we get accuracy of 78.3%.

## 2. Random Forest
Random Forest is a famous machine learning algorithm that belongs to the supervised learning technique. It may be used for each Classification and Regression issue in ML. It is primarily based totally on the idea of ensemble getting to know, that's a procedure of mixing a couple of classifiers to remedy complicated trouble and enhance the overall performance of the model. With Random Forest we got accuracy of 94.5%.

## 3. XGB classifier
XGBoost, which stands for Extreme Gradient Boosting, is a scalable, distributed gradient-boosted decision tree (GBDT) machine learning library. It provides parallel tree boosting and is the leading machine learning library for regression, classification, and ranking problems. XGBClassfier has given accuracy of 79.7%.

## Challenges 
Identify a highly imbalanced data set and manage it carefully.
Ensure that the model treats all groups fairly.Set prediction thresholds before deploying the model. After deployment, understand the behavior of the model on real data. It is difficult to perform predictive analysis for end users.

## Conclusion 

 • Males are 30% more likely to reply as   87.7% of clients spoke back as No to purchasing car insurance. It surely indicates that a maximum of the clients aren't interested in shopping for car insurance. 
 
 • Males are 30% more likely to reply as sure for car coverage than females. So business enterprises may want to attention greater on concentrated on male clients and do greater promotions centered toward the woman clients
 
 • Most of the clients have riding licenses and out of them, 12% are probable to reply as sure for car coverage.
 
 • There isn't any factor in attaining out to clients who have already got car coverage as nearly they all spoke back negatively about purchasing every other coverage.
 
 • 22% of clients who spoke back definitely do not have preceding coverage. So, the business enterprise ought to attention greater such clients as conversion opportunities are better in such cases.
 
 • Company ought to attention to clients whose car is greater than 2 years old, as 30% of instances they may be interested in shopping for coverage, which is large in comparison to different features.
 
 • Customers with cars aged much less than 12 months are least interested in insurance as at the same time as shopping for a car human beings frequently purchase 1 year coverage. Companies should not spend greater time on those clients as simply 4% of instances they may be probable to mention Yes for car insurance.
 
 • Customers who have broken their motors in beyond are greater sensitive toward shopping for car insurance. In truth 24% of instances, they spoke back definitely primarily.





