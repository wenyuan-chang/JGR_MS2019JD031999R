#### Title: Asymmetrical Linkages between Multi-frequency Atmospheric Waves and Variations in Winter PM2.5 Concentrations in Northern China during 2013–2019
#### Manuscript submitted to Journal of Geophysical Research

#### 1. Data description:
The page provides the instantaneous PM2.5 concentrations (ug/m3) at 06:00UTC for six winers in 2013-2019 that are in use for the manuscript submitted to JGR_MS2019JD031999R.
The raw data was downloaded from the http://data.epmap.org. The raw data was preprocessed in the following steps to attain the data in this page: 
1. Remove the sites that have missing values more than 10% of the whole records over the six winters.
2. The instantaneous PM2.5 concentration of each city was averaged from the PM2.5 values at the reserving sites in the city.
3. The city without continuous missing values longer than three days was kept.

In the download "tar" file, there are 36 files (pm25.yyyymm.txt) and each has the instantaneous PM2.5 concentration (ug/m3) at 06:00UTC in a month from October to March in 2013-2019. Each file has 103 rows indicating 103 cities and n columns, where n denotes the amount of days in that month. A file "zlonlat.txt" in the download "tar" file contains three columns which are longitude, latitude and identification number of the city. The lon/lat of a city is the average lon/lat of the reserving sites in the city. To attain the final PM2.5 data in the mansucript, the remaining missing values in the download files are need to be further substituted by the interpolation values between the preceding and following PM2.5 concentrations.

#### 2. Missing values:
-99.

#### 3. Download link

[Click to the data server](http://www.lapc.ac.cn/t.php?t=1586264287)
