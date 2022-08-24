# surfs_up

## Project Overview
Using SQLite database and sqlalchemy, complete the following tasks:

1. Filter the Measurement table on June temperatures and provide the summary statistics.
2. Filter the Measurement table on December temperatures and provide the summary statistics.
3. Summarize the analysis.

## Results
After completing the analysis we can see that:

- There are fewer temperature observations for December even though there are more days in December than in June.  
- The mean and median for June are almost identical.  December's mean and median are almost identical too.
- The average and max temperatures for June are within 4 degrees of the December temps, however, the min temperature for June is 8 degrees higher than December.

June Summary Statistics                                                      | December Summary Statistics 
:----------------------------------------------------------------:  | :-------------:  
![June Stats](/Resources/june_stats.png)  |  ![December Stats](/Resources/dec_stats.png)




## Challenge Summary
Based on the analysis there does not appear to be much temperature fluctuation between the months of June and December.  

To expand on this analysis I suggest completing the same queries on the precipitation data for June and December.  I also suggest doing these same queries by station to see if there are temperature and precipitation fluctuations between the two months based on location.
