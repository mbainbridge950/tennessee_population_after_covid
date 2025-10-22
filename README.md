# Tennessee Population After Covid



## Table of Contents



* PowerBI Dashboard
* Questions
* Normalizing the Data
* Problems and Hurdles
* Technologies Used
* Data Sources
* Conclusion



## PowerBI Dashboard

Link: [https://app.powerbi.com/groups/me/reports/21131c88-d84a-40fd-a121-12196412c4ae/0212973c35766e73cccb?experience=power-bi](https://app.powerbi.com/groups/me/reports/21131c88-d84a-40fd-a121-12196412c4ae/0212973c35766e73cccb?experience=power-bi)



## Motivation:

During the Covid-19 pandemic, Tennessee experienced a large growth in population as well as a sharp increase in housing prices.  At my company, we experienced a large growth of new customers who had moved to rural areas, many times to buy their first home.  I was fascinated by this new trend of customers that wanted their own garden, chickens, and to live a different lifestyle than their previous urban life.  I heard of and saw many who moved due to the opportunity to work remotely.  Now, 5 years since the pandemic, I wondered if the trend still continues, if people are moving back to the urban areas, and if people are still choosing to move out of the major cities.

 

## Questions:

1. What are the top 10 states of population growth since 2020?
2. What is the population change for Tennessee's largest cities?
3. Where are we seeing the most growth across the state?
4. Do home prices affect the decision to move?
5. Do these trends hold as more and more employers are pushing for employees to return to the office?
6. Are employees embracing a longer commute or moving back to the cities?



## Normalizing the Data

The datasets I selected contain population changes both nationally and within Tennessee.  Tennessee population changes are since 2020.  I also have a data set for median home prices in Tennessee since 2012.  I had to clean the data in Python in order to do my analysis as well as get the data sets to be readable by PowerBI so I could create graphs.



## Problems and Hurdles

My data sets differed between City and County, so I had to join them with a data set that had both city and county to get similar values. I also found once I got all of my data into PowerBI, it would not graph, so I had to change values from rows and make them columns in order to successfully show change per city/county per year.



## Technologies Used

1. Python / Pandas - for exploration, normalizing and aggregation of the dataset
2. PowerBI - for creating interactive dashboard
3. Git - for version control



## Data Sources

To answer the above questions I used the following sources to collect datasets for my analysis

1. Tennessee Housing Development Agency - Tennessee Home Sales Data
   https://thda.org/research-and-reports/tennessee-home-sales-data/
2. Tennessee State Data Center
   https://tnsdc.utk.edu/
   https://libguides.utk.edu/tngis/county
3. TN Department of Health
   https://www.tn.gov/health/cedep/ncov/data.html



## Conclusion

The data analysis shows Tennessee is one of the top states in the country for population growth since 2020, and the trend has not changed.  Initially, Nashville experienced a large drop in population between 2020 and 2021, but has steadily gained back a large amount most likely due to the job opportunities in the highly tech oriented city.  Memphis has lost the most population steadily year over year, most likely due to the large increase in crime.  The areas of the most growth are the surrounding counties outside of these areas, which suggests people are choosing larger, rural homes and longer commutes over shorter commutes, smaller spaces, and higher property value.  In the case of Memphis, people are choosing higher priced homes outside of the city as opposed to the lower priced homes within Memphis itself.  Chattanooga and Knoxville experienced steady growth in population more like a traditional suburb as opposed to a major city.  Covid death rates were not predominantly responsible for the population decrease in Nashville.  Memphis had the highest number of Covid deaths across the state, but this was only a fraction of the amount of population lost due to people leaving the city.  All in all, Covid played a role mostly in getting people to think differently about where they live.  Suburban and rural areas are hot, whereas urban living is not seeing as much growth.

