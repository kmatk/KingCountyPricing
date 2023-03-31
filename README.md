
![image](https://user-images.githubusercontent.com/124652720/229219682-c04fa6e3-939c-48d8-8230-a0187df4f7fb.png)





# Phase 2 Project

**Authors**: [Mahum Abid](mailto:mahumabid101@gmail.com), [Kevin Atkinson](mailto:kmatk620@gmail.com), [Luke Sims](mailto:lukeasims@gmail.com)

## Overview

Seattle and King County represent one of the most stable and lucrative parts of the American Real Estate Market. Our client, a major real estate investment firm in the area, contracted us to thoroughly examine the factors around housing and land prices to understand better when and what to buy and sell. We came to conclude an investment strategy following this critera: 

- Certain Areas, High Living Space/Lot Space, Views/Waterfront, and quality construction.
- Converting Basement Space to Living Space.
- Converting Garage-rooftops to rooftop-Patios. 
- Avoid neighborhoods with Private Sewer Systems and older buildings.
- School Districts play a major role in housing prices and are a unique selling point. 


## Business Problem

Since 2015 the Seattle housing market has undergone a rapid price increase, 4-5% annually, and now is experiencing an increasingly rapid contraction, with house prices falling 7% this February alone. In light of the recent shifts in the Real Estate Market, our client is re-evaluating their short and long-term investment strategies to mitigate the fallout. Our client wants to reasses their strategy and has contracted us to provide a data-informed, buying and selling strategy for short term and long term investments. The questions we set out to answer for our clients were: 

- What were the factors of a house's price?
- What were the influences that had been overlooked?
- Which properties should they unload from their portfolio? 
- What modifications could they make to existing properties to increase value? 

## Data

We used a variety of available data sources ranging from one provided by the client and publically available APIs. 

- King County House Sales: 
https://github.com/npagrawal/Kings-County-Real-Estate-Analysis/blob/main/data/kc_house_data.csv

- King County Public School::
https://gis-kingcounty.opendata.arcgis.com/datasets/kingcounty::school-districts-in-king-count[…]ea/explore?location=47.527326%2C-121.923521%2C11.00


## Methods

After examining collectively and cleaning individually our data sets, we used a combination of descriptive and analytical statistical methods to determine correlations among our variables. Next, we standardized and ran singular and multiple linear regressions to confirm and quantify our findings. Finally we used a combination of data and business acumen to substantiate relevant conclusions for our stakeholder. 

## Results

In total we analyzed 18 different categories with 131 variables and found the most determinant factors were: Location and access to Schools, Lot and Living space SQ Footage, Quality of Views, Waterfront access, and Grade of Construction Materials. Bewteen these categories and variables we came to RSquared of 83%, meaning we we're able to explain the 83% of the variance in pricing between one house and another with an alpha of 5% (False Positive).   

![PredictedVsActual (2)](https://user-images.githubusercontent.com/124652720/229214613-bf122a0f-0734-4e3b-9af3-984b9d551630.png)


![QQPlot (1)](https://user-images.githubusercontent.com/124652720/229214639-10cf6a74-b8e1-4228-b379-da89d6268838.png)


Breakdown of Factors: 

SQ Footage:
- For every 866 of Living Space SQ footage, we see an increase of 10.25%. 
- For every 7,256 of Lot Space SQ footage, we see an increase of 4.3%. 

On a range of 3 relating to types of Views properties, there is a significant value difference. 
- 1 None: influences the price by 0%. 
- 2/Good: influences prices as compared to the previous category by 14%. 
- 3/Excellent: influences prices as compared to the previous category by 31%. 

On a scale of 13 relating to Grades of Quality of Materials, there is a significant value difference.
- 1/Fair influences prices by 0%.
- 2/Average: influences prices as compared to the previous category by 6%. 
- 3/Good: influences prices as compared to average by 10%. 
- 4/Very Good: influences prices as compared to the average by 24.5%. 
- 5/Excellent: influences prices as compared to the average by 28%.

 Waterfront Properties influence price by 24% compared to Properities with no Waterfront. 
 
 School Districts also show an strong correlation to the value of surrouding homes so implemeneting a strategy around purchasing propeities in these areas 
 is highly recommended, as evidenced by the following graphs. 
 
 ![DistrictVsPrice2 (3)](https://user-images.githubusercontent.com/124652720/229214420-6eafa1d3-ef0a-4975-ac5b-5076b8733c0a.png)

And specifically focusing on these neighborhoods: 

![bar_chart](https://user-images.githubusercontent.com/124652720/229215082-112e5359-8295-4125-ae43-049d6a93d550.png)

 
 In conclusion, we would make the following recommendations for purchases:
 

- Average or above Views
- Good or above Grade of Materials (ideally the higher the better to retain value). 
- High SQ Footage of Living Space or Lot Space 
- Waterfront Access
- Converting SQ Footage of Basement Space to multiply the value per foot by a factor of 4. 
- Modifying Garages with Patio spaces atop to maxmize unused space. 
- Avoid neighborhoods with Private Sewer Systems and older buildings.
- Priotizing acquisiton in the following Zip Codes: 98039, 98004, 98033, 98112, 98102, due to the quality of schools. 

## Next Steps

If contracted further we would analyze how public and private amenities effected long term housing values, the relationships between the wealth of local governments, and tax incentives currently employed. Also worth exploring would be how gyms, bars, superstores, public transporation and parks influenced local housing prices. Lastly we would like to refine some of the factoring around SQ footage in reguards to Lot Size. 

## For More Information Contact: 

Kevin Atkinsin
-------------------------------------------
- kmatk620@gmail.com 
- https://github.com/kmatk 
- https://www.linkedin.com/in/kevin-m-atkinson/
-------------------------------------------

Luke Sims
-------------------------------------------
- lukeasims@gmail.com 
- https://github.com/vileincorp 
- https://www.linkedin.com/in/luke-sims-oo7/
-------------------------------------------


Mahum Abid
-------------------------------------------
- mahumabid101@gmail.com 
- https://github.com/mahumabid 
- https://www.linkedin.com/in/mahumabid0505/
-------------------------------------------
