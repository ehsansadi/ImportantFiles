
DATAPACKAGE: TIME SERIES
===========================================================================



by Open Power System Data: http://www.open-power-system-data.org/

Package Version: 2016-07-14

Load, wind and solar, prices in hourly resoltion

This data package contains different kinds of timeseries data relevant for
power system modelling, namely electricity consumption (load) for 36
European countries as well as wind and solar power generation and
capacities and prices for a growing subset of countries. The timeseries
become available at different points in time depending on the sources. The
full dataset is only available from 2012 onwards. The data has been
downloaded from the sources, resampled and merged in a large CSV file with
hourly resolution. Additionally, the data available at a higher resolution
(Some renewables in-feed, 15 minutes) is provided in a separate file. All
data processing is conducted in python and pandas and has been documented
in the Jupyter notebooks linked below.

The data package covers the geographical region of Europe.

We follow the Data Package standard by the Frictionless Data project, a
part of the Open Knowledge Foundation: http://frictionlessdata.io/


Documentation and script
===========================================================================

This README only contains the most basic information about the data package.
For the full documentation, please see the notebook script that was used to
generate the data package. You can find it at:

https://nbviewer.jupyter.org/github/Open-Power-System-Data/time_series/blob/2016-07-14/main.ipynb

Or on GitHub at:

https://github.com/Open-Power-System-Data/time_series/blob/2016-07-14/main.ipynb

License and attribution
===========================================================================

Data license: 
License Name Here

