# 4610Fa24Group4-2

**Team Name:**

Group 4

**Team Members:**

Lindsay Fleishman @LindsayFleishman

Jonathan Li @JonathanL02

Arti Girish @artig123

Anish Kapoor @a-kapoor731

Omar Meshaal @OmarMeshaal2004


**Description of Dataset**

We received our data from catalog.data.gov. This 23 by 188,091 dataset is specifically obtained from Montgomery County of Maryland from 2015 to 2024 and is the data for Crash Reporting. Reports details of all traffic collisions occurring on county and local roadways within Montgomery County.

Shows each collision data recorded and various other related data points related to each collision like weather conditions, car makes, speed limit, light, substance use, and many other variables. 

**Generated Questions & Their Importance**

Question #1: How does the severity of injuries in car collisions vary within a vehicle’s make? 

Importance: It is important to examine the injury severity of collisions within a manafacturer's car line as it would helps guid customers in making informed decisions about a vehicle’s safety. They can better understand which car manufacturer may offer better protection in the event of a car crash. Manafacturers can also benefit and use this data to enhance safety features within their car lines if the injury severity in their car crashes tends to be more severe rather than minor. Thus, this question is important for both the buyer and the seller of cars. Here, we’re looking at some of the top vehicle brands in the U.S. For each car make, we’ve broken down injury severity based on crash reports from our dataset. To focus specifically on injuries, we’ve filtered out "No injury" cases.



Question #2: Based on post-Covid monthly statistics, what is the forecast for the amount of crashes per month and the change in average speed limit?

Importance: Due to Covid-19, there was a drop in the amount of vehicles on the road. To ensure that this would not skew our forecasted data, we excluded all statistics from before the pandemic. It is important to see what months contain the most crashes so that drivers can avoid collisions and law enforcement knows what to expect each month. The change in average speed limit is important to note so that it can potentially be changed to eliminate future crashes or so that law enforcement knows what speeds to monitor.

**Manipulations Applied**

Excluding and filtering out extraneous data and outliers (ex: Longitude, Latitude, and null values).

Modifying the data and datatypes for spelling mistakes, uniformity, and standardization (ex: Vehicle Make misspelled).

Aggregating data to calculate values to find percentages and proportions.

This resulted in the data being more **organized**, **readable** and **valid**.

**Analysis and Results**

**Question 1**

Before making this table it was important to note that car brands like Honda and Toyota are among the most commonly owned vehicles, so we factored that into our analysis. We did this by calculating percentages within each car make (column-wise), to see how injuries are distributed for each brand. From this table, we observe that Audi shows the highest proportion of severe injuries, making it, statistically, the deadliest and most severe car to drive. On the other hand, Lexus has the lowest percentages of severe injuries, suggesting it may be the safest car to drive based on this table. Interestingly, this aligns with Lexus being recently named the most reliable brand by J.D. Power. 


**Question 2**

It is important to note that we analyzed this question post-Covid as there was a big drop due to less cars on the road, and we did not want this to impact the forecasting as it would be included and impact the future data. Our analysis worked best with linear regression as it showed the dips and peaks to crashes that were reported throughout the year; this also helped with forecasting in the future. It was interesting to note how the peak amount of crashes were at the end of the year between November and December, which can correlate to holiday season and potential driving under the influence, as well as more people on the road due to travel season. Another important aspect of the linechart is the pattern of February being the month every year with the least amount of crashes. Since this dataset is from Maryland, it makes sense that in February the number of crashes reported drops as February in Maryland is the worst weather conditions with blizzards. This leads to less people on the road, as well as minimal traveling with no holidays in that month, and less crashes occurring.
