
# Table of contents
- [Table of contents](#table-of-contents)
  - [Time Series](#time-series)
      - [Australian demand](#australian-demand)
      - [Spanish demand](#spanish-demand)
      - [ETT datasets](#ett-datasets)
      - [CIF2016](#cif2016)
      - [Exchange rate](#exchange-rate)
      - [M3 and M4](#m3-and-m4)
      - [SAGRA](#sagra)
      - [Pollution](#pollution)
      - [Traffic](#traffic)
      - [Traffic perms bay](#traffic-perms-bay)
      - [Traffic metr la](#traffic-metr-la)
      - [Wiki web traffic](#wiki-web-traffic)

## Time Series

#### Australian demand

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Australian Energy Demand Time Series                                                                                                                |
| **Number of Instances**  | 26,304                                                                                                                                           |
| **Number of Features**   | 3                                                                                                                                                |
| **Temporal frequency**  | Hourly                                                                                                                                          |
| **Period**  | 2012-01-01 to 2014-12-31                                                                                                                                           |
| **Feature Types**        | Real, Categorical, Time Series                                                                                                                     |
| **Associated Tasks**     | Forecasting, Time Series Analysis                                                                                                                  |
| **Subject Area**         | Energy, Economics                                                                                                                                   |
| **Has Missing Values?**  | No                                                                                           |
| **Dataset Characteristics** | Time Series, Multivariate                                                                                                                                   |
| **Dataset Origin**       | Data comes from the Australian Energy Market Operator (AEMO) and includes historical demand. This data is critical for understanding electricity usage patterns and optimizing energy grid management in Australia.                         |
| **Prediction Task**      | Predict future electricity demand based on historical energy consumption data.                                   |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `DateTime`: (time) Timestamp indicating the date and time of the recorded demand                                                                |
|                          | 2. `Demand`: (real) Energy demand in megawatts (MW)                                                                                                |
|                          | 3. `Temperature`: (real) Temperature data associated with the region at the time of demand                                                          |

|                          | 5. `Holiday`: (binary) Whether the timestamp falls on a public holiday (1 = Yes, 0 = No)                                                           |                                                                 |


#### Spanish demand

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Australian Energy Demand Time Series                                                                                                                |
| **Number of Instances**  | 26,304                                                                                                                                           |
| **Number of Features**   | 1                                                                                                                                                |
| **Temporal frequency**  | 10 minutes                                                                                                                                          |
| **Period**  | 2014-01-01 to 2022-12-31                                                                                                                                           |
| **Feature Types**        | Real, Categorical, Time Series                                                                                                                     |
| **Associated Tasks**     | Forecasting, Time Series Analysis                                                                                                                  |
| **Subject Area**         | Energy, Economics                                                                                                                                   |
| **Has Missing Values?**  | No                                                                                           |
| **Dataset Characteristics** | Time Series, Univariate                                                                                                                                   |
| **Dataset Origin**       | Data comes from the Red Eléctrica Española (REE) ESIOS API and includes historical demand.                         |
| **Prediction Task**      | Predict future electricity demand based on historical energy consumption.                                   |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `DateTime`: (time) Timestamp indicating the date and time of the recorded demand                                                                |
|                          | 2. `Demand`: (real) Energy demand in megawatts (MW)                                                                                                |

#### ETT datasets

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | ETTh1 and ETTh2 Time Series                                                                                                                         |
| **Number of Instances**  | 17,420 (ETTh1), 17,420 (ETTh2)                                                                                                                      |
| **Number of Features**   | 7                                                                                                                                                   |
| **Temporal Frequency**   | Hourly                                                                                                                                              |
| **Period**               | ETTh1: 2016-07-01 to 2018-07-01 <br> ETTh2: 2016-07-01 to 2018-07-01                                                                                |
| **Feature Types**        | Real, Categorical, Time Series                                                                                                                      |
| **Associated Tasks**     | Forecasting, Time Series Analysis                                                                                                                   |
| **Subject Area**         | Energy, Economics                                                                                                                                   |
| **Has Missing Values?**  | No                                                                                                                                                  |
| **Dataset Characteristics** | Time Series, Multivariate                                                                                                                        |
| **Dataset Origin**       | These datasets are part of the Electricity Transformer Temperature (ETT) series collected from a single power station in China. The data includes various load features and outdoor temperature measurements. It is used primarily for time series forecasting. |
| **Prediction Task**      | Predict future load and temperature values based on historical data.                                                                                 |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `DateTime`: (time) Timestamp indicating the date and time of the recorded values                                                                 |
|                          | 2. `OT`: (real) Outdoor temperature at the given timestamp                                                                                          |
|                          | 3. `HUFL`: (real) High-use transformer load at the given timestamp                                                                                  |
|                          | 4. `HULL`: (real) Low-use transformer load at the given timestamp                                                                                   |
|                          | 5. `MUFL`: (real) Medium-use transformer load at the given timestamp                                                                                |
|                          | 6. `MULL`: (real) Medium-use transformer low load at the given timestamp                                                                            |
|                          | 7. `LUFL`: (real) Low-use transformer full load                                                                                                     |
| **Dataset URL**          | [ETT repository](https://github.com/zhouhaoyi/ETDataset)                                                                                 |


#### CIF2016

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | CIF2016o6 and CIF2016o12 Time Series                                                                                                               |
| **Number of Instances**  | 72 time series with ~30 to ~80 instances (depending of the series)                                                                                                              |
| **Number of Features**   | 1                                                                                                                                                   |
| **Temporal Frequency**   | Monthly                                                                                                                                               |
| **Period**               | Undefined                                                                        |
| **Feature Types**        | Real                                                                                                                     |
| **Associated Tasks**     | Time Series Analysis                                                                                                               |
| **Subject Area**         | Climate, Environment                                                                                                                                 |
| **Has Missing Values?**  | Yes                                                                                                                                                 |
| **Dataset Characteristics** | Time Series, Multivariate                                                                                                                        |
| **Dataset Origin**       | These datasets consist of climate and environmental data collected from various meteorological stations across different regions, specifically tailored for classification tasks in machine learning. |
| **Prediction Task**      | Predict baking indexes for a period of 6 or 12 months ahead.                                                                       |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `target`: Banking domain index.                                                                                                   |
|                          | 2. `Group_idx`: Time series index                                                                                                   |
|                          | 3. `Time_idx`: Timestamp index                                                                                                 |
| **Dataset URL**          | [CIF2016](https://zenodo.org/records/3904073)                                                                                 |

#### Exchange rate

Here is the table for the **Exchange Rate Dataset** commonly used in data analysis and forecasting:

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Exchange Rate Time Series                                                                                                                          |
| **Number of Instances**  | 7500.                                             |
| **Number of Features**   | 1                                                                                                                                                   |
| **Temporal Frequency**   | Daily                                                                                                                                               |
| **Period**               | From 1999 to the ??.                                                   |
| **Feature Types**        | Real, Time Series                                                                                                                                 |
| **Associated Tasks**     | Forecasting, Time Series Analysis                                                                                                                  |
| **Subject Area**         | Economics, Finance                                                                                                                                 |
| **Has Missing Values?**  | Yes, depending on the dataset used.                                                                                                               |
| **Dataset Characteristics** | Time Series, Multivariate                                                                                                                        |
| **Dataset Origin**       | The dataset is often compiled from various financial sources, including central banks, financial institutions, and historical market data.          |
| **Prediction Task**      | Predict future exchange rates based on historical data and trends.                                                                                 |
| **Attributes**           |                                                                                                                                                     |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `target`: Rate conversion between the currencies.                                                                                                   |
|                          | 2. `Group_idx`: Time series index                                                                                                   |
|                          | 3. `Time_idx`: Timestamp index                                                                                                 |
| **Dataset URL**          | [ExchangeRate](https://www.kaggle.com/datasets/federalreserve/exchange-rates/data)                                                                                 |


#### M3 and M4

Here’s the table for the **monthly versions of the M3 and M4 datasets**, which are widely used for time series forecasting competitions:

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | M3 and M4 Monthly Time Series Datasets                                                                                                            |
| **Number of Instances**  | M3: 3,003 series; M4: 1,500 series                                                                                                               |
| **Number of Features**   | Varies by dataset; typically includes several features for each series.                                                                            |
| **Temporal Frequency**   | Monthly                                                                                                                                             |
| **Period**               | M3: January 1990 to December 1994 <br> M4: January 2016 to December 2018                                                                             |
| **Feature Types**        | Real, Categorical, Time Series                                                                                                                     |
| **Associated Tasks**     | Forecasting, Time Series Analysis                                                                                                                  |
| **Subject Area**         | Business, Economics, Forecasting                                                                                                                  |
| **Has Missing Values?**  | Yes, there may be gaps in some series.                                                                                                            |
| **Dataset Characteristics** | Time Series, Multivariate                                                                                                                        |
| **Dataset Origin**       | Both datasets are derived from various real-world sources, including retail sales, economic indicators, and financial data.                        |
| **Prediction Task**      | Predict future values based on historical monthly data, focusing on accuracy and model performance.                                                  |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `target`: Rate conversion between the currencies.                                                                                                   |
|                          | 2. `Group_idx`: Time series index                                                                                                   |
|                          | 3. `Time_idx`: Timestamp index                                                                                                 |


#### SAGRA

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Set of Meteorological Stations in Alentejo Areas                                                                                                   |
| **Number of Instances**  | 3,679                                                                                                                                              |
| **Number of Features**   | 15                                                                                                                                                  |
| **Temporal Frequency**   | Daily                                                                                                                                               |
| **Period**               | 2012-01-01 to 2022-09-08                                                                                                                           |
| **Feature Types**        | Real, Categorical, Time Series                                                                                                                     |
| **Associated Tasks**     | Forecasting, Time Series Analysis                                                                                                                  |
| **Subject Area**         | Meteorology, Environmental Science                                                                                                                  |
| **Has Missing Values?**  | Yes, there may be gaps in some series.                                                                                                            |
| **Dataset Characteristics** | Time Series, Multivariate                                                                                                                        |
| **Dataset Origin**       | Datasets are derived from the [SAGRA](https://www.cotr.pt/servicos/sagra.php) system.                                                            |
| **Prediction Task**      | Predict reference evapotranspiration for at least three days ahead.                                                                               |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `date`: (time) Date of the recorded observation                                                                                                   |
|                          | 2. `tmed`: (real) Daily average temperature                                                                                                          |
|                          | 3. `tmax`: (real) Maximum daily temperature                                                                                                          |
|                          | 4. `tmin`: (real) Minimum daily temperature                                                                                                          |
|                          | 5. `hrmed`: (real) Daily average relative humidity                                                                                                   |
|                          | 6. `hrmax`: (real) Maximum daily relative humidity                                                                                                   |
|                          | 7. `hrmin`: (real) Minimum daily relative humidity                                                                                                   |
|                          | 8. `rsg`: (real) Daily solar radiation received                                                                                                      |
|                          | 9. `dv`: (real) Daily vapor pressure                                                                                                                |
|                          | 10. `vvmed`: (real) Daily average wind speed                                                                                                        |
|                          | 11. `vvmax`: (real) Maximum daily wind speed                                                                                                        |
|                          | 12. `p`: (real) Daily total precipitation                                                                                                           |
|                          | 13. `tmed_relva`: (real) Average temperature at grass level                                                                                         |
|                          | 14. `tmax_relva`: (real) Maximum temperature at grass level                                                                                         |
|                          | 15. `tmin_relva`: (real) Minimum temperature at grass level                                                                                         |
|                          | 16. `et0`: (real) Target variable for reference evapotranspiration                                                                           |


#### Pollution

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Set of Meteorological Stations in Andalusia's Zones                                                                                               |
| **Number of Instances**  | 166,546                                                                                                                                           |
| **Number of Features**   | May vary on the dataset, typically 10.                                                                                                           |
| **Temporal Frequency**   | Hourly                                                                                                                                             |
| **Period**               | 2005-01-01 to 2023-12-31                                                                                                                           |
| **Feature Types**        | Real, Categorical, Time Series                                                                                                                     |
| **Associated Tasks**     | Forecasting, Time Series Analysis                                                                                                                  |
| **Subject Area**         | Meteorology, Environmental Science                                                                                                                  |
| **Has Missing Values?**  | Yes, there may be gaps in some series.                                                                                                            |
| **Dataset Characteristics** | Time Series, Multivariate                                                                                                                        |
| **Dataset Origin**       | Datasets are derived from the [RIA](https://www.juntadeandalucia.es/agriculturaypesca/ifapa/riaweb/web/).                                       |
| **Prediction Task**      | Predict some pollutant based on exogenous variables.                                                                                               |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `datetime`: (time) Timestamp indicating the date and time of the recorded observation                                                           |
|                          | 2. `dd`: (real) Wind direction in degrees                                                                                                          |
|                          | 3. `no2`: (real) Concentration of nitrogen dioxide (NO2) in the air                                                                                |
|                          | 4. `o3`: (real) Concentration of ozone (O3) in the air                                                                                            |
|                          | 5. `pm10`: (real) Concentration of particulate matter (PM10) in the air                                                                          |
|                          | 6. `tmp`: (real) Averaged air temperature at the time of observation                                                                                       |


#### Traffic

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Traffic Volume Dataset for Time Series Forecasting                                                                                                |
| **Number of Instances**  | 862 time series with 17,543 instances each.                                                                                       |
| **Number of Features**   | 1.                                                                            |
| **Temporal Frequency**   | Hourly                                                                                                                    |
| **Period**               | Undefined.                                                                              |
| **Feature Types**        | Real, Categorical, Time Series                                                                                                                     |
| **Associated Tasks**     | Forecasting, Time Series Analysis                                                                                                                  |
| **Subject Area**         | Transportation, Urban Studies                                                                                                                      |
| **Has Missing Values?**  | No.                                                  |
| **Dataset Characteristics** | Time Series, Multivariate                                                                                                                        |
| **Dataset Origin**       | Datasets are collected from various traffic sensors and cameras in urban areas, often provided by local government or transportation agencies.    |
| **Prediction Task**      | Predict future traffic volume based on historical data and other exogenous variables.                                                              |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `target`: Traffic flow.                                                                                                   |
|                          | 2. `Group_idx`: Time series index                                                                                                   |
|                          | 3. `Time_idx`: Timestamp index                                                                                                 |


#### Traffic perms bay

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Traffic Volume Dataset for Time Series Forecasting                                                                                                |
| **Number of Instances**  | 325 time series with 52,116 instances each.                                                                                       |
| **Number of Features**   | 1.                                                                            |
| **Temporal Frequency**   | Hourly                                                                                                                    |
| **Period**               | Undefined.                                                                              |
| **Feature Types**        | Real, Categorical, Time Series                                                                                                                     |
| **Associated Tasks**     | Forecasting, Time Series Analysis                                                                                                                  |
| **Subject Area**         | Transportation, Urban Studies                                                                                                                      |
| **Has Missing Values?**  | No.                                                  |
| **Dataset Characteristics** | Time Series, Multivariate                                                                                                                        |
| **Dataset Origin**       | Collected from traffic sensors installed in the Bay Area, with data provided by local transportation authorities.    |
| **Prediction Task**      | Predict future traffic volume based on historical data and other exogenous variables.                                                              |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `target`: Traffic flow.                                                                                                   |
|                          | 2. `Group_idx`: Time series index                                                                                                   |
|                          | 3. `Time_idx`: Timestamp index                                                                                                 |


#### Traffic metr la

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Traffic Volume Dataset for Time Series Forecasting                                                                                                |
| **Number of Instances**  | 207 time series with 34,272 instances each.                                                                                       |
| **Number of Features**   | 1.                                                                            |
| **Temporal Frequency**   | Hourly                                                                                                                    |
| **Period**               | Undefined.                                                                              |
| **Feature Types**        | Real, Categorical, Time Series                                                                                                                     |
| **Associated Tasks**     | Forecasting, Time Series Analysis                                                                                                                  |
| **Subject Area**         | Transportation, Urban Studies                                                                                                                      |
| **Has Missing Values?**  | No.                                                  |
| **Dataset Characteristics** | Time Series, Multivariate                                                                                                                        |
| **Dataset Origin**       | Collected from traffic sensors installed across the Los Angeles area, with data provided by the Los Angeles Department of Transportation.    |
| **Prediction Task**      | Predict future traffic volume based on historical data and other exogenous variables.                                                              |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `target`: Traffic flow.                                                                                                   |
|                          | 2. `Group_idx`: Time series index                                                                                                   |
|                          | 3. `Time_idx`: Timestamp index                                                                                                 |

#### Wiki web traffic


| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Wikipedia Web Traffic Dataset for Time Series Analysis                                                                                            |
| **Number of Instances**  | 996 time series with 608 instances each                                                                                                                 |
| **Number of Features**   | Typically around 5 to 10 features, depending on the specific dataset version.                                                                     |
| **Temporal Frequency**   | Daily                                                                                                                                               |
| **Period**               | Covers the period from 2015-01-01 to 2022-12-31                                                                                                   |
| **Feature Types**        | Real, Categorical, Time Series                                                                                                                     |
| **Associated Tasks**     | Forecasting, Time Series Analysis                                                                                                                  |
| **Subject Area**         | Web Analytics, Internet Traffic                                                                                                                   |
| **Has Missing Values?**  | No.                                                    |
| **Dataset Characteristics** | Time Series, Multivariate                                                                                                                        |
| **Dataset Origin**       | Data collected from the Wikipedia pageview API.                                      |
| **Prediction Task**      | Predict future pageviews for Wikipedia articles based on historical traffic data over different pages.                                             |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `target`: Traffic flow.                                                                                                   |
|                          | 2. `Group_idx`: Time series index                                                                                                   |
|                          | 3. `Time_idx`: Timestamp index                                                                                                 |
