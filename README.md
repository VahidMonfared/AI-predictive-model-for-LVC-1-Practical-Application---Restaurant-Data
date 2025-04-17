## **Objective**
---------------------------
The goal of this problem is to develop a predictive model that can determine whether a customer will decide to wait for their food order or leave without placing the order, based on specific factors. This is essentially a classification task where the outcome is binary—either the customer waits (yes) or leaves (no).
To make this prediction, we use various input features or variables related to the dining experience. These might include expected waiting time, number of people in the queue, availability of alternative restaurants, estimated service time, customer hunger level, and other relevant factors. By analyzing patterns in the data and training a machine learning model on past customer behavior, we aim to predict future customer decisions in similar situations.
Such a model can be valuable for restaurants and food service providers, helping them identify situations where customer drop-off is likely and take proactive steps—such as reducing wait times or offering promotions—to improve customer satisfaction and retention.
-------------------------
## **Dataset Description**
-------------------------
- **Alt** - Is there a suitable alternative restaurant available?
- **Bar** - Whether the restaurant has a comfortable bar area to wait in.
- **Fri** - True if it's a Friday or Saturday.
- **Hungry** - Whether we are hungry or not.
- **Patrons** - How many people are there in the restaurant? Values are None, Some, and Full which are encoded as 0, 1, and 2, respectively.
- **Price** - The restaurant's price range.
- **Raining** - Whether it is raining outside or not.
- **Reservation** - Whether we made a reservation or not.
- **Type**- The kind of restaurant.
- **Wait Estimate** - The estimated wait time. Values are binned into four categories 0-10, 10-30, 30-60, >60. 
