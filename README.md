# PyBer Analysis - Ride-Sharing Data by City Type 
## Purpose 
Analysing PyBer ride-sharing data in rural, sub-urban, and urban areas to provide valuable insights on the company's relative performance in these different city types. 
## Results 
### Summary Data 
There were some predictable results when analyzing data for total rides, drivers, fares, and their averages across different city types. The results are as follows (reference the summary dataframe pictured in the image below):

*From PyBer_Challenge.ipynb in Resources Folder*
<img width="635" alt="rideshare_summary" src="https://user-images.githubusercontent.com/79600550/113447157-4c21f180-93c7-11eb-99ae-5d1bf2b334ad.png">

- Total Rides 
  - total rides were greatest in urban cities (1,625), second largest in suburban (625), and smallest in rural areas (125). 
  - urban cities had a substantially larger number of rides vs other city categorizations:
    - over double that of suburban cities
    - thirteen times more than that of rural cities. 
  - suburban cities saw five times the number of rides vs. rural areas  

- Total Drivers 
  -  Similar relationship as drivers: largest in urban areas (2,405), second largest in suburban (490), and smallest in rural cities (78). 
  -  An even greater disparity in these quantities vs total rides:
      -  Urban cities had almost five times the number of drivers vs suburban cities 
      - Urban cities had thirty times more drivers than rural city areas.   
      - Suburban cities had six times the number of drivers vs. rural city areas. 

- Total Fares: 
  - Largest number of total fares coming from urban city areas ($39, 854), second largest from suburban ($19,356), and smallest total fare amount from rural areas ($4,328). 
  - Total fares were almost exactly double in Urban areas vs. Suburban areas 
  - Total fares were approxiamtely nine times greater in urban areas vs. rural areas 
  - Total fares were four times greater in suburban cities vs rural city areas.
  
- Average Fare/Ride 
  - The average fare per ride represented an inverse relationship in comparison with the above sets of results: 
    - highest average fare/ride seen in rural cities ($34.62)
    - Second highest in suburban areas ($30.97)
    - Lowest average fare in urban city types ($24.53)
  - Disparity amongst these values were tighter, ranging anywhere around 10-50% greater in respective city types. 

- Average Fare/Driver
  - Similar relationship as average fare/ride: greatest average far in rural areas ($55.49), second greatest in suburban areas ($39.50), and lowest average fare per driver in urban cities ($16.57)
  - Disparity amongst these values were more accentuated with rural cities having more than 3 times greater average fare/driver vs. urban areas.
  - suburban average fare/driver was two times larger than that of urban cities. 

### Weekly Fare($) Data (January - April 2019)
Similar deductions can be made when analyzing weekly fare data occuring between the months of January-April 2019. Some new inferences are also available with this analysis (see image below):

- total fares for urban city types were substantially larger across all months, followed by suburban, and lastly, lowest in rural city areas. 
- total fares across all city types followed generally a similar pattern through the months of January - April. 
  -   a slight spike in total fares toward the end of February/beginning of March. 
  -   a very gradual increase through January to April- although this trend is apparently quite minor. 

<img width="857" alt="Screen Shot 2021-04-04 at 10 35 07 AM" src="https://user-images.githubusercontent.com/79600550/113512213-8c04e800-9531-11eb-8d0c-4751342df661.png">

*See also in Analysis folder - Pyber_fare_summary.png*

## Summary
Given the results above, there are a number of disparities that become salient when considering opportunities for business:

First, is considering the large disparity that exists between the total number of rides and total fares in urban city types vs. those in rural city types. Although urban city types see a total number of rides thirteen times greater vs. rural cities, their total fares value is only roughly nine times greater than that of rural types. Here, there is an opportunity to extend profit margins, especially when considering urban city type's standing in average fare/ride - one could consider charging a premium price for rides in urban areas, driving the average price up to a number closer to the average fare value of suburban and rural areas. Although these values could be represented by some specifying factors (i.e that people may be more likley to take physically longer rides in rural areas/shorter rides in urban areas), charging a slight premium in rides in urban areas could be beneficial to the business considering the high number of rides (i.e that a small change in price could provide a meaningful benefit to profit margins) while also being small enough to not be viewed as unreasonable by customers paying for ride-share services.

A second area in the data to consider is the comparative difference in total rides and drivers in rural areas  vs. the comparative difference in total fare in rural areas - that is, the relative number of total rides and drivers in rural areas is significantly lower than total fares in rural areas. Here, another opportunity to extend profits may exist: money is being spent in these areas, however, the frequency of rides is low and the number of drivers is even lower in comparison. Although susceptible to other factors, given the data, a variable behind a low number of rides in this area could be due to lack of presence and accessibility - turning focus to building a larger driver base in rural areas could very well lead to greater accessibility and greater frequency of rides. Given the above results - i.e that rural areas see a relatively high average fare/ride and good total fare value given the extreme lack of drivers and total rides - this change could make a meaningful impact on profits in rural areas. This, of course, involves some speculation, however is an area worth investigating nevertheless.

Finally, given the very similar trends seen across all city types through the first four months of the year, one could be confident in making the above changes to generalize over the entirety of the year rather than looking for seasonal changes in services across different city types.
