# Bikesharing Analysis

## Overview
The purpose of this analysis is support the business case from brining bike sharing to Des Moines, IA. To accomplish this an analysis was run on the New York City Citi Bike program since it is a well estabilshed bike sharing program. The analysis below provides informaiton such as peak hours, gender breakdown, trip durration and starting location. This information can be used to help determine if starting a bikesharing program in Des Moines is viable. 

### Resources
**Input**: 201908-citibike-tripdata.csv <br/>
**Software**: Python, Tableau <br/>
**Output**: GitHub ReadMe, Tableau Bikesharing Story <br/>

## Results
The screen shots below describe the results of the bikesharing analysis. For the original Tableau visualizations click on the following link: 
[Tableau Bikesharing Story](https://public.tableau.com/profile/mike.horstman#!/vizhome/Bikesharing_Challenge_16155041760540/BikesharingStory)

### Result #1
![August Peak Hours](https://github.com/mhorstman/Bikesharing/blob/main/Tableau_Screenshots/August_User_Peak_Hours.png)
Peak hours for NYC Citibike are 8am and 4pm-8pm as shown in the chart above. This aligns closely to commute times and it is reasonable to assume that the peak times in Des Moines would be similar. 

### Result #2
![Trips by Weekday](https://github.com/mhorstman/Bikesharing/blob/main/Tableau_Screenshots/Trips_by_Weekday.png)
Adding weekday to the analysis, the chart above confirms that peak days are Monday through Friday during commuting times. The chart is also broken out by 'subscribers' and 'customers' (i.e. one-time or non reoccuring users). 

### Result #3
![Trips by Gender](https://github.com/mhorstman/Bikesharing/blob/main/Tableau_Screenshots/Trips_by_Gender.png)
Looking at the gender breakdown, Females and Males follow the same commute pattern. The rides with "Unknown" gender are likely toursits (since less information is collected for non-subscribers) which are spread more evenly throughout the week. Since Des Moines has less concentration of tourists, the Des Moines data will likely look closer to the Female/Male charts. 

### Result #4
![Checkout Times](https://github.com/mhorstman/Bikesharing/blob/main/Tableau_Screenshots/Checout_Times.png)
Nearly all trips are less than an hour with most trips lasting 4-7 minutes. This means that bikes will turn over quickly and therefore the pricing structure should be set accordingly. 

### Result #5
![Checkout Times by Gender](https://github.com/mhorstman/Bikesharing/blob/main/Tableau_Screenshots/Checkout_Times_by_Gender.png)
Females and Males have similar trip durations. The rides with "unknown" gender again are likely tourists with tips lasting 4-30 minutes.

### Result #6
![User Trips by Gender](https://github.com/mhorstman/Bikesharing/blob/main/Tableau_Screenshots/User_Trips_by_Gender.png)
Nearly all Subscribers are categorized as Female or Male; These users are likely local and not tourists. 

### Result #7
![Top Starting Locations](https://github.com/mhorstman/Bikesharing/blob/main/Tableau_Screenshots/Top_Starting_Locaitons.png)
Most trips start in Manhattan near business and tourist dense areas. In Des Moines it can be expected that typical starting locations will follow the same pattern near business districts and possible near university populations. 

## Summary
Although Des Moines is a very different city than New York City, many of the same trends with bikesharing will align. As discussed above, Des Moines may have a smaller percentage of tourists but the usage by locals should be similar to NYC (when adjusted for population). With the right pricing structure the program should be a sucess. 
In order to continue the analysis I am suggesting that the following additional analysis is performed:
1. The checkout times analysis should be re-run using only subscribers. Since these are less likely to be tourists and will be more of a source of steady income for the program, this may give a more realiztic picture of what the Des Moinse program can expect to see. 
2. Another useful datapoint would be percent utilization of the bikes in the system. The total number of bikes can be calculated using the bike ID and then the utilization charted to extimated how many bikes are sitting idle at any one time and therefore not making any money. 
