# Dog Bite Analysis

*This repo was initially generated from a bookdown template available here: https://github.com/jtr13/EDAVtemplate.*	

URL for the output: https://rul124.github.io/DogBiteAnalysis/

This project is for Stats 5702 EDAV Fall 2021:\
Ziyu Fang (zf2253); Xiaorui Qin (xq2209); Ruoxi Liu (rl3155)
## Data Lists:
Dog Bite Data: (Main Dataset)\
 https://data.cityofnewyork.us/Health/DOHMH-Dog-Bite-Data/rsgh-akpg \
NYC Dog Licensing Data: (Auxiliary Dataset)\
https://data.cityofnewyork.us/Health/NYC-Dog-Licensing-Dataset/nu7n-tubp \
NYC Weather Data: (Auxiliary Dataset) (to be decided) \
https://www.weather.gov/wrh/climate?wfo=okx




## Data Set Description:
Our main data is about dog bite incidents that happened in NYC from 2015 to 2017 reported to the Department of Health and Mental Hygiene (DOHMH). There are about 10.3k records in total. Each record represents a single dog bite incident and information on breed, age, gender. Spayed and neutered status are also provided. With those features given, we can explore the relationships between bite incidents and dogs’ related features. We can also make some predictions about whether some specific dogs are more likely to bite citizens in some neighborhoods and seasons. The second dataset is an auxiliary one which provides information about licensing in different areas in NYC. We want to use this data to explore more about licensing with areas in order to make a better assumption about relationship dog bitten incidents with environments.

## Questions:
Here are some interesting questions that we want to answer when having this data set: (And we also provide some explanations about why we want to pay attention to them)

1. What’s the relationship between dog bites and dog’s breed, age, gender and whether it’s neuter or not? We also want to see if a specific season makes dogs more aggressive? Are there some neighborhoods where dogs get stimulated easily such that more fights and bite incidents are provoked?
If there indeed exists a relationship between dog bites and some specific features. Our results can remind the dog’s owners to pay closer attention to their dogs while walking them in conditions that are proven to be more likely to make their dogs aggressive. What we want to do is that, with dog lovers’ more care, it can help reduce the unwanted incidents and also make puppies as lovely creatures in people’s minds.

2. In the existing dog bites dataset, we can see the breed with the highest proportion of biting people. In order to see if the reason behind it is about its higher population among all dogs or simply about this breed’s natural potential of being aggressive, we could use the auxiliary dataset (NYC Dog Licensing Dataset), which is much larger than the dog bites dataset, to roughly estimate the population composition of different breeds and analyze the above question. 
With this exploration, we can have a clearer picture of the relationship between breeds and its potential aggressiveness. We do not want to make a rash decision of naming some breeds “aggressive ones” without comparing the proportion. In order to give a more scientific answer, this step is unignorable. 

3. We want to have a classifier that, given the breed, age, gender, neuter situation, borough, and Zipcode of a certain dog, could we predict the probability of a dog attacking people? 
We will divide our data into the training set and the testing set. A classifier will be trained and tested for dog bites, which could assist the Health Department to roughly get an idea of what kind of dogs are more dangerous. 
With these probability given, the officers in the Health Department can strengthen targeted management. And feeders can also pay more attention in educating dogs with those features that can cause a high potential danger.
The classifier will also help citizens to make a detour when they discover dogs that are likely to bite people to prevent more incidents.
