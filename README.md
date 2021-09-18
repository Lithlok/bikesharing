![carl-nenzen-loven-igKjieyjcko-unsplash](https://user-images.githubusercontent.com/85216568/133871744-671a1fbb-5ee8-4230-8bfa-55c6d089d051.jpg)
[Link to Dashboard](https://public.tableau.com/app/profile/jon.correll/viz/CitibikeUsageAnalysis_16319287829170/CitibikeUsagebyLocationWeekdayandGender#1)

# Overview of the Citibike bikeshare analysis: 
  
The analysis within this repository is a look at bikesharing data using Citibike data from New York City in August 0f 2019. This data is real data from the Citibike site archives. The following breakdown is a look at **Weekday usage, Gender usage, and Start and Stop locations**.
<br>

# Results: 
The following images were created in Tableau Public and use the Citibike CSV with the only modification being of the 'timeduration' column to a 'datetime' data type.
<br>

![Top Starting Locations](https://user-images.githubusercontent.com/85216568/133870170-0aae0af8-2002-4a44-8c06-8484c26aee72.png)
### Top Starting Locations: 
  At the start of the Tableau story, the image of Top Starting Locations is presented.
This shows a data point for each starting location of one of the bikes, with the geographical location in a pop-up. 
<br>

![Checkout Times by Week](https://user-images.githubusercontent.com/85216568/133870471-926b5d8c-3c60-4ef2-832d-bbddb77c33e2.png)
### Checkout Times by Week:
  The next page of the story is Checkout times by Week, which gives a ride duration broken down by hour and the filter options let the user select which length of ride to inspect. Shown here is Hour 0, 1 and 2. We have the most rides within the first frame due to the amout of rides being less than an hour long. **The peak is 5 minute duration, with a count of 146,752 rides for the month**.
<br>

![Checkout Times by Gender](https://user-images.githubusercontent.com/85216568/133870489-2f5d3b88-a8d5-4839-a315-3437bd0bf339.png)
### Checkout Times by Gender:
  Thirdly, we can see a similar line graph, with added filters for Gender included. This enables us to see that the vast majority are **Male riders with a 108,087 count on the 5 minute peak, compared to 34,151 Female riders, on the 6 minute peak**.
<br>

![Trips by Weekday by Each Hour](https://user-images.githubusercontent.com/85216568/133870607-d7d81e94-ff2a-4d67-91fa-fdc48edf1956.png)
### Trips by Weekday by Each Hour:
  Next we have a heatmap graph of rides within a week and broken down by time of day. We can see the most usage on the evening commute, followed by the morning commute. The busiest time for our bikes in on **Thursday from 5 PM to 7 PM**.
<br>

![Trips by Gender (Weekday per Hour)](https://user-images.githubusercontent.com/85216568/133870700-e8c31392-0c30-4829-a217-c966573ec31d.png)
### Trips by Gender (Weekday per Hour):
  Following the heatmap, we then break down the data by Gender. We can see that while Male and Female heatmaps differ in amount of rides, **they still follow the same pattern**. Weekday commutes and Weekend Lunch are our peak times for both genders, with Unknown gender showing the most use on the Weekends, giving the impression of guest users and/or tourists.
<br>

![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/85216568/133870806-ea0bd89f-29e4-49f0-9556-1fee76c8aec4.png)
### User Trips by Gender by Weekday:  
  Focusing on this thread, the next heatmap shows the difference between Subscribers and Customers. In the Gender bracket, the **highest Unknown Subscriber day is Thursday at 6,082 rides**. Comparing this to the **Unknown Customer section, we can see that the rides are between 12,632 (Wednesday) and 35,631 (Saturday)**.
<br>


![Top Ending Locations](https://user-images.githubusercontent.com/85216568/133870954-2b53dc54-c780-4c5e-900d-47ceea9e5d88.png)
### Top Ending Locations:
  Finally, we can see that we have some difference in the ending location data. We have several new locations in the **Jersey City/ Hoboken** area, with no starting data in these areas.
<br>

# Summary: 
  In summation, from the data and visualizations, we can see an interesting story emerge about the user data in NYC. We can see that the target customer is a Male commuter who lives and works within the city, with heavier emphasis on the evening commute. While the numbers are high, we also have a peak usage time per bike between 1 and 45 minutes. We can see from this information that more bikes within the central usage area would likely create more business, but also we can see the need for several bikes in outlying areas.
<br>

  The most obvious anomaly is in the heatmap on Wednesday afternoons, with the trips amounting to about half of Tuesday and Thursday. How can we discern the cause of this? I suggest creating a visualization centered around **extracurricular activities**. Is there a city function occurring on Wednesday nights? Happy Hour? Church services? More data is required.
<br>

  The next visualization I would add would be a look at the rates of **Customer vs. Subscriber**, and how to add these general users to the subscription service. I would also add locations at primary tourist attractions, and move bikes around the city on Friday centered around usage data. This would be effective in moving bikes into the city of Friday evening, and returning bikes to outlying neighborhoods on Sunday nights. 
