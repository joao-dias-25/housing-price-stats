# housing-price-stats

*the dataset comes from the city Ames from Iowa State , USA.
*the city seems to have a big university campus
*one airport


*basic information from the city
Ames, Iowa 



12 Reviews | Review This Place | Photos and Maps

Population - 65,005 +13.4% since 2010

Unemployment Rate - 1.5%

Median Income - $42,373

Median Home Price - $183,400

Median Age - 23.1

Comfort Index (Climate) 6.9/10

Pros
 College-town amenities
 Steady employment
 Cost of living
Cons
 Outdoor recreation
 Low diversity
 Harsh winters


How people in Ames get to work:
- 68.9% drive their own car alone
- 5.0% carpool with others
- 4.0% work from home
- 8.3% take mass transit


after some research on the style of living I started to choose and pick 
some of variables that could have an impact on the price.

The price on real estate its very corellated to the square feet, 
because its one KPY (price per sq.feet) that people/consumers use to evaluate and compare prices.

-MSZoning
-LotFrontage
-LotArea
-Utilities
-Neighborhood
-Condition1:
-Condition2:
-BldgType:
-HouseStyle:
-(-OverallQual:, i will exclude -OverallCond:)
-( YearRemodAdd (includes YearBuilt)
-(ExterQual, ExterCond: one of this)
-(BsmtQual,BsmtCond:: (there are tornados is this area)
-Heating: HeatingQC: 
-GrLivArea:
-Fullbath , Halfbath
-Bedroom: or TotRmsAbvGrd
-Kitchen
-KitchenQual:
-GarageArea
-PavedDrive:
-PoolQC:
-MiscVal:
-YrSold: MoSold:
- SaleCondition: Condition of sale


Sale price formula = lot_sqfeet(price_lot/sq feet)+ basement*price + garage*price +  living sp_feet*price_sqfeet + misc-values



