# Title-Here
*Probing effects of natural calamities on crops*


## Special Precipitation Index to predict drought and potential floods
Standardized Precipitation Index (SPI) expresses the actual rainfall as standardized departure from rainfall probability distribution function and, hence, this index has gained importance in recent years as a potential drought indicator permitting comparisons across space and time. Title-here intends to predict droughts and potential floods by computing SPI by averaging data over last 30 years. Computation of SPI requires long term data on precipitation to determine the probability distribution function which is then transformed to normal distribution with mean of zero and standard deviation of one.Computation of SPI with time series data, at a monthly scale, was carried out based on the two parameter gamma distribution function.

<img src="https://github.com/AbhilashRN/Title-Here/blob/master/spi%20index%20table.png" height="180" weight="240">

SPI is advantageous to use as it provides a time averaged value for a specific region and not the country or the world as a whole. It not only tells us which regions will face a drought but also the severity to which the drought will strike that area(referenced in above image). This is also an appropriate tool for determining crop yield as it can be directly related to the water requirements of a crop.


## Predicting Frost Frequency from Cloud Cover and Minimum Temperature 
Perennial crops are prone to be damaged from late-spring frost events. Title-Here intends to predict the frost frequency in a month by taking in Cloud Cover, Minimum Temperature and Max-Min Difference as input variables and creating classification labels.

| Frost Frequency  | Label |
| --------- |--------- |
| 0 | Perfectly Normal   |
| < 3 | Slight aberration  |
| < 7 | Mild issues  |
| < 12 | Potenial problem  |
| >13 | Serious Hazard |

Frost damage occurs to legume pods and seeds, canola pods, flowers and seeds and cereal grains, flowers, or whole heads if the stem freezes around the flag leaf or in the boot. Climate irregularities and recent events have further added discrepancy and deviation from traditional frost frequency mechanisms especially in temperate regions in our country and around the planet

## Probing Crop-yield versus Potential Evapotranspiration
Evapotranspiration(ET) is the process by which water is transferred from the land to the atmosphere by evaporation from the soil and other surfaces and by transpiration from plants. The two types are reference ET, which is the recorded measure of ET in a given area, and Potential ET, which is the ideal ET where an unlimited water source is assumed to exist in the area.

Depending on the difference between the RET and PET values we can predict the crop yield of a certain plant by taking into consideration the yield response factor, which is a arbitrary quantitative measure of how tolerant a crop is to a water deficit. The net ET shows the amount of precipitation which inturn affects crop yield. Looking at the severity of a drought we can predict how crop yield is affected and possible irrigation methods can be suggested.


## Dataset used 
http://www.indiawaterportal.org/met_data/

States of Maharastra, Karnataka, Himachal Pradesh, Uttar Pradesh and Assam will be targeted for a thorough and generic picture of Climatic effects on crop.
