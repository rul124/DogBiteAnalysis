# Dog Bite Analysis

*This repo was initially generated from a bookdown template available here: https://github.com/jtr13/EDAVtemplate.*	

URL for the output: https://rul124.github.io/DogBiteAnalysis/

This project is for Stats 5702 EDAV Fall 2021:\
Ziyu Fang (zf2253); Xiaorui Qin (xq2209); Ruoxi Liu (rl3155)
## Data Lists:
Dog Bite Data: (Main Dataset)\
 https://data.cityofnewyork.us/Health/DOHMH-Dog-Bite-Data/rsgh-akpg
 
NYC Dog Licensing Data: (Auxiliary Dataset)\
https://data.cityofnewyork.us/Health/NYC-Dog-Licensing-Dataset/nu7n-tubp

NYC Weather Data: (Auxiliary Dataset) (to be decided) \
https://www.weather.gov/wrh/climate?wfo=okx


## Data Set Description:
Our main data is about dog bite incidents that happened in NYC from 2015 to 2017 reported to the Department of Health and Mental Hygiene (DOHMH). There are about 10.3k records in total. Each record represents a single dog bite incident and information on breed, age, gender. Spayed and neutered status are also provided. With those features given, we can explore the relationships between bite incidents and dogs’ related features. We can also make some predictions about whether some specific dogs are more likely to bite citizens in some neighborhoods and seasons. The second dataset is an auxiliary one which provides information about licensing in different areas in NYC. We want to use this data to explore more about licensing with areas in order to make a better assumption about relationship dog bitten incidents with environments.

## Questions:
Here are some interesting questions that we want to answer when having this data set: (And we also provide some explanations about why we want to pay attention to them)

1. Which breed has the largest number of dog bites? Is this because of its higher population among all dogs or because of this breed’s natural potential of being aggressive? 

2. Which borough has the largest number of dog bites? Is this because of the higher population of dogs in this borough or because of the inadequate management and policies? Are dog bites affected by time? Is there periodicity? Is this related to temperature? 

3. Are dog bites affected by gender and spayed/neutered status? Which gender has the larger number of dog bites? Is this because of the higher population of dogs with this gender or because of their aggression? Which is more likely to bite people, younger dogs or older dog? Is this related to breeds?
