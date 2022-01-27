# Online-Shopper-s-Intention

  TARGETING THE RIGHT CUSTOMERS USING CLASSIFICATION ALGORITHMS TO INCREASE REVENUE
# Business Problem:
   As a result of today’s knowledge-based economy and the information society, e-commerce is becoming increasingly popular allover the globe. The most common type being the Business-to-Customer trade, typically represented as online stores,displacing physical stores quickly (Suchacka & Chodak, 2016). The transitionfrom physical to online shopping can be inferred by numbers such as an increase in total retail sales in Germany of 3% in 2016, whereas the e- commerce sales rose by an estimated 12.5% to 58.52 billion dollars and are expected to exceed 86 billion dollarsat the end of 2021 (Retail Ecommerce in Germany: A Major Digital Market Growing in Size and Sophistication, 2017). The rapid growth of e-commerce has transformed the shopping process as a whole and along with it the traditional buyer-merchant relationships. This change is accompanied by challenges that companies need to address. 
 # Objective:
   The basic objective of the project is to analyse the customer’s behaviour in the shopping website data collect from the e-commerce website whether the customer will make some purchase or not and also the company will generate revenue by the customer or not. The dataset was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period. this would help the company to understand the customer’s activity and understanding the areas that company should make some more concentration to increase the  revenue by the customer.
# Dataset  and Attribute Information:
   The dataset consists of feature vectors belonging to 12,330 sessions and also having 10 numerical and 8 categorical attributes. The dataset was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period.
# Data Cleanings process:
   * Redundant Columns removal
   * data-type casting
   * missing values treatment 
   * lanbel encoding
# EDA PART:
   * Five Point Description : describe the numerical and categorical variables
   * Pair Plot , correlation : helps to find the relation between numerical variables 
   * Univariate,bivariate and multivariate Analysis : by Using [box plot,Count Plot,Bar Plots] to understand and the inference of the features.
 # VISUALIZATION PART 
  ## REVENUE AS PER MONTH 
   ![Screenshot (418)](https://user-images.githubusercontent.com/98252828/151322407-90fb2d49-a687-400c-ae6a-837ff68e26bf.png)
  Revenue is high for informational searches especially in the month of March and July 

  ## REVENUE DURING SPECIAL DAY
   ![Screenshot (419)](https://user-images.githubusercontent.com/98252828/151323353-27f5e785-de7f-490b-acd7-71f7c7f9541c.png)
     Special day has no impact on the number of visitors 
  
  ## VISITOR TYPE REVENUE
   ![VISITOR-TYPE](https://user-images.githubusercontent.com/98252828/151324615-9a34117f-a8c7-4a02-8c73-e873035b0432.png)
    RETURNING VISITORS MAKES MORE REVENUE THAN NEW VISITORS
  ## FEATURES ARE HAVING RELATION WITH REVENUE 
   ![REVENUE](https://user-images.githubusercontent.com/98252828/151325289-73b09b49-263d-43be-b521-73d48826fe39.png)

   * Revenue generated by administrative page is slightly high than revenue not 
generated by that page, shows the page is somehow Profitable, this is same 
with respect to information related page.
   * Respect to product related the revenue is neither profit nor loss. 
   * Revenue generated by high page value is slightly higher than revenue generated by the low page value.
 ## Complexity Observed 
   * class imbalance 
   * influence of outlier 
 ## Feature Selection 
   * Mann Whitney statistical Test for numerical features
   * Chi-Square Yate's Correction statistical Test for categorical features
 ## Base Model Performance 
   * model Perfomance metrics => Precision, Recall, Accuracy, ROC_AUC
   * Model selection – Precison and Recall Ranks
 
 
     ![base-model](https://user-images.githubusercontent.com/98252828/151338537-29122e6b-1d1e-4765-9e33-8617dd353ab0.png)

## Final Model Performance 
   * Model selection – Precison and Recall Ranks
   * Hyper parameter tuning - GridSearchCV
   * Final  – after boosting , bagging and stacking process 
 ![final-report](https://user-images.githubusercontent.com/98252828/151339592-f4b3eea3-9ab8-46d4-b1ae-35bccdd9becd.png)
     
     
     Among these stacked model performs well and it can be further moved to deployment.

## Conclusion
After training our dataset, testing it and using hyperparameter tuning to improve our models, we can conclude that the Random Forest and the AdaBoost are the best models we have to predict whether a client will make an online purchase or not. The accuracy score of both models was close to 90%, which means that both managed to correctly predict 90% of the cases. After stacking we get good predictions in models.
## Business Conclusion
   from this analysis ,it allows the owner to address the intention of customers 
while,imporving their webiste and also their marketing strategy. 


 
