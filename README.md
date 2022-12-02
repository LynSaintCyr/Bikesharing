# Bikesharing

## Overview

To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

Show the length of time that bikes are checked out for all riders and genders
Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## Resources 

Source Files: 201908-citibike-tripdata.csv, 201908-citibike-revised_tripdata.csv
Software: Tableau, Python 3.7.6, Jupyter NB, Pandas Library

## Results 
1) We analyzed the checkout times by users
we did that by selected 0,1,2 hours for this graph and graph clearly shows that there are no users with more than 60 minutes in August 2019.
![Checkout Times for Users](https://user-images.githubusercontent.com/107447648/205221360-5c173888-03eb-4770-b2e7-0acaf372955b.png)
 
 2) After that we added Still no trips for more than 60 minutes, but a huge percentage of the  riders were male, while female made up a small percent, and and the rest of the riders' genders were unknown but it was not a big amount.
 
 ![Checkout Times by Gender](https://user-images.githubusercontent.com/107447648/205222048-d9cde355-3855-4e79-93b2-edc79ec58a68.png)

3) We used a heatmap to show weekly usage patterns. By looking at the heatmao we can see the heavy bike usage during weekday commute times, and weekend usage is spread throughout the middle of the day.

![Trips by Weekday per Hour](https://user-images.githubusercontent.com/107447648/205222591-0131273c-3cb6-468d-98d7-050fc7d92368.png)

4) Then using that same heatmap we added Gender to the mix just to see which gender is using the bikes during these peak hours.

![Trips by Gender (Weekday per Hour)](https://user-images.githubusercontent.com/107447648/205222897-df0e1cba-80e4-46f6-b339-5315c631524a.png)

This map provides similar information as third and fourth maps, but this time we added usetype to the mix. This tells us that we have way more male subscribers compare to female, also we almost about the same share of male, female and other customers because as we can see the color for customer look similar.

![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/107447648/205223468-50d14460-f76c-4b54-9ed4-4a2607ae4059.png)


## Summary 

In conclusion, bikeshare services are very popular in busy metropolitan areas. The users of these bikes are mostly male subscribers. 
