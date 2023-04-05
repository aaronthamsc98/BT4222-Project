# BT4222 Mining Web Data for Business Insights - Project

## Group 14 Members:
Jerome Seah Jia Jun

Lim Qin Da

Ong Sijie Grace

Tham Shun Cong Aaron

You Jing

## Requirements:

````
$ pip install -r ./Requirements.txt
````

If you are unable to pip install the pycld2 package, you can manually install it by downloading the package from here: 
```
https://www.lfd.uci.edu/~gohlke/pythonlibs/#pycld2
```

## Additional Notes
If you wish to not re-run the BERTopic Model initiation, you can download the saved model here:

```
https://drive.google.com/file/d/1HVruOS50XSvRlrvDkHQ6taZDuEX0iCXY/view?usp=share_link
```
The dataset is also zipped since Git Repo doesn't allow huge files!
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

## References
1. Misra, Rishabh, Mengting Wan, and Julian McAuley. "Decomposing fit semantics for product size recommendation in metric spaces." In Proceedings of the 12th ACM Conference on Recommender Systems, pp. 422-426. 2018.

2. Misra, Rishabh, and Jigyasa Grover. "Sculpting Data for ML: The first act of Machine Learning." ISBN 9798585463570 (2021).

3. Bizjournals.com. (n.d.). Retrieved March 30, 2023, from https://www.bizjournals.com/bizwomen/news/latest-news/2018/12/half-of-shoppers-expect-to-return-clothes-bought.html?page=all

4. Guardian News and Media. (2022, July 20). Past the parcel: How the end of free returns will change the way we shop | Sophie Benson. The Guardian. Retrieved March 30, 2023, from https://www.theguardian.com/commentisfree/2022/jul/20/end-free-returns-fast-fashion-online-shoppers

5. Igini, M. (2023, February 17). 10 concerning Fast Fashion Waste Statistics. Earth.Org. Retrieved March 30, 2023, from https://earth.org/statistics-about-fast-fashion-waste/

6. Online clothing rental market size & share analysis - industry research report - growth trends. Online Clothing Rental Market Size & Share Analysis - Industry Research Report - Growth Trends. (n.d.). Retrieved March 30, 2023, from https://www.mordorintelligence.com/industry-reports/online-clothing-rental-market

7. Rent The Runway. What if my one-time rental doesn't fit? (n.d.). Retrieved March 30, 2023, from https://help.renttherunway.com/en_us/what-if-my-one-time-rental-doesnt-fit-BkXV2enVU#:~:text=If%20one%20or%20all%20of,unable%20to%20provide%20a%20replacement

8. Technavio. (2022, April 25). Online clothing rental market size to grow by USD 3.00 bn: 44% of the growth to originate from APAC: Technavio. PR Newswire: press release distribution, targeting, monitoring and marketing. Retrieved March 30, 2023, from https://www.prnewswire.com/news-releases/online-clothing-rental-market-size-to-grow-by-usd-3-00-bn-44-of-the-growth-to-originate-from-apac-technavio-301531008.html
