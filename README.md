# surfs_up

## Overview of Analysis

### Purpose

The purpose of this analysis was to examine trends in precipitation and temperatures over a series of time for a client, W. Avy. in order to determine whether opening a suft and ice cream shop business in Hawaii is a good business idea. The project began by having us examine the SQLite data titled, "hawaii.sqlite", in order to plot precipitation levels across the time covered. Additionally we plotted the frequency of temperatures in this dataset in the form of a histogram. Finally, we looked specifially at the temperatures for the months of June and December and derived summary statistics for these months across all the years covered by this dataset.

## Results

The results from our analysis of the temperatures in the months of June and December revealed three major points:

1. There were 1700 total temperature observations for the month of June and 1517 total temperature observations for the month of December, implying that the dataset is very reliable and that trends can be heavily relied on.

2. The measures of central tendency (mean and median in our case) for both June and December were very close to one another implying that the data was not largely skewed and that temperatures for both months are relatively stable. June has an average temperature of 74.9 degrees Farenheit and a median temperature of 75 degrees Farenheit. and December has an average temperature of 71.04 degrees Farenheit and a median temperature of 71 degrees Farenheit. Since these temperatures are optimal for surfing and eating ice cream we can infer that the business should be able to perform well.

3. June and December have very tight spreads respectively based on the standard deviation in the summary statistics for each month. June has a standard deviation of 3.26 degrees and December has a standard deviation of 3.71 degrees. More significantly, these spreads in temperature overlap with one another despite the usually drastic difference in seasons (Summer and Winter) meaning that the business should perform equally well at both times of the year.

Below are screenshots of the descriptive statistics for each month:

![June Stats](https://github.com/josem279/surfs_up/blob/master/June_stats.PNG)

![December Stats](https://github.com/josem279/surfs_up/blob/master/December_stats.PNG)

## Summary

Our analysis, though simple, is able to convey a lot of information. After filtering data for the months of June and December, we can see that the dataset was very robust and thus very reliable for finding trends. The analysis also showed that the temperatures for the two months hardly vary and are relatively similar suggesting that the business would not only be profitable but that it would be profitable year round.

Aside from our analysis, two other queries that I would perform to gather more weather data for June and December are visually depicting the information in histograms so that it is more easily and :

![Histograms]()