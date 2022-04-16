#  Surf's Up with Advanced Data Storage and Retrieval

## Overview of the Analysis
This project looks at temperature trends for Oahu in June and December. The analysis is intended to help a client determine if an ice cream surf shop is a sustainable business year-round. The project used several tools, dependencies, and analysis to determine whether the ice cream surf shop would be profitable for investors. For this project, we used Python, Pandas, Jupyter Notebook, Flask, SQLite, SQLAlchemy, Visual Studio, Matplotlib, to name a few of the resources we used. 


## Results

Three key differences in the weather for June and December:

-We can see that the minimum temperature for December was 56 degrees and the minimum temperature for June was 64 degrees. December's lowest temperature might be too cold for ice cream.

-The maximum temperature in December was 83 for all years data was available. For June, we can see the maximum temperature was 85 degrees. 

-The average daily temperature for June is 4 degrees warmer than the average daily temperature for December. 

!['June Temperature Statistics'](https://github.com/lllohr/surfs_up/blob/7e62b295c1fcc0679135d80b63dc34e138b3a840/resources/june_tobs_statistics.png)
!['December Temperature Statistics'](https://github.com/lllohr/surfs_up/blob/7e62b295c1fcc0679135d80b63dc34e138b3a840/resources/december_tobs_statistics.png)

### Challenges and Difficulties Encountered

Some of the challenges I encountered was creating the correct query for the month of June and December. Initially, I was stumped on how to create these queries. I ended up utilizing the AskBCS Learning Assistant to help me with my queries. I had to reach out twice before figuring out the task.

Secondly, I did not change the query from precipitation to temperature initially. This was a reminder to know what my task is before I dive headlong into my project. Overall, this project was a great tool to learn how to properly format datetime queries. 


## Summary

The analysis we performed showed us the temperatures for June and December. We were able to see that the average daily temperature for June was 74.94 and for December it was 71.04. This analysis was run for all years for the months of June and December. There were 1700 data points that our analysis looked at. 


### What are some limitations of this dataset?

For the investors, it will be important to determine whether or not the ice cream business would be sustainable on the days that it is 56 degrees. We would want to see how many days of the year the weather is warm enough for ice cream. Minimum and maximum temperatures don't tell the whole story.

The initial task for the module was to look at the precipitation for the previous year. Do we want to perform a query that looks at the precipitation datas for all available years in the month of June and December? 

I would continue with this temperature analysis and include some fancy Matplotlib graphs, as we did with the precipitation analysis. I would also compare the highs and lows for each month and plot them for review for the investors. Do we want to perform a query to determine what the other available weather data is available for June and December? Is it humid? Is it windy? What is the air quality like? 

The initial task for the module was to look at the precipitation for the previous year. Do we want to perform a query that looks at the precipitation datas for all available years in the month of June and December? 
