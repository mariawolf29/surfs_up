# surfs_up

## Approach 1 
using method groupby to calculate the average precipitation per year across all of the stations for the month of December and June looking at percentiles we can say that:
- average precipitation in June is 65.5% of the December's precipitation, 0.138 vs. 0.21
- year with min precipitation in December is almost 50% higher than min precipitation in June (0.0896 vs. 0.0422)
-  the same can be said about year with max precipitation. We also have to mention that year 2010 holds the highest precipitation for the month of December and the lowest precipitation for the month of June. To better understand the data, I would recommend this analysis on  more data (years)
- 50th percentile - half of Decembers have precipitation lower than 0.1884 and 0.1248 for June, again December's precipitation is 66% higher than June's
- 75th percentile, only 25% Decembers have precipitation higher than 0.2005 and 25th of June's precipitation higher than 0.1612 

```
	     December	June
count	       7	       8
mean	0.210961	0.138185
std	    0.115829	0.062694
min	    0.089604	0.042241
25%	    0.16926	    0.114265
50%	    0.188439	0.124766
75%	    0.200538	0.161224
max	    0.459087	0.240142
```

## Approach 2
calculating across all of the stations and years without the method group by
- average precipitation in December is 0.2168 and 0.1363 in June (62.89% of December's level)
- 25th percentile- we can say that 25 measurements in June and December were without rain
- 50th percentile- half of the measurements in the month of December across all stations and years has precipitation lower than 0.03, for the month of June 0.02 which is 66.66% of the December's level
- highest precipitation measured in December is 6.42 and 4.43 in June (69% of December’s) level

```
	    December	June
count	1405	    1574
mean	0.216819	0.13636
std	    0.541399	0.335731
min	    0	        0
25%	    0	        0
50%	    0.03	    0.02
75%	    0.15	    0.12
max	    6.42	    4.43
```

## Recommendations:
- I would recommend to collect data for more years, to have better understanding 
- analysis to compare all months
- analysis based on the location - analyze precipitation levels on the possible store locations, it could make a huge difference
- analysis based on the number of sunny days
- analysis based on the temperature





