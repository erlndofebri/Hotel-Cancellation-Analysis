# Hotel Cancellation Analysis
The objective of this project is to explore the insights about customer behavior on hotel cancellation 

Dataset Overview and Preprocessing 
1. This dataset contains of 119,390 rows and 29 features
2. It consist of 20 numeric features and 9 categorical features
3. This contains missing values in 4 features: children, city, agent, and company
4. We will impute 0 for children, company, agent and for city we will impute ‘unknown’ value
5. Replace ‘Undefined’ from meal feature with ‘No Meal’ as they both have the same meaning.
6. Drop the rows that contains data with 0 total_guests and 0 total_stays


## Insights :

![abcde task2](https://user-images.githubusercontent.com/106853320/185884857-5d7058c9-03fd-4020-911f-026c8234e4a5.png)


![cancelrate_leadtime](https://user-images.githubusercontent.com/106853320/185884870-377b823e-23a5-463e-a431-9ae560b2d5ce.png)


![cancelrate_stayduration](https://user-images.githubusercontent.com/106853320/185884889-257ef780-3798-456c-bac6-daef94c3ce4e.png)

## Summary :
1. Both hotels have more guests during the holiday season, and City Hotel has more guests than Resort Hotel. Need further analysis to make a strategy for leveraging revenue in holiday season

2. The longer total night booked, the higher the percentage of being cancelled, and the City hotel has a steeper trend compared to the Resort hotel. Positive trend on Total Night and Cancelation Rate for both hotels type, the hotels should apply a cancellation policy.
 
3. The lowest booking cancellation rate is for bookings with a waiting time of fewer than 30 days and it applies to both types of hotels.

4. Both resort and city hotels have the highest cancellation rate more than 1 year of lead time. The hotel could give reminders to them so that they would not cancel their reservation. Also, applying a cancellation policy on every reservation could help the hotel to prevent this from happening.

