# Surfs_up
## Purpose:
W avy wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. To do this task we have used Python, Pandas functions and methods, and SQLAlchemy. First, we filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. Then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.
## Resulta:


### June Temperature
<img width="473" alt="June_temps" src="https://user-images.githubusercontent.com/107155888/184403685-524a3b7d-b4e3-48e4-bca5-511fbe05101f.png">



### December Temperature
<img width="514" alt="dec_temps" src="https://user-images.githubusercontent.com/107155888/184403649-0b220377-3f7a-41c8-a9d1-394b40403780.png">

By comparing both June and December temperatures. The mean is only 4% higher in June. Maximum temperature is 

 June Temperature visualization

<img width="415" alt="june_dec_hitogram" src="https://user-images.githubusercontent.com/107155888/184407671-526b5c63-f8ed-4140-8742-2f0bb1ebc2ef.png">

December Temperature visualization



## Summary:
Two additional queries
### June Temperature with station and precipitation.


<img width="625" alt="june_st_pr_tm" src="https://user-images.githubusercontent.com/107155888/184414625-8eca94ca-3377-46f3-b9b6-60cd68d9d3f3.png">


### December Temperature with station and precipitation.

<img width="617" alt="dec_st_pr_tm" src="https://user-images.githubusercontent.com/107155888/184414649-d02e0b6a-40de-4747-a3d5-b03d47191488.png">
