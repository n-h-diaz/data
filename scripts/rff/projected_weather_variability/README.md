# Importing Forecasted Raster of RFF Weather Variability Data

This directory imports RFF's Forecasted rasters of weather variability data 
with 0.25 degree spatial resolution.

The script generates:
- WeatherVariability_Forecast.csv
- WeatherVariability_Forecast.tmcf
- places_forecast.csv
- places_forecast.tcmf

and it relies on these statistic variables:
- dcs:StandardDeviation_DailyPrecipitation
- dcs:Skewness_DailyPrecipitation
- dcs:Kurtosis_DailyPrecipitation
- dcs:StandardDeviation_DailyMinTemperature
- dcs:Skewness_DailyMinTemperature
- dcs:Kurtosis_DailyMinTemperature
- dcs:StandardDeviation_DailyMaxTemperature
- dcs:Skewness_DailyMaxTemperature
- dcs:Kurtosis_DailyMaxTemperature
- dcs:HeavyPrecipitationIndex
- dcs:ConsecutiveDryDays


## Generating Artifacts:

To generate `WeatherVariability_Forecast.tmcf` and `WeatherVariability_Forecast.csv`, run:

```bash
python preprocess_forecast.py
```