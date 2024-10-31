# Capstone - Cancer Analysis Project

By Ishan Sharma

### My goal

In this project, I seek to analyze cancer data across the United States and compare them against various indices that could plausibly be causing higher rates. Through, this, I wish to be able to construct a model which can predict cancer based on such indices.

The impact of such a solution would be a list of potential causes of cancer which could be further analyzed, and if indeed proven they could be dealt with. This would improve the health of the United States

### My data

My data consists of a very granular analysis of cancer data by county, over several years. Being too dense to attach to a github repo, I shall instead link to the dataset [here](https://1drv.ms/f/s!AneQxAmQInlBks8f2UygKzbvNH3F6w?e=Leb351), downloaded [here](https://ghdx.healthdata.org/record/ihme-data/united-states-cancer-mortality-rates-county-1980-2014). 

The first, and perhaps simplest, part of the dataset, is under "Annual". This is data of cases the US and various states by year. It is raw data, where there are columns for location, cause, sex, and bounds, and this data is collated under several states. 

The second part of the dataset is under "linking_ids". This is less data and more of an index to keep all of the IDs straight. 

The third part of this dataset is under "national". This consists of multiple sheets, all of differing rates of cancer by county over the years from 1980 to 2014. 

The fourth part of this dataset, "percent_difference", consists of an index of IDs, as well as a list of percent changes in cases over time, in common with "Annual". 

The fifth part of this dataset, "state_by_state" consists of excel spreadsheets, each of showing several states broken down by county. In separate sheets are data for various types of cancer by time interval, and together all these spreadsheets contain data for cancer broken down in each county of the United States by time interval. 

The sixth part of this dataset, "top_and_bottom", contains cancers and their mortality rates by US county, with top and bottom 10 ranked causes. This is data that may be unnecessary, as I can process this (and more than just top and bottom) myself. This contains columns for processing standard, county, ranking of cause, the cause itself, and mortality rates.
