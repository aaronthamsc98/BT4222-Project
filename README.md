# BT4222-Project

## Group Members:
Jerome Seah Jia Jun

Lim Qin Da

Ong Sijie Grace

Tham Shun Cong Aaron

You Jing
## Installing Requirements:
$pip install -r ./Requirements.txt

## About the Project
### Problem Statement:
Fast fashion is a serious environmental issue. The fashion industry contributes to nearly 10% of global carbon emissions (Earth.Org). More seriously, US$500 billion is lost annually due to under-wearing and failure to recycle clothing (Earth.Org). In particular, online shopping contributes to significant wastage. Many returned items are more often disposed of straight to landfills than resold, creating massive heaps of fast fashion wastage (The Guardian). 

To mitigate this issue, online clothing rental is a way to encourage sustainable shopping. Clothing rental is becoming increasingly prevalent. The global online clothing rental market is expected to grow at a CAGR of 8.89% over the next few years (Mordor Intelligence). Driven by increasing trends of eco-friendly fashion and a desire for greater fashion choices at affordable price points, APAC is expected to contribute to 44% of total growth (PRNewswire). 

Despite increasing preference towards online clothing rental, consumers continue to face common problems such as apparel misfits. 72% of customers indicated they had returned clothes online as they did not fit well (The Business Journal). This resulted in increased costs incurred due to size-related issue returns and lower customer satisfaction. For instance, the replacement of rented apparel with incorrect fits cost $12.95 in shipping and is only available within the first 48 hours after placing an order (Rent The Runway). This also results in lower revenue for online apparel rental shops. 

## Our Project's Initiative:
To alleviate environmental issues of fast fashion wastage while enabling 
- (1) Better revenue flow for online shops and 
- (2) Better shopping experience for customers at online apparel rental stores, <br>

Our group seeks to (A) analyse clothing rental data to uncover insights on clothes that do not fit and (B) use modelling to help consumer predict clothing fit, enabling convenience while they shop and allow online retailers to sustain revenue while reducing the detrimental impact on the environment. 

## Project Summary 
After cleaning the data, the variables were analysed to conduct a preliminary investigation of their influence on fit. As clothing fit is subjective, beyond exploratory data analysis, sentiment analysis and topic modelling was conducted, utilising NLP techniques to value-add to the models using unstructured data from customer reviews. The team trained 5 different classification models, namely Logistic Regression, Random Forest, Gradient Boost, AdaBoost, and XGBoost. The F1-score was used as the main evaluation metric, coupled with elapsed time to account for the real-time usability of a fit recommender system. The final chosen model uses XGBoost (TF-IDF) with feature selection and has the best F1-score score of 0.602, with a reasonable runtime of 28.0 seconds. To further value-add in the business process and expand the project’s use case beyond online clothing rental onto other e-commerce apparel websites, the team also explored further extensions of using RCA to enhance the model. 
