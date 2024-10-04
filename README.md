# Emergency Response Times in New York City Increased Again in 2023
## Lede Program Project Assignment 3 

I analyzed New York City emergency services data to calculate average emergency service response times per year and per borough. I found that response times grew every year between 2020 to 2023, the most recent year of available data, as have the overall number of calls made.

I used EMS Incident Dispatch Data for this analysis, which is available here: https://data.cityofnewyork.us/Public-Safety/EMS-Incident-Dispatch-Data/76xm-jjuj/about_data

To carry out the analysis, I downloaded the four most recent years of available data, going back to 2020, as separate csv files. I then analyzed each file separately as pandas dataframes in Python. I calculated the response time for a given emergency call in minutes by substracting the time of the incident from the time first responders arrived on scene, which is recorded for every call. I also analysed whether emergency calls became more numerous in a certain season of the year, because I wanted to investigate whether extreme weather was increasing the number of incidents. It is true that there appeared to be about 20,000 more emergency calls placed in the Summer of 2023 than in the Fall of 2023, but without more context, it was difficult to say whether this finding was significant, so I did not include this in my final analysis. In addition, I used Python to calculate the mean and median of response times in each borough and in each year, because the two types of information complemented eachother well. (Medians were lower; means were higher. The discrepancy may have something to do with the priority first responders give to the most serious emergencies.

## Skills learned: 
I learned how to use DataWrapper for charts by doing this project. I also learned more about using python to analyze data, and tested the limits of Python's capacity to handle extremely large datasets.

## Things I would've liked to do:
If I had had the time, I would have liked to distinguish in my analysis between calls related to serious emergencies and other EMS calls, perhaps according to the severity code rating that every entry includes. This would help me understand better the quality of response times when they matter the most, as compared with events of lower priority, such as patient transports. This would have deepened my analysis, though taking the median and mean response time values helped get around this some.
