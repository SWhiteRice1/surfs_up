# surfs_up
## Overview of Project
##### Purpose
   The purpose of this analysis was to facilitate reporting on W.Avy's new surf shop in Hawaii. This project was to particularl look at the temperature trends of June and December in Oahu to determine if the surf and ice cream shop can work year-round. 
#### Code
  Using sql.lite, pandas, and VScode we grabbed the temperature data for Oahu.
  #### Resources:hawaii.sqllite

## Results
For June the sqllite data built into a Pandas Dataframe, showed the average temperatures to be around 75. 
```
	June Temps
count	1700.000000
mean	74.944118
std	3.257417
min	64.000000
25%	73.000000
50%	75.000000
75%	77.000000
max	85.000000
```
For December the avergage temperatures in Oahu are 71.
```
	December Temps
count	1517.000000
mean	71.041529
std	3.745920
min	56.000000
25%	69.000000
50%	71.000000
75%	74.000000
max	83.000000
```

The results of the temperatures for June and December reveal three minor differences
- December tempertures are only 4 degrees lower on average than June
- December max temperature is only 2 degrees lower than June
- December's lowest temperture is 56 degrees while June's lowest temperature is 64.

## Summary
Although there are a couple differences between the temperatures of June and December, this data demonstrates that the surf shop and ice cream could do well year-round in Oahu with average temperatures in the 70s. However, additional queries on the stations where this data comes from for June and December and how often it rains during these months would also be valuable for determining the sustainability of this ice cream/ surf shop.
  
