# Surfs_up
Surf's Up with Advanced Data Storage and Retrieval 

## CHALLENGE OVERVIEW
---
 The purpose of this analysis is to review a dataset pertaining to weather conditions that has been stored in a SQLite database to provide information that will convince an investor that opening up a Surf n' Shake shop in Oahu, Hawaii is a good business idea. The idea is that the shop will sell surf boards and ice cream throughout the year, but the investor is hesitant because he invested in a similar business that failed due to the weather conditions. In order to get this investor on board, we need to provide statistical analysis specifically on the weather conditions in Oahu that will convince him that this will be a successful business venture

## FEATURES AND DATA SOURCES
-  Tools: Python SQL toolkit (SQLAlchemy), Object Relational Mapper, pandas, numpy
-  Software: SQLlite, Python 3.9.2, Flask, Jupyter Notebook

## Results

- Summary Statistics DataFrame: June Temperatures

![june temps](https://user-images.githubusercontent.com/96033163/156903221-5fccef44-d204-4334-b4e2-6fbab6522ae0.png)

- Summary Statistics DataFrame: June Temperatures

![dec temps](https://user-images.githubusercontent.com/96033163/156903220-59d13272-31d5-4bfb-ab1b-ed883e8b2f8c.png)


1) The average recorded temperature in June is 74.9 F, 4 degrees higher than the average temp in December.
2) June had a low temperature of 64°F and a high temperature of 85°F whereas December had a low temperature of 56°F and a high temperature of 83°F.
3) In addition, both June and December had roughly similar standard deviations. June's standard deviation of 3.25 and December's standard deviation of 3.75 tells me that their temperature records are concentrated around both of their average temperatures.
4) Lastly, June and December had a 75th percentile of 77°F and 74°F, respectively, which indicates that these two seasons had relatively warm temperatures.
   
## Summary 
Oevrall the weather in December and June are historically very similar
I would recommend further analysis on:

- Determine whether precipitation plays a factor in june and december despite the warm temperatures that are experienced during this time.
-  determine if location's elevation attracts or deters business more than another location.
