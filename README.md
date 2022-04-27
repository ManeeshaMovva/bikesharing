# bikesharing

## Overview

Now that I have a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like me to do a bike trip analysis. 

For this analysis, I will use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, I will create a set of visualizations to show the length of time that bikes are checked out for all riders and genders, he number of bike trips for all riders and genders for each hour of each day of the week and the number of bike trips for each type of user and gender for each day of the week. Then I will create a story analysis to pitch to the investors. 

## Results:

![graph 1](https://user-images.githubusercontent.com/74915619/122993814-c08c8100-d375-11eb-9f8f-520dc69d33d6.png)

In this first visual, I graphed the length of time that bikes are checked out for all riders.  Most rides only lasted 5 minutes between stations, however there were longer and longer average rides that numbered into the tens of thousands. For example, 66,769 rides lasted 15 minutes, and 21,346 lasted 30 minutes.

![graph 2](https://user-images.githubusercontent.com/74915619/122994312-51635c80-d376-11eb-9997-b3a818ea431f.png)

In this visual, I graphed the length of time that bikes are checked out for each gender. To inspect how specific genders use this service, we can have a look at this visual. The majority of bike share customers are Males by more than a 3 to 1 ratio when compared to female usage. 

![graph 3](https://user-images.githubusercontent.com/74915619/122995961-490c2100-d378-11eb-9f05-dee2952576d8.png)

In this visual, I graphed the number of bike trips by weekday for each hour of the day as a heatmap. Since we’re dealing with dense data with overlapping data points, heatmaps would be a good option for representing the data. Predictably, the highest usage times are the classic work commuting hours of Monday-Friday 7am-9am and 5pm-7pm. We observe steady usage throughout the daylight hours on Saturday and Sunday. 

![graph 4](https://user-images.githubusercontent.com/74915619/123009119-23881300-d38a-11eb-93d6-aa95ab7e6f2a.png)

I created another heatmap similar to the one we just saw but for this, I filtered the data by gender. As you can see males are the predominant customer gender, however, an important finding is that females use this service at similar peak times and nearly as high frequency as males on the weekends. 

![graph 5](https://user-images.githubusercontent.com/74915619/122999331-21b75300-d37c-11eb-8018-c86c85db0ae2.png)

Last but not least, our final visualization shows the number of bike trips by gender for each hour for each day of the week as a heatmap. In this scenario, the following conditions determine who qualifies as a customer or a subscriber: 
    •	Customer: 24-hour pass of 3-day pass
    •	Subscriber: annual member
Subscriber customer type shows strong usage indicating the use by local population is popular. This will make for a cleaner environment and healthier people where bike sharing is provided. It would be a good consideration for young professionals when selecting a new residence. 



## Summary 

The visualizations created in Tableau for the bike-sharing program make it easier for the Investors to see exactly what they would be investing in and the smartest ways to go about marketing this program in Philadelphia. From the visualizations, we can conclude that the weekdays in the morning and evening are popular because professionals are waking up to either exercise prior to work or after work or commuting to work. The male gender makes up most of the population that are subscribers which is not a surprise at all as they bike more compared to their female counterparts. For a good return on investments, I would suggest marketing to fit professionals who are always on the go and if we want to focus on a gender, I’d suggest the male gender. 

One of the issues I found with this data is that analyzing one month of data is not an accurate representation of the data as bikesharing will be most popular during the months of spring and summer. I’d suggest using a year’s worth of data for the future for a more accurate analysis of how successful this program is in New York and to show how popular it could be in Philadelphia on a smaller scale considering it’s a smaller city compared to New York. 

Another issue I found that I’d like to fix within the program itself is the lack of gender identities. There are several ways to describe a person’s gender in today’s and should not be limited to just female, male and unknown. We should be most inclusive and provide all possible options and an “Other” option for people to type in their own identity if they don’t identify with what’s provided.  


[link to dashboard](https://public.tableau.com/app/profile/meesh3741/viz/BikeTrapAnalysisStory/Story1) 

