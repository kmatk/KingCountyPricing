
# Phase 2 Project

**Authors**: [Mahum Abid](mailto:mahumabid101@gmail.com), [Kevin Atkinson](mailto:kmatk620@gmail.com), [Luke Sims](mailto:lukeasims@gmail.com)

## Overview

Seattle and King County represent one of the most stable and lucrative parts of the American Real Estate Market. Our client, a major real estate investment firm in the area, contracted us to thoroughly examine the factors around housing and land prices to understand better when and what to buy and sell. We came to the following conclusions: 

- SQ Footage of Living Space and Lot Space played a determinant role in the price
- There are specific neighborhoods that retain their value better, especially properties with views, and quality construction and are situated by the waterfront.
- Converting SQ Footage of Basement Space multiply the value per foot by a factor of 4. 
- Garages with Patio spaces atop are a highly preferable modification. 
- Avoid neighborhoods with Private Sewer Systems and older buildings. 


## Business Problem

Since 2015 the Seattle market has undergone a rapid price increase, 4-5% annually, and now is experiencing an increasingly rapid downturn, with house prices falling 7% this February alone. In light of the recent shifts in the American Real Estate Market, our client is re-evaluating their short and long-term investment strategies to mitigate the fallout. Our client wants to better understand what are the predictive factors for a data-informed, buying and selling strategy for short term and long term investments. The questions we set out to answer for our clients were: 

What were the factors we could numerically evaluate to determine a house's price? 
What overlooked variables could positively influence a home’s price? 
Which properties should they unload from their portfolio? 
What modifications could they make to existing properties to increase value? 

## Data

We used a variety of available data sources ranging from one provided by the client and publically available APIs. 

King County House Sales: 
https://github.com/npagrawal/Kings-County-Real-Estate-Analysis/blob/main/data/kc_house_data.csv

King County Public School: :https://gis-kingcounty.opendata.arcgis.com/datasets/kingcounty::school-districts-in-king-count[…]ea/explore?location=47.527326%2C-121.923521%2C11.00


## Methods

After examining collectively and cleaning individually our data sets, we used a combination of descriptive and analytical statistical methods to determine correlations among our variables. Next, we standardized and ran singular and multiple linear regressions to confirm and quantify our findings. Finally we used a combination of data and business acumen to substantiate relevant conclusions for our stakeholder. 

## Results

In total we analyzed 18 different categories and found the most determinant factors we’re: Location(Zip Code), Lot and Living space SQ Footage, Quality of Views, Waterfront access, and Grade of Construction Materials. 

Properties vacant or rundown in these Zip Codes are inhertnatly more valuable and be invested for a flip or renovation: 
- For every ____ of Living Space SQ footage, we see an increase of ____. 
- For every ____ of Lot Space SQ footage, we see an increase of ____. 
On a scale of 5 relating to types of Views properties, there is a significant value difference. 
- 1/None:  influences prices by _____
- 2/Average: influences prices as compared to the previous category by ________. 
- 3/Fair: influences prices as compared to the previous category by ________. 
- 4/Good: influences prices as compared to the previous category by ________. 
- 5/Excellent: influences prices as compared to the previous category by ________. 

On a scale of 13 relating to Grades of Quality of Materials, there is a significant value difference.
- 1/Cabin: influences prices by ______
- 2/Substandard: influences prices as compared to the previous category by ________. 
- 3/Poor: influences prices as compared to the previous category by ________. 
- 4/Low: influences prices as compared to the previous category by ________. 
- 5/Fair: influences prices as compared to the previous category by ________. 
- 6/Low Average: influences prices as compared to the previous category by ________. 
- 7/Average: influences prices as compared to the previous category by ________. 
- 8/Good: influences prices as compared to the previous category by ________. 
- 9/Better: influences prices as compared to the previous category by ________. 
- 10/Very Good: influences prices as compared to the previous category by ________. 
- 11/Excellent: influences prices as compared to the previous category by ________. 
- 12/Luxury: influences prices as compared to the previous category by ________. 
- 13/Mansion: influences prices as compared to the previous category by ________. 
 Waterfront Properties influence price by _______, In conclusion, we would make the following recommendations for purchases: focus on 

In conclusion our best strategy for our client to position themselves during shifting markets is to unload properties devoid of these features and acquire properties with the following characteristics or to have the following features: 

Structures or Land in the following Zip Codes: 
- Average or above Views
- Good or above Grade of Materials (ideally the higher the better to retain value). 
- High SQ Footage of Living Space or Lot Space 
- Waterfront Access
- Converting SQ Footage of Basement Space to multiply the value per foot by a factor of 4. 
- Modifying Garages with Patio spaces atop to maxmize unused space. 
- Avoid neighborhoods with Private Sewer Systems and older buildings.

## Next Steps

If contracted further we would analyze how public and private amenities affected long term housing values, the relationships between the wealth of local governments, and tax incentives currently employed. Also worth exploring would be how gyms, bars, superstores, public transporation and parks influenced local housing prices.  

## For More Information

## Repository Structure

```
├── code
│   ├── 
│   ├── 
│   ├── 
│   └── 
├── data
├── images
├── README.md
├── 
└── 
```
