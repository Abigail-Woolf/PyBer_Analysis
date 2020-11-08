# PyBer_Analysis
To help improve access to ride-sharing services and determine affordability for underserved neighborhoods I took a deep dive into the ride_data.csv and the accompanying city_data.csv. Firstly, I wanted to create a summary dataframe to get familiary with obvious trend in the data. This is the Summary Dataframe:

![](https://github.com/Abigail-Woolf/PyBer_Analysis/blob/master/Analysis_Imgs/Summary_DataFrame.png)

Matplotlib is a graphing and plotting library for Python that comes with the Anaconda installation. To use it with Jupyter Notebook, all we need to do is import it. Matplotlib is often used with another Python library, NumPy, a numerical mathematics library for making arrays or matrices.
The PyBer analysis was completed in order to deliver a clear and concise representation of the ride-sharing app data to the company CEO. The data was analyzed by organizing the fares per ride and fares per driver by the three different city types. This allowed us to recognize different patterns of success in the ride-sharing app between different geographical areas. 
short summary of results

## Challenges
Luckily, the raw data used in this assignment was very clean, allowing me to go ahead with the analysis and skip the cleaning process. A method I used to further organize the raw data was to merge the two separate dataframes into one dataframe: ride_data_df and city_data_df. This created my master dataframe, pyber_data_df, which I used to create my visual representations. The line graph below shows that the trends between the three city types mirror each other, and tend to be dependent on the time of year. This makes sense because as the weather gets better (in May, for example), people will walk more. This graph also shows that there are more variables to be considered throughout this analysis other than city type.
![](https://github.com/Abigail-Woolf/PyBer_Analysis/blob/master/Analysis_Imgs/Challenge_fare_summary%20copy.png)



### Further Research
After completing my summary dataframe, I observed that the urban city type has a much higher amount of total fares, which translates to higher fares per ride and per driver in urban areas. Rural cities had the lowest fares, likely due to lower population density. I would suggest further analysis to determine whether offering the app in rural areas is financially sustainable for the company, especially if it is rarely used. To perform this analysis, I would request more data from the company pertaining to operational costs. I would compare the money spent for operating the application in the varying city types. 
