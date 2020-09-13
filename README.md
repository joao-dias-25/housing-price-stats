![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# housing-price-stats
(quick statistic analysis on Sale price)

## Overview

The goal of this project is to practice statistical analysis using the iterative data analysis process with the following dataset.

[Housing Prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

**The goal of your analysis is to identify the most important features of houses that affect the sale prices.**

Because the variable is a price variable you need to make a research on the market to construct your hipoteses.

**correlation doenst mean causation!**

## Real Estate market problems

**very illiquid market , that means very hard to convert into cash.**
**tipical house sale can take months, maybe years.**
**uniqueness in every asset, is dificul to compare assets, and evaluate**

Because of this problems you will need to make a lot a assumptions


## price decomposition

cost estimate for brand new house = lote price( the better the location the expensive it is)
				+ cost of construction( fix cost + variable cost(depending on size and luxus)
				+ extras not included in a typical market house
				+ profit/risk of the promoter/contractor



## Research of the market 

I will try to first research the market in Ames from Iowa State, USA where this data set comes from to possible variables that can make a different is this city.

basic information about Ames

* Unemployment Rate - 1.5%
* Median Income - $42,373
* Median Home Price - $183,400
* Median Age - 23.1 - (the city seems to have a big university campus)

General information:

Pros
 College-town amenities
 Steady employment
 Cost of living
Cons
 Outdoor recreation
 Low diversity
 Harsh winters


How people in Ames get to work:
*- 68.9% drive their own car alone* (transportation)
- 5.0% carpool with others
- 4.0% work from home
- 8.3% take mass transit
-t


after some research on the style of living I started to choose and pick 
some of variables that could have an impact on the price.

The price on real estate its very corellated to the square feet, 
because its one KPY (price per sq.feet) that people/consumers use to evaluate and compare prices.


Possible variables for location: 
-Neighborhood, -Condition1, -Condition2,

Possible variables for Quality:
pool, -LotArea ,-OverallQual, -OverallCond, KitchenQual, MSSubClass, YearBuilt

Possible variables for size:

-LotArea,-GrLivArea, -Fullbath , Halfbath ,Bedrooms,TotRmsAbvGrd, -GarageArea

Possible variable for the market:
-YrSold: MoSold:

Possible variables for extras:
MiscFeature, pool, SaleCondition




## confirm hipoteses

2007 / 2008 crisis

![graph](https://upload.wikimedia.org/wikipedia/commons/9/92/TED_Spread.png)

* price dicrease with the financial crisis 

* pool impact and extras


* ratio between bathrroms and beedrooms

* location area

## Possible variations and hipoteses

take out outliers

segment the market according to the different prices (houses for higher class, houses for middle class, and houses for lower class)

check if the near by transportations and public transports make a diference (from the research 