# Ford GoBike System Data Exploration
## by Ikechukwu Chilaka

## Dataset
> This data set is 37.5MB in size and includes information about individual rides made in a bike-sharing system for the period in February 2019, covering the greater San Francisco Bay area. The data was provided by Udacity as a CSV file
link: [https://video.ud]acity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv]. Wrangling steps used involved extracting hour and period of day, as well as subsetting for a clearer view

>A final subset of the data containing top ten stations with trip duration max of 2000secs was carved for last analysis. Customer trip is set as 30mins(1800secs) which is close to 2000secs


## Summary of Findings

**After examining the distribution of the individual variables in this dataset, I discovered that most trips were: between 500 -600secs; taken by 25-40 year olds; by subscribers; also by males; during daytime; and more on weekdays than weekends.**

>A deeper dive into the stations with the highest number of trips revealed thus:

**Gender: Men made the highest number of trips, women clocked more trip durations across almost all ages.** 

>Perhaps there are more men than women living in the region with the top stations of San Francisco Bay area, hence the high occurrence

**Age: The concentration of trips in 25-40 age group for all genders and user types could suggest it is used as commute to workplaces in the region while the older group may just use cycling as a form of exercise**

>The ages of women reduce greatly after 60years. Not only are there fewer women, there aren't many older ones

**User Type: Length of trip duration for for Subscriber category: Male > Female > Other, is a reverse of Customer category: Other > Female > Male**

>You can find the html link to data exploratory analysis here: https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/Ford%20GoBike%20System%20Data%20(I).html


## Key Insights for Presentation
>I will focus on the top contributors to trip duration which is the main source of revenue for the bike share system. I will start by introducing the dependent variable: trip duration for the final data subset in a histogram plot. 

>Afterwards, I will introduce the distribution of trip duration with age, and how the categorical variables (gender and user category) interact with it.

>Note: The last three sub slides showed difficulty in displaying my visualizations, so they were inserted as images instead. The codes still very much represent the plot

>You can find the html link to data exploratory analysis here:https://c424b21b95de446b824f9d87634b4986.udacity-student-workspaces.com/view/Ford_GoBike_System_Data_slide_deck.slides.html