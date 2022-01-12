# bikerentalprediction

The aim of this project is to predict the bike rental count on a particular time along with season, weather setting, and temperature. The advantage of predicting bike rental count will help the management to maintain exact number of bikes according to the seasons, weather conditions without losing the customers by lacking bikes.  

**Predictor Variables**
        Predictor
        instant
        dteday
        season
        yr
        mnth
        holiday
        weekday
        workingday
        weathersit
        temp
        atemp
        hum
        windspeed
        casual
        registered
        
        
       
 **Boxplot Analysis**
 ![Boxplot1](https://user-images.githubusercontent.com/46658606/109354580-ab7a6800-7843-11eb-9144-c308df68f0af.png)
 
 ![image](https://user-images.githubusercontent.com/46658606/109354646-c51baf80-7843-11eb-8dea-c7711f6d4f67.png)
 
 ![image](https://user-images.githubusercontent.com/46658606/109354706-d8c71600-7843-11eb-8c3c-6e370de742a3.png)

![image](https://user-images.githubusercontent.com/46658606/109354729-e086ba80-7843-11eb-9f77-f585b9622175.png)

![image](https://user-images.githubusercontent.com/46658606/109354760-e8def580-7843-11eb-95bb-c031b206f7f6.png)


**
**Data distribution of contiuous variables using histograms**

![image](https://user-images.githubusercontent.com/46658606/109354800-f98f6b80-7843-11eb-8f33-59df39f006d3.png)

![image](https://user-images.githubusercontent.com/46658606/109354823-fdbb8900-7843-11eb-8a41-59db71d91bdc.png)

![image](https://user-images.githubusercontent.com/46658606/109354833-0318d380-7844-11eb-8c86-8fdac40f3ffd.png)

![image](https://user-images.githubusercontent.com/46658606/109354844-07dd8780-7844-11eb-9041-eccf7c908bb0.png)

![image](https://user-images.githubusercontent.com/46658606/109354860-0ca23b80-7844-11eb-8ae8-9661a45b2a8e.png)

![image](https://user-images.githubusercontent.com/46658606/109354869-10ce5900-7844-11eb-9852-ef398c4438e1.png)

![image](https://user-images.githubusercontent.com/46658606/109354876-14fa7680-7844-11eb-96c7-71e5e96f5324.png)

![image](https://user-images.githubusercontent.com/46658606/109354896-1a57c100-7844-11eb-98d2-e1b90ceb403c.png)

![image](https://user-images.githubusercontent.com/46658606/109354920-1f1c7500-7844-11eb-83b0-3e23f565c52b.png)

The following inferences can be drawn from the data. it was seen that the number of registered users was overall higher compared to that of casual users. Specifically when classified by working days it was found that more number of registered bikes were rented on occasions when it was neither a weekend nor a holiday as compared to casual bike rentals which were more during situations (1) when it could have been a weekend or a holiday. This possibly helps us to have an understanding of purpose and type of bike rentals. Registered users might use bikes on a daily basis, example for work or other day to day activities where as casual bike rentals are associated with holiday and leisure.

The highest number of bike rentals were between the months of June and August, whereas the lowest number of bike rentals were between the months November and February. This gives us an indication about the role of corresponding seasons associated with these months. Furthermore, I also checked for total count of bike rentals across seasons which confirms that the highest rentals were during summer followed by spring, fall and lastly in winter.

Another important factor to understand the bike rental trends is temperature. There was not a significant difference between real temperature and feeling of the temperature. Total Temperature was significantly correlated with total bike rentals. Irrespective of the type of bike rental the temperature (real) was equally correlated with both casual and registered rentals. However, one important thing to mention again is that the registered users were higher overall compared to casual users, hence the results could be biased or misleading, but overall it seems like temperature plays an important role for total count. Furthermore, weather situation was found to be significant predictor of bike rentals. However,the impact of holidays is not significant. One reason for holidays not being significant could be that there were probably a very few holidays during the years for it to have a significant impact.







