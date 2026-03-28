# DS 4320 Project 1: Forecasting Primary Productivity for Climate Change Mitigation
 

Executive summary: TODO

Name: Elaine Liu

Net ID: bpa2hu

DOI: TODO

Press Release: ADDLINK

Data: [data folder](https://myuva-my.sharepoint.com/:f:/g/personal/bpa2hu_virginia_edu/IgAliK4bc6AsQruETaP0ny1ZARABee2bor8mKPRcuSiCsW0?e=HmfbTM)

Pipeline: ADDLINK

License: MIT License. [license file](https://github.com/elaineliu05/databydesign_p1/blob/main/LICENSE)

## Problem Definition:

**General problem**: Forecasting climate change

**Refined specific problem statement**:

Forecasting oceanic primary productivity values to determine carbon capture rates. This will be done using data from the Bermuda Atlantic Time-series study dataset, since they have a long standing time series dataset with measured primary productivity values

**Rationale**:

Forecasting climate change is a big problem to tackle because climate change is impacted by many different interactions across the atmosphere, land, and ocean. To address and understand global climate change, full earth system models and datasets are needed, which may not be realistic or computationally possible. I chose to narrow down the scope of this problem to the ocean's impact on climate change, specifically using primary productivity. Primary productivity is the rate at which phytoplankton perform photosysnthesis, aka turning carbon dioxide and sunlight into energy. This is the main method the ocean is able to absorb atmospheric carbon and help mitigate climate change. With this narrowed down scope, the broader problem of "forecasting climate change" is much easier to tackle and more measurable.

**Motivation**:

Primary productivity plays an important role in helping mitigate climate change, since it takes atmospheric carbon and turns it into energy for animals in the ecosystem. Phytoplankton are able to take in enourmous amounts of carbon, making this process an essential part of mitigating climate change as a whole. Forecasting primary productivity values is valuable because it can help tell us how much carbon the ocean can take in in the future, allowing us to accordingly adjust climate change mitigation strategies. Ie if future primary productivity values decrease, then the ocean will take in less carbon, climate change will escalate, and we will need to take action to reduce our carbon emissions.

**Headline**:

Predicting Primary Productivity: Helping Forecast Climate Change Using Our Oceans. ADDLINK


## Domain Exposition:

**Terminology**:

| Term | Description | 
|---|---|
| Primary Productivity | The rate phytoplankton can convert carbon dioxide into organic matter. This process is done through photosynthesis, aka turning sunlight into energy. In this dataset, it is measured in milligrams of carbon per meters cubed per day | 
Phytoplankton | Microscopic organisms that are able to perform photosysnthesis. They are the basis of marine ecosystems and drive oceanic primary productivity. | 
BATS | Stands for Bermuda Atlantic Time-series study. This study is conducted in the Atlantic ocean and have been performing long term measurements of oceanic variables, such as primary productivity. They have one of the longest time series datasets of oceanic measurements. | 
Climate Change | Refers to the long term shift in temperature and weather, which has largely been due to huuman driven carbon emissions. Climate change has significant consequences on the environment, such as rising sea levels, extreme weather events, etc. One factor that helps mitigate climate change is primary productivity, since large amounts of carbon dioxide is removed from the atmosphere using photosynthesis. | 
Carbon Cycle | The carbon cycle refers to the global movement of carbon through the atmosphere, ocean, and land. Oceanic primary productivity plays a major part in this cycle, since phytoplankton are able to absorb a large amount of carbon, perform photosysnthsis, and convert that into energy. | 
Time Series | Times series data is data that is recorded over a sequence of time. This allows us to see changes over time, which give us insight into potential trends/patterns in the data. In this case, time series data is relevant because primary productivity follows seasonal cycles. Ie primary productivity increases in the summer because there is more sunlight for photosynthesis, and primary productivity decreases in the winter. | 
Predictive forecasting | Forecasting using machine learning methods uses historical data to analyze patterns. This way, we can project future outcomes based on information we know about the past. Generally, large time series datasets are needed to make accurate and robust predictions. | 

**Domain**:

This work combines domains from environmental science and data science. We are attempting to predict primary productivity values to see how it will impact climate change in the future. Primary productivity is an essential measurement to look at because it represent sthe rate of photosynthesis hapenning. Specifically, we will focus on oceanic primary productivity with data from the Bermuda Atlantic Time Series Study (BATS), since they have a long sanding dataset of primary productivity values. Using these long term time series measurements, we will be able to train machine learning models to use environmental variables to forecast primary productivity values. With this information, we will be able to better adapt to climate change impacts in the future.


**Background reading**:

link to: [folder](https://myuva-my.sharepoint.com/:f:/g/personal/bpa2hu_virginia_edu/IgCN8VwFUjTuR6Sdv8rNojNwAfWudNasFactl1rbGVHurk0?e=aPaQjo) (background reading folder)
1. https://www.mdpi.com/2072-4292/12/5/826
2. https://www.soest.hawaii.edu/oceanography/courses/OCN626/2008_OCN%20626/steinberg_Deepsea.pdf
3. https://www.nature.com/articles/s41598-020-59989-y
4. https://link.springer.com/article/10.1007/s12040-025-02525-1
5. https://www.sciencedirect.com/science/article/pii/S0272771425001210

**Summary Table**:

| Title | Description | Link |
|---|---|---|
| Primary Production, an Index of Climate Change in the Ocean: Satellite-Based Estimates over Two Decades | Research paper that investigates the long term patterns of primary productivity in the ocean using satellite observations. Dives deep into what primary productivity is and its impact on the global carbon cycle. Emphasizes its importance of mitigating climate change, as well as an essential indicator of climate driven changes. Research suggests that primary productivity values will become more variable, and forecasts of primary productivity are essential. | [link](https://www.mdpi.com/2072-4292/12/5/826) |
| Overview of the U.S. Bermuda Atlantic Time-series Study (BATS) | This research paper is the paper describing BATS, the Bermuda Atlantic Time series Study. It explains the objective of the program, to monitor long term ocean biogeochemical variability in the Atlantic Ocean, as well as how measurements are made. They emphasize that BATS is one of the longest continuous places measuring ocean variables and providing time series data, which will be valuable for future data analysis. | [link](https://www.soest.hawaii.edu/oceanography/courses/OCN626/2008_OCN%20626/steinberg_Deepsea.pdf) |
| Machine learning identifies a strong association between warming and reduced primary productivity in an oligotrophic ocean gyre | This research paper examines how climate change has had an impact on ocean warming, which is affecting phytoplankton primary productivity. They also used data from the BATS dataset, so this research is being conducted in the same study area. In the paper itself, they mention they used machine learning to determine complex relationships between environmental variables. They provide evidence that climate change is decreaisng primary productivity values in certain ocean regions, meaning that we can expect to find a decreaisng trend in primary productivity in the future. | [link](https://www.nature.com/articles/s41598-020-59989-y) |
| A comparison of machine learning algorithms for predicting gross primary productivity of the Western Ghats region in India using reanalysis and satellite data | This research paper evaluates machine learning models to predict primary productivity in India. Their objective was to improve estimates of carbon sequestiation and support climate change mitigation strategies. They found tha the decision tree model performed the best out of all the models they tested. Some metrics they used for comparision included r^2, mae, and rmse. They found that machine lerning approaches were useful for estimating primary productvity, especially in regions with less data. | [link](https://link.springer.com/article/10.1007/s12040-025-02525-1) |
| Estimating primary production in the California Current System using machine learning methods | This research paper evaluates machine learning approaches for estimary primary producivity values in the California ocean system. Some of the machine learning methods they used were random forest regression, xgboost, and bagging. These were compared to traditional physical system primary productivity models to make predictions. They found that the machine learning models outperformed the traditional ones, with XGBoost having the best predictive performance. | [link](https://www.sciencedirect.com/science/article/pii/S0272771425001210) |


## Data Creation

The dataset for my project 1 can be found at this (link)[https://www.bco-dmo.org/project/2124]. This includes all of the data from the BATS research study. This includes CSV files for all measurements regarding BATS data, as well as data dictionaries and citations for all of them. There are 9 different datasets listed from the different biogeochemical ocean measurements that they take. 

I chose to focus on 4 different datasets: the primary productivity estimates, discrete bottle samples, HPLC and fluorometric-derived phytoplankton pigment concentrations, and CTD profiles. There is an option to download the CSV file for each dataset, which lists the parameters, funding, instruments, deployments, and archives. The specific table names are included below:

Data Creation Table (with links to code): 

ADD LINKS TO CODE LATER 
| Table Name | Description | Link to Code |
|---|---|---|
| bats_pp | Primary productivity estimates from the incubation of seawater collected at the Bermuda Atlantic Time-series Study (BATS) site from December 1988 through June 2025 | Cell C1 |
| bats_bot | Discrete bottle samples collected at the Bermuda Atlantic Time-series Study (BATS) site in the Sargasso Sea from October 1988 through June 2025 | Cell C2 |
| bats_pig | HPLC and fluorometric-derived phytoplankton pigment concentrations from seawater collected at the Bermuda Atlantic Time-series Study (BATS) site from October 1988 through June 2025 | Cell C2 |
| bats_ctd | Two decibar averaged CTD profiles collected at the Bermuda Atlantic Time-series Study (BATS) site from October 1988 through June 2025 | Cell C2 |

**Bias Identification**:

There are many ways bias could have been introduced in the data sampling and selection process. The first possibility for bias was during data collection - all measurements are taken at a single fixed location in the study area, which introduces spatial bias. This allowed them to perform consistent monitoring, but it limits generalizability to other ocean regions. Temporal bias is also introduced, since measurements are taken during monthly cruises and within a specific window each time. This could mean there is short-term variability impacting the data collected. Additionally, after all the data is collected and measured, there is a lot of processing that needs to be done, which means there is experimental bias. For instance, there is incubation and filtering that occur with the nutrient measurements that could affect the values seen. Lastly, when data was entered into the database, there was cleaning and merging being done. Things like merging datasets and converting missing values could introduce integration bias.

**Bias Mitigation**:

Although there are many ways to introduce bias, there are also many methods to help mitigate bias. For one, quality control flags are used to quantify and handle uncertainty. For some of the datasets, for each measurement, there is another column that acts as the quality control flag to help handle uncertainty. The temporal bias introduced can be mitigated by narrowing the data analysis to only this specific site. Because we are restricting our inferences, we cannot make generalizations to other areas, but we can help mitigate this bias. Additionally, data processing bias can be addressed by using the most updated dataset versions they have available on the website, and also checking for consistency between cruises when using multiple datasets.

**Rationale**:

There were many important and critical decisions that needed to be made when compiling this dataset together. The first thing that stood out to me was that this data is structured by time and then depth. For each cruise, measurements at multiple depths are taken, making this a multivariate time series problem. Since each depth has measurements, we could analyze each depth separately or integrate across depths to estimate total productivity. Ultimately, I think I chose not to integrate across depths so that we have a more complete understanding of primary productivity across ocean layers. Another decision was how to handle the quality flags. I needed to choose how much uncertainty I was willing to take in when making the data, which basically meant determining a threshold on the tradeoff between data quantity and data quality. I ultimately decided to keep all the data no matter the quality, since a large amount of data is needed to train models later during data analysis. Lastly, since this is a time series dataset, I needed to decide whether to aggregate by time or not. Since these are monthly cruises, I could aggregate to annual means or keep them as individuals. For the analysis, I think I will keep the monthly time steps so I can see trends throughout the year.

## Metadata

**Schema ER Diagram**: 
<img width="483" height="669" alt="image" src="https://github.com/user-attachments/assets/65ca6f68-e235-476a-8993-561b4439e2f0" />

**Table of Tables in Dataset**:

| Table Name | Description | Link to Code |
|---|---|---|
| Primary Productivity | Contains measurements of primary productivity estimates at the BATS site from 1988 to June 2025. Measurements were collected in situ at depths ranging from the surface to 140 meters. | [link](https://drive.google.com/file/d/1ekk2X68H3gcmCKY525-cOa9S79sX3uYV/view?usp=sharing) |
| Discrete Bottle Measurements | Contains measurements of discrete bottle samples collected at the BATS site from October 1988 through June 2025. Measurements were collected on monthly cruises and include variables such as depth, temperature, and various nutrients. | [link](https://drive.google.com/file/d/1qOnIcw67wfZphVeeHM6kPmnOI-beQJ2g/view?usp=sharing) |
| Phytoplankton Pigment and Chlorophyll Measurements | Contains measurements of HPLC and fluorometric-derived phytoplankton pigment concentrations from seawater collected at the BATS site from October 1988 through June 2025. Samples were collected from the upper 250 meters of the water column. Various processing steps were performed to obtain values. | [link](https://drive.google.com/file/d/1lTfcmLyB5Q5wOXgG1tmq5Zh8a1fCddIB/view?usp=sharing) |
| CTD Profiles | Contains measurmeents of two decibar averaged CTD profiles collected at BATS site from October 1988 through June 2025. Important measurements include beam attenuation, relative fluorescence, and photosynthetic active radiation. | [link](https://drive.google.com/file/d/1KRzz_XbmxbXBWbpGIePiMiBAFm70AOYi/view?usp=sharing) |

**Data Dictionary**:

Primary Productivity

| Variable | Description | Example |
|---|---|---|
| ID (int) | Sample identification; identifies cruise and cast | ie 1000308001 |
| Date (datetime) | date of cruise departure in yymmdd format | ie 1988-10-20 |
| Vessel (string) | Name of vessel used for cruise. Unitless. | ie R/V Weatherbird |
| Cruise_type (string)|  Cruise type (BATS Core, Bloom A, or Bloom B). | ie BATS Core |
| Cruise_num (string) | BATS Cruise number. unitless | ie 10003 |
| Depth (float) | Collection depth of sample. units: meters | ie 20 |
| Pressure (float) | Pressure (dbar) from CTD. | ie 4.0 |
| dark (float) | 14C Primary Production dark bottle. Measured in mgC/m^3/day. | ie 6.5 |
| pp (float) |Primary Production Mean Light values - Dark value. Measured in mgC/m^3/day. | ie 3.8 |

Discrete Bottle Measurements

| Variable | Description | Example |
|---|---|---|
| ID (int) | Sample identification; identifies cruise and cast | ie 1000308001 |
| Date (datetime) | date of cruise departure in yymmdd format | ie 1988-10-20 |
| Vessel (string) | Name of vessel used for cruise. Unitless. | ie R/V Weatherbird |
| Cruise_type (string)|  Cruise type (BATS Core, Bloom A, or Bloom B). | ie BATS Core |
| Cruise_num (string) | BATS Cruise number. unitless | ie 10003 |
| Depth (float) | Collection depth of sample. units: meters | ie 20 |
| Temperature (float)| Temperature in ITS-90 standard. Measured in degrees Celsius ( °C)| ie 3.0|
| Salinity (float)| Salinity-1 measurement on PSS-78 scale. Dimensionless| ie 5.2 |
| NO2 (float)| Nitrite. measured in micromoles per kilogram (umol/kg). |  ie 0.5 |
| PO4 (float)| Phosphate. measured in micromoles per kilogram (umol/kg).| ie 9.0|
| POC (float)| Particulate organic carbon. measured in micrograms per kilogram (ug/kg).| ie 3.4|
| PON (float)|  Particulate organic nitrogen. measured in micrograms per kilogram (ug/kg)| ie 3.4|
| TOC (float)|  Total organic carbon. measured in micromoles per kilogram (umol/kg). | ie 4.2|
| TN (float)|Total Nitrogen (prior to BATS 121, DON is reported instead of TN). measured in micromoles per kilogram (umol/kg). | ie 2.1|
| Bac_Enum (float)| Bacterial enumeration. measured in cells times 10^8 per kilogram. | ie 2.2|
| POP (float)|  Particulate organic phosphorus. measured in micromoles per kilogram (umol/kg).  | ie 2.1|
| TDP (float)| Total dissolved phsophorus. measured in nanomoles per kilogram (nmol/kg). | ie 0.5|
| yymmdd (datetime)| date of cruise departure in yymmdd format.| ie 1988-10-20|


HPLC/Chlorophyll (Pigments)

| Variable | Description | Example |
|---|---|---|
| ID (int) | Sample identification; identifies cruise and cast | ie 1000308001 |
| Date (datetime) | date of cruise departure in yymmdd format | ie 1988-10-20 |
| Vessel (string) | Name of vessel used for cruise. Unitless. | ie R/V Weatherbird |
| Cruise_type (string)|  Cruise type (BATS Core, Bloom A, or Bloom B). | ie BATS Core |
| Cruise_num (string) | BATS Cruise number. unitless | ie 10003 |
| Depth (float) | Collection depth of sample. units: meters | ie 20 |
| Cast (string)| Cast Number (1-80 = CTD, 81-99 = Hydrocast). unitless.|  ie 1|
| Cast_type (string)| Cast type (CTD or Hydrocast). unitless.|  ie CTD|
| Bottle_number (int)| Niskin bottle number. unitless.|  ie 100|
| p1 (float)| pigment 1 = Chlorophyll c3. measured in nanograms per kilogram (ng/kg).| ie 5.5|
| p2 (float)| Chlorophyllide_a. measured in nanograms per kilogram (ng/kg).|  ie 10.5|
| p3 (float)| Chlorophyll c1 + c2. measured in nanograms per kilogram (ng/kg).| ie 7.1|
| p14 (float)| pigment 14 = Chlorophyll a. measured in nanograms per kilogram (ng/kg). |  ie 13.0|
| p16 (float)| pigment 16 = fluorometric Chlorophyll a. measured in micrograms per kilogram (ug/kg).| ie 10.5|


CTD Profiles

| Variable | Description | Example |
|---|---|---|
| ID (int) | Sample identification; identifies cruise and cast | ie 1000308001 |
| ISO_DateTime (datetime) | CTD deployment time in UTC format. | ie 1988-10-20 |
| Vessel (string) | Name of vessel used for cruise. Unitless. | ie R/V Weatherbird |
| Cruise_type (string)|  Cruise type (BATS Core, Bloom A, or Bloom B). | ie BATS Core |
| Cruise_num (string) | BATS Cruise number. unitless | ie 10003 |
| Depth (float) | Collection depth of sample. units: meters | ie 20 |
| Pressure (float) | Pressure (dbar) from CTD. | ie 4.0 |
| BAC (float)| Beam Attenuation Coefficient. measure in Coefficient reciprocal meters (1/m). |ie 0.438 |
| Flu (float)| Fluorescence. measured in relative fluorescence units (RFU).|  ie 0.67.|
| PAR (float)| Photosynthetically Active Radiation (PAR). Measured in microeinsteins per meter squared per second (uE/m2/s) | ie 5.2 |


**Data Dictionary - Quantifying Uncertainty**:

Since these are in situ measurements, there is a lot of uncertainty surrounding the numerical features. Luckily, the bats website helps quantify uncertainty values during their preprocessing steps. For instance, quality control flags are set for most variables, meaning that for each observation, there is a numerical quality control flag that tells you how confident they are in this value. If the quality control flag is high, it means that its more possible that this is bad quality data, and could be removed if you want a more robust analysis. This helps indicate data reliability to the user and lets the user choose how much uncertainty they are willing to risk. 

Quality control flags are set for primary productivity values, so we are able to quantify uncertainty for our target variable. Specifically, in the table, the first record of primary productivity has a quality control flag of 2, which means that we can be relatively certain that we can trust this measurement. The second row has a quality control flag of 9, and the value is missing, meaning that they could not reliably measure primary productivity at that depth. Another important variable is depth, which is measured in the CTD table and is generally precise. They do discrete sampling every 20 m interval, so we can generally quantify uncertainty to be 0. However, this introduces resolution uncertainty. This can be handled by treating depth as binned or discrete levels. Each dataset also has time variables like datetime since this is a time series dataset. There is very little uncertainty with these numbers, since they used ISO standardized formats, so we can also quantify it to be 0. Overall, the uncertainty in the numerical values is primarily systematic and stems from how the data was processed, rather than measurement error. They have helped quantify error through quality flag variables and standardized procedures.

**Data**:

Link to UVA OneDrive Folder: (here)[https://myuva-my.sharepoint.com/:f:/g/personal/bpa2hu_virginia_edu/IgAliK4bc6AsQruETaP0ny1ZAWyETGFHBKURFV5wC6UvnWU?e=f4WWjt]