Script license:
    [MIT License](https://opensource.org/licenses/MIT)

Attribution:
    Attribution in Chicago author-date style should be given as follows:
    "Open Power System Data. 2016. Data Package Time series. Version
    2016-07-14.
    https://data.open-power-system-data.org/time_series/2016-07-14/.
    (Primary data from various sources, for a complete list see URL)."


Version history
===========================================================================

* 2016-07-14 Included data from Energinet.DK, Elia and Svenska Kraftnaet


Resources
===========================================================================

* [Package description page](http://data.open-power-system-data.org/time_series/2016-07-14/)
* [ZIP Package](http://data.open-power-system-data.org/time_series/opsd-time_series-2016-07-14.zip)
* [Script and documentation](https://github.com/Open-Power-System-Data/time_series/blob/2016-07-14/main.ipynb)
* [Original input data](http://data.open-power-system-data.org/time_series/2016-07-14/original_data/)


Sources
===========================================================================

* [TenneT](http://www.tennettso.de/site/en/Transparency/publications/network-figures/actual-and-forecast-wind-energy-feed-in)
* [ENTSO-E](https://www.entsoe.eu/data/data-portal/consumption/Pages/default.aspx)
* [Elia](http://www.elia.be/en/grid-data/power-generation/wind-power)
* [TransnetBW](https://www.transnetbw.com/en/key-figures/renewable-energies/photovoltaic)
* [Svenska Kraftnaet](http://www.svk.se/aktorsportalen/elmarknad/statistik/)
* [50Hertz](http://www.50hertz.com/en/Grid-Data/Photovoltaics/Archive-Photovoltaics)
* [own calculation](http://data.open-power-system-data.org/datapackage_timeseries)
* [Amprion](http://www.amprion.net/en/wind-feed-in)
* [50Hertz](http://www.50hertz.com/en/Grid-Data/Wind-power/Archive-Wind-power)
* [TenneT](http://www.tennettso.de/site/en/Transparency/publications/network-figures/actual-and-forecast-photovoltaic-energy-feed-in)
* [TransnetBW](https://www.transnetbw.com/en/key-figures/renewable-energies/wind-infeed)
* [Amprion](http://www.amprion.net/en/photovoltaic-infeed)
* [own calculation](http://data.open-power-system-data.org/datapackage_renewables/)


Field documentation
===========================================================================

timeseries60min.csv
---------------------------------------------------------------------------

* timestamp
    - Type: datetime
    - Format: YYYY-MM-DDThh:mm:ssZ
    - Description: Start of timeperiod in UTC
* load_AT_load
    - Type: number
    - Description: Consumption in Austria in MW
    - Source: 
* load_BA_load
    - Type: number
    - Description: Consumption in Bosnia and Herzegovina in MW
    - Source: 
* load_BE_load
    - Type: number
    - Description: Consumption in Belgium in MW
    - Source: 
* load_BG_load
    - Type: number
    - Description: Consumption in Bulgaria in MW
    - Source: 
* load_CH_load
    - Type: number
    - Description: Consumption in Switzerland in MW
    - Source: 
* load_CS_load
    - Type: number
    - Description: Consumption in Serbia and Montenegro in MW
    - Source: 
* load_CY_load
    - Type: number
    - Description: Consumption in Cyprus in MW
    - Source: 
* load_CZ_load
    - Type: number
    - Description: Consumption in Czech Republic in MW
    - Source: 
* load_DE_load
    - Type: number
    - Description: Consumption in Germany in MW
    - Source: 
* load_DK_load
    - Type: number
    - Description: Consumption in Denmark in MW
    - Source: 
* load_DKw_load
    - Type: number
    - Description: Consumption in DKw control area in MW
    - Source: 
* load_EE_load
    - Type: number
    - Description: Consumption in Estonia in MW
    - Source: 
* load_ES_load
    - Type: number
    - Description: Consumption in Spain in MW
    - Source: 
* load_FI_load
    - Type: number
    - Description: Consumption in Finland in MW
    - Source: 
* load_FR_load
    - Type: number
    - Description: Consumption in France in MW
    - Source: 
* load_GB_load
    - Type: number
    - Description: Consumption in United Kingdom in MW
    - Source: 
* load_GR_load
    - Type: number
    - Description: Consumption in Greece in MW
    - Source: 
* load_HR_load
    - Type: number
    - Description: Consumption in Croatia in MW
    - Source: 
* load_HU_load
    - Type: number
    - Description: Consumption in Hungary in MW
    - Source: 
* load_IE_load
    - Type: number
    - Description: Consumption in Ireland in MW
    - Source: 
* load_IS_load
    - Type: number
    - Description: Consumption in Iceland in MW
    - Source: 
* load_IT_load
    - Type: number
    - Description: Consumption in Italy in MW
    - Source: 
* load_LT_load
    - Type: number
    - Description: Consumption in Lithuania in MW
    - Source: 
* load_LU_load
    - Type: number
    - Description: Consumption in Luxembourg in MW
    - Source: 
* load_LV_load
    - Type: number
    - Description: Consumption in Latvia in MW
    - Source: 
* load_ME_load
    - Type: number
    - Description: Consumption in Montenegro in MW
    - Source: 
* load_MK_load
    - Type: number
    - Description: Consumption in Macedonia, Republic of in MW
    - Source: 
* load_NI_load
    - Type: number
    - Description: Consumption in Northern Ireland in MW
    - Source: 
* load_NL_load
    - Type: number
    - Description: Consumption in Netherlands in MW
    - Source: 
* load_NO_load
    - Type: number
    - Description: Consumption in Norway in MW
    - Source: 
* load_PL_load
    - Type: number
    - Description: Consumption in Poland in MW
    - Source: 
* load_PT_load
    - Type: number
    - Description: Consumption in Portugal in MW
    - Source: 
* load_RO_load
    - Type: number
    - Description: Consumption in Romania in MW
    - Source: 
* load_RS_load
    - Type: number
    - Description: Consumption in Serbia in MW
    - Source: 
* load_SE_load
    - Type: number
    - Description: Consumption in Sweden in MW
    - Source: 
* load_SI_load
    - Type: number
    - Description: Consumption in Slovenia in MW
    - Source: 
* load_SK_load
    - Type: number
    - Description: Consumption in Slovakia in MW
    - Source: 
* load_UAw_load
    - Type: number
    - Description: Consumption in UAw control area in MW
    - Source: 
* solar_DE_capacity
    - Type: number
    - Description: solar capacity in Germany in MW
    - Source: 
* solar_DE_forecast
    - Type: number
    - Description: solar day-ahead generation forecast in Germany in MW
    - Source: 
* solar_DE_generation
    - Type: number
    - Description: Actual solar generation in Germany in MW
    - Source: 
* solar_DE_profile
    - Type: number
    - Description: Share of solar capacity producing in Germany
    - Source: 
* solar_DE50hertz_forecast
    - Type: number
    - Description: solar day-ahead generation forecast in DE50hertz control area in MW
    - Source: 
* solar_DE50hertz_generation
    - Type: number
    - Description: Actual solar generation in DE50hertz control area in MW
    - Source: 
* solar_DEamprion_forecast
    - Type: number
    - Description: solar day-ahead generation forecast in DEamprion control area in MW
    - Source: 
* solar_DEamprion_generation
    - Type: number
    - Description: Actual solar generation in DEamprion control area in MW
    - Source: 
* solar_DEtennet_forecast
    - Type: number
    - Description: solar day-ahead generation forecast in DEtennet control area in MW
    - Source: 
* solar_DEtennet_generation
    - Type: number
    - Description: Actual solar generation in DEtennet control area in MW
    - Source: 
* solar_DEtransnetbw_forecast
    - Type: number
    - Description: solar day-ahead generation forecast in DEtransnetbw control area in MW
    - Source: 
* solar_DEtransnetbw_generation
    - Type: number
    - Description: Actual solar generation in DEtransnetbw control area in MW
    - Source: 
* solar_SE_generation
    - Type: number
    - Description: Actual solar generation in Sweden in MW
    - Source: 
* wind_BE_capacity
    - Type: number
    - Description: wind capacity in Belgium in MW
    - Source: 
* wind_BE_forecast
    - Type: number
    - Description: wind day-ahead generation forecast in Belgium in MW
    - Source: 
* wind_BE_generation
    - Type: number
    - Description: Actual wind generation in Belgium in MW
    - Source: 
* wind_DE_capacity
    - Type: number
    - Description: wind capacity in Germany in MW
    - Source: 
* wind_DE_forecast
    - Type: number
    - Description: wind day-ahead generation forecast in Germany in MW
    - Source: 
* wind_DE_generation
    - Type: number
    - Description: Actual wind generation in Germany in MW
    - Source: 
* wind_DE_profile
    - Type: number
    - Description: Share of wind capacity producing in Germany
    - Source: 
* wind_DE50hertz_forecast
    - Type: number
    - Description: wind day-ahead generation forecast in DE50hertz control area in MW
    - Source: 
* wind_DE50hertz_generation
    - Type: number
    - Description: Actual wind generation in DE50hertz control area in MW
    - Source: 
* wind_DEamprion_forecast
    - Type: number
    - Description: wind day-ahead generation forecast in DEamprion control area in MW
    - Source: 
* wind_DEamprion_generation
    - Type: number
    - Description: Actual wind generation in DEamprion control area in MW
    - Source: 
* wind_DEtennet_forecast
    - Type: number
    - Description: wind day-ahead generation forecast in DEtennet control area in MW
    - Source: 
* wind_DEtennet_generation
    - Type: number
    - Description: Actual wind generation in DEtennet control area in MW
    - Source: 
* wind_DEtransnetbw_forecast
    - Type: number
    - Description: wind day-ahead generation forecast in DEtransnetbw control area in MW
    - Source: 
* wind_DEtransnetbw_generation
    - Type: number
    - Description: Actual wind generation in DEtransnetbw control area in MW
    - Source: 
* wind_SE_generation
    - Type: number
    - Description: Actual wind generation in Sweden in MW
    - Source: 
* wind-offshore_BE_capacity
    - Type: number
    - Description: wind-offshore capacity in Belgium in MW
    - Source: 
* wind-offshore_BE_forecast
    - Type: number
    - Description: wind-offshore day-ahead generation forecast in Belgium in MW
    - Source: 
* wind-offshore_BE_generation
    - Type: number
    - Description: Actual wind-offshore generation in Belgium in MW
    - Source: 


timeseries15min.csv
---------------------------------------------------------------------------

* timestamp
    - Type: datetime
    - Format: YYYY-MM-DDThh:mm:ssZ
    - Description: Start of timeperiod in UTC
* solar_DE_capacity
    - Type: number
    - Description: solar capacity in Germany in MW
    - Source: 
* solar_DE_forecast
    - Type: number
    - Description: solar day-ahead generation forecast in Germany in MW
    - Source: 
* solar_DE_generation
    - Type: number
    - Description: Actual solar generation in Germany in MW
    - Source: 
* solar_DE_profile
    - Type: number
    - Description: Share of solar capacity producing in Germany
    - Source: 
* solar_DE50hertz_forecast
    - Type: number
    - Description: solar day-ahead generation forecast in DE50hertz control area in MW
    - Source: 
* solar_DE50hertz_generation
    - Type: number
    - Description: Actual solar generation in DE50hertz control area in MW
    - Source: 
* solar_DEamprion_forecast
    - Type: number
    - Description: solar day-ahead generation forecast in DEamprion control area in MW
    - Source: 
* solar_DEamprion_generation
    - Type: number
    - Description: Actual solar generation in DEamprion control area in MW
    - Source: 
* solar_DEtennet_forecast
    - Type: number
    - Description: solar day-ahead generation forecast in DEtennet control area in MW
    - Source: 
* solar_DEtennet_generation
    - Type: number
    - Description: Actual solar generation in DEtennet control area in MW
    - Source: 
* solar_DEtransnetbw_forecast
    - Type: number
    - Description: solar day-ahead generation forecast in DEtransnetbw control area in MW
    - Source: 
* solar_DEtransnetbw_generation
    - Type: number
    - Description: Actual solar generation in DEtransnetbw control area in MW
    - Source: 
* wind_BE_capacity
    - Type: number
    - Description: wind capacity in Belgium in MW
    - Source: 
* wind_BE_forecast
    - Type: number
    - Description: wind day-ahead generation forecast in Belgium in MW
    - Source: 
* wind_BE_generation
    - Type: number
    - Description: Actual wind generation in Belgium in MW
    - Source: 
* wind_DE_capacity
    - Type: number
    - Description: wind capacity in Germany in MW
    - Source: 
* wind_DE_forecast
    - Type: number
    - Description: wind day-ahead generation forecast in Germany in MW
    - Source: 
* wind_DE_generation
    - Type: number
    - Description: Actual wind generation in Germany in MW
    - Source: 
* wind_DE_profile
    - Type: number
    - Description: Share of wind capacity producing in Germany
    - Source: 
* wind_DE50hertz_forecast
    - Type: number
    - Description: wind day-ahead generation forecast in DE50hertz control area in MW
    - Source: 
* wind_DE50hertz_generation
    - Type: number
    - Description: Actual wind generation in DE50hertz control area in MW
    - Source: 
* wind_DEamprion_forecast
    - Type: number
    - Description: wind day-ahead generation forecast in DEamprion control area in MW
    - Source: 
* wind_DEamprion_generation
    - Type: number
    - Description: Actual wind generation in DEamprion control area in MW
    - Source: 
* wind_DEtennet_forecast
    - Type: number
    - Description: wind day-ahead generation forecast in DEtennet control area in MW
    - Source: 
* wind_DEtennet_generation
    - Type: number
    - Description: Actual wind generation in DEtennet control area in MW
    - Source: 
* wind_DEtransnetbw_forecast
    - Type: number
    - Description: wind day-ahead generation forecast in DEtransnetbw control area in MW
    - Source: 
* wind_DEtransnetbw_generation
    - Type: number
    - Description: Actual wind generation in DEtransnetbw control area in MW
    - Source: 
* wind-offshore_BE_capacity
    - Type: number
    - Description: wind-offshore capacity in Belgium in MW
    - Source: 
* wind-offshore_BE_forecast
    - Type: number
    - Description: wind-offshore day-ahead generation forecast in Belgium in MW
    - Source: 
* wind-offshore_BE_generation
    - Type: number
    - Description: Actual wind-offshore generation in Belgium in MW
    - Source: 


Feedback
===========================================================================

Thank you for using data provided by Open Power System Data. If you have
any question or feedback, please do not hesitate to contact us.

For this data package, contact:

For general issues, find our team contact details on our website:
http://www.open-power-system-data.org














