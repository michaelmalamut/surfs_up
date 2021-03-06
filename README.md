# Surfs Up

## Overview

W. Avy wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. 

### Purpose

The purpose is to provide data to a business if it will be sustainable year-round to run and evalutate if we could expand to other islands, and how conditions would vary for the business.

## Results
I received W. Avy's data on Hawaii weather collections as a sqlite file. I was able to quickly and efficiently compare values for the months of June and December. The same can be done to compare every other month throughout a year with different queries.

**The focus here will be solely on June and December**

* The mean temperature for June and December are within the 70 degree range, however June is slightly warmer at 75 degrees while december is 71 degrees
* Mean temperatures may be within range, but when you look at the lowest temp in december it can get as low as 56 degrees while June is higher at 64
* The max temperatures for June and December seem to be similar, only a 2 degree difference

![June_Temps](https://user-images.githubusercontent.com/97328622/161444477-8fc80f7d-a46a-42c0-b435-0df381372429.png)

![December_Temps](https://user-images.githubusercontent.com/97328622/161444484-c13b3a07-d37e-4d6b-8f39-53522aafd7d0.png)


## Summary

When it comes to considering opening a surf shop, weather and temperature is a major factor in its success. In my opinion, W. Avy can open up shop year-round. Although the shop may experience a temperature as low as 56 degrees in the month of december, this should deter the business from the fact that the month of June and December average a temperature within the mid 70s. Definitely beautiful weather for a surf shop to be open. One additional query I would perform would be changing up the months, like choosing March and September to gain a further understanding on whether the surf shop should remain open all year-round. Another query I would perform is creating histograms and sorting the data frame by dates.
