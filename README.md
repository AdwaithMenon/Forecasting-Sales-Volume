# _**Sales Volume Forecasting : Developing a Predictive Model for Business Success**_


## **Project Description**

Favorita is an Ecuador-based business that specializes in supermarket retail. Our data set is taken from one of Kaggle's ongoing competitions that emphasize the importance of brick and mortar stores to estimate sales. 


The dataset includes data from various stores across the country as well as quantitative sales (sales volume) for all families (categories of items in the store) by date. The dataset also includes the number of items on promotion on a specific day at a specific store. Our goal is to forecast sales volume for the upcoming 16 days and use historical data to improve forecasts.


For brick-and-mortar retail stores, which must carefully balance how much inventory to acquire, sales volume estimates are critical. The stores are left with an excess of perishable goods if the forecasts are a little off. Accurate forecasting could help stores ensure they have just enough products at the correct time. If a store can match a product's demand with just the correct amount of supply, there will be no missed sales owing to a lack of inventory and no additional costs due to overstocking. Based on the estimates, the retailers would gain information on how to stock products, eventually retaining clients and ensuring consumer satisfaction. When it comes to perishable commodities, it is essential to ensure that there is enough and that nothing goes to waste owing to rising demand. Through this study, we also intend to assist Favorita in being profitable by examining the data based on the location . Depending on the forecasting model we ultimately select, some recommendations we would want to offer include optimizing the number of stores by boosting the number of items on promotion, implementing customer loyalty programs, and restructuring the staffing schedule.


We also believe that subjective forecasting approaches are insufficient for making decisions and must be supplemented with data science. As more products are introduced to the market and retailers strive to increase sales, complexity rises.



## **Model Comparison**

<img width="486" alt="image" src="https://user-images.githubusercontent.com/70052374/226159626-1c441e01-cab1-49b8-baa2-82296724f30a.png">


* Time Series Model in SAS gave the best results among the 5 models with an R2 of **0.663** and an MAPE of **0.127**.



## **Recommendations**

### **a) Optimizing Shelf Space**

* According to our data, the least sold products are those from the families of Hardware, Clothing, and Beauty. We advise giving shelf space for these products in accordance with the volume of sales. 

* The shelf space should be assigned in such a way that the best-selling products, such as Groceries and Beverages, are placed at the back of the store. Customers would travel inside the store to purchase these items because they are the most popular, and the least sold items, such as hardware and clothing, should be placed on shelves and aisles that can attract customers' attention (near the store's entrance) so that sales volume for these items can be increased.


### **b) Leveraging Number of Stores**

![image](https://user-images.githubusercontent.com/70052374/226159810-0fc64c63-b434-4a25-a726-fa72f734cc53.png)

![image](https://user-images.githubusercontent.com/70052374/226159826-0caf09eb-42cd-4f12-bc8f-cc36effb92b5.png)


* Despite having the second highest number of stores, the average sales for Guayaquil are lower than the average sales for Cayambe, Ambato, and Daule. 

* We discovered that this was due to a greater number of items on promotion for the cities of Cayambe, Ambato, and Daule. We would suggest stores in Guayaquil to increase promotions in order to leverage their store count within the city for increased sales volume. 



### **c) Thrifty Thursdays**

![image](https://user-images.githubusercontent.com/70052374/226160004-fcbd465a-8061-4cb8-a7f1-3c130f0ed456.png)


* Thursdays have the lowest average daily sales. The reason for this is that there are fewer promotions on Thursdays. 

* We recommend that stores launch a campaign such as "Thrifty Thursdays" to attract customers, where the number of items on promotion across all product families is highest on Thursdays, resulting in an increase in sales volume.


### **d) Reasonable Work Schedule**

* Revamping the staffing schedule is one method to cut labor costs. 

* For instance, compared to weekends, weekdays have lower sales volume. When opposed to weekends, we would recommend fewer active counters during the weekdays, which would result in lower overall labor costs


### **e) Customer Retention**

* As oil prices rose, we noticed a decline in sales volume (due to an increase in logistics costs). 

* During such inflationary periods, we would advise the stores to introduce membership-based loyalty or rewards programs, as this would encourage customers to make more repeat purchases from the same stores. Implementing such programs can significantly help stores to retain customers & maintain sales volume.


## **Conclusions and Future Work**


* When comparing results at the store level, our best model had the lowest RMSE when compared to most of the Kaggle submissions.

* With enhanced computational power, we can explore advanced models such as Recurrent Neural Networks (RNN) and Seasonal  Artificial Neural Networks (Seasonal-ANN) to improve forecasting accuracy.


