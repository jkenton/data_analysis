Business Task and Stakeholders.md

Ask:
The task is to 
1. analyze the data to find relevant ways that casual users differ from members
2. formulate a strategy to attract casual users to consider joining as members

METHOD

The data I analyzed to visualize these relevant differences came from the Cyclistic Bike Share repository. I downloaded all data from September 2021 to August 2022 inclusive. This consisted of 12 zip files, each containing one month's worth of ridership data.

I extracted the zip files to a local computer, and made archive copies of the original CSV files in case I needed to start over with some aspect of the analysis. 

I then loaded the files into Microsoft Excel and familiarized myself with the data. To assist data analysis, I created two new columns. One was created to provide information about ride duration, the other was created to identify the day of the week for each of the rides. 

After seeing that the data problem was limited to ridership, as opposed to location-to-location trends, I elected to remove columns that had location-related data to simplify the analysis materials. The concerns section has more detail about this decision.

I assured that each of the thus-reduced data files had all pertinent data for the ridership questions. There were no missing values across the twelve data files. There was information about 5,883,043 ride segments. 

I completed a pivot table analysis of the data, using casual-member as the row information, day-of-the-week as column information, and values came from the count of rides, and the average duration of rides.

From this information, a summary table was created, showing monthly break-downs of daily average ride length and number of rides for both members and casual riders.

The summary table was used to create some visualizations that helped to identify important differences between members and casual users. What follows is an annotated graphic summary of the data files, with interpretation that may become useful for marketing purposes.

RESULTS

One fairly clear difference between casual and member riders was seen in the difference of average ride duration. Whereas the members were fairly consistent in their average usage as a group (12 mins and 29 seconds, plus or minus two minutes), casual riders made longer rides on average (28 mins and 40 seconds, plus or minus four minutes)

month-month differences

Weekday differences

Weekend Differences


CONCERNS
I noted that many of the data records were missing information related to starting GPS location, ending GPS location, and also many were missing data related to the station where the bikes were originally rented, and where they were returned. Since the question was only concerned with differences in patterns of use volume, rather than more qualititative concerns (like which depot would benefit from having more bikes available on given days), I made copies of the data files, and omitted the columns related to starting and ending locations and stations from the data files that generated the visualizations above.

If a future analysis is undertaken regarding the begin- and end-points of the ride segments, a method must be created to deal with this substantial volume of missing data.

