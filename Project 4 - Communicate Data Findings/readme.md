# Airline on time data
## by Gustavo Bertoli


## Dataset

> This dataset comprises a collection from 1987 to 2008 of scheduled flights performance (on-time, delays, cancellations) from many airports in the USA.

> The data consists of flight arrival and departure details for all commercial flights within the USA, from October 1987 to April 2008. This is a large dataset: there are nearly 120 million records in total, and takes up 1.6 gigabytes of space compressed and 12 gigabytes when uncompressed  **(in this work only the data from 2006 to 2008 is analyzed due to computer resources constraint)**. 

> Some open questions based on this dataset:
> - When is the best time of day/day of week/time of year to fly to minimise delays?
> - Do older planes suffer more delays?
> - How does the number of people flying between different locations change over time?
> - How well does weather predict plane delays?
> - Can you detect cascading failures as delays in one airport create delays in others? Are there critical links in the system?
> - Are there certain destination or arrival cities that are home to more delays or cancellations?
> - What are the preferred times for flights to occur? Are there any changes over multiple years?

> References: 
> 1. https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7
> 2. http://stat-computing.org/dataexpo/2009/
> 3. [Dataset Features Description](https://www.transtats.bts.gov/Fields.asp?Table_ID=236)


## Summary of Findings

> - The flight departure and arrival delays are high correlated, which illustrates the cascade effect, also confirmed by the `Late Aircraft Delay` correlation
> - The most impactful delays are in order of impact: Carrier, National Air System, Weather, and Security
> - There are no direct relations from Day of Week and Month with the occurrence of delays 


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.