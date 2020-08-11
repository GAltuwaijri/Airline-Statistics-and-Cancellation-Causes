# Airline-On-Time-Statistics-and-Delay-Causes

This is project is part of Udacity [Data Analyst Nanodegree](https://eu.udacity.com/course/data-analyst-nanodegree--nd002)

## Setup
In order to run the notebook, you'll need to install:
- Python 3.6
- Jupyter (notebook or lab)
- Pandas
- Numpy
- Matplotlib

This notebook will not be maintained.



## Investigation Overview

Exploring US flights of 2008 and answering on:-

    Is there is Any relation between Flight Distance and Cancelled Flights?

    Which cancellation reason is most common?

    Is there is Any relation between Flight Distance and Cancelled Flights?

    What is the trend of each Carrier from day to day? Which day has the most flight cancellations? Is there a lot of variation in any of these?



## Dataset Overview

The data consists of flight arrival and departure details for all commercial flights within the USA, from October 1987 to April 2008. This is a large dataset: there are nearly 120 million records in total, and takes up 1.6 gigabytes of space compressed and 12 gigabytes when uncompressed. To make sure not overwhelmed by the size of the data.

The data is separated by year. We decided to explore only the flights on 2008 because it was the nearest year that contained a full data files.

I'll probably be using many of the variables in the data set like Month, DayofMonth, DayOfWeek, UniqueCarrier, Distance, Cancelled, CancellationCode. Others like delay related features, fligth number and taxi times don't seem like they'll be very useful for me.


## Data

The Carriers.csv and the 2008.csv data comes originally from RITA -> http://stat-computing.org/dataexpo/2009/the-data.html
