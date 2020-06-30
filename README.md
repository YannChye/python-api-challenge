# python-api-challenge

Completed python (week 6) homework for Monash University Data Analytics Boot Camp.

* Folder structure include -
	* **output_data** folder - contains outputs (csv file and png plots) from *WeatherPy*, needed for *VacationPy*
	* **WeatherPy** folder - contains Jupyter notebook for WeatherPy code and report
	* **VacationPy** folder - contains Jupyter notebook for VacationPy code

## WeatherPy
* Extracts weather data from >500 cities distributed across the globe, and plot weather data by latitude
* Requires API key from https://openweathermap.org
* Generated figures include scatter plots and linear regressions for the following weather data -
   1. Temperature
   2. Humidity
   3. Cloudiness
   4. Wind Speed

## VacationPy
* Uses the cities' weather data output from WeatherPy. Narrow down the perfect vacation spot based on certain weather condition, locate the closest hotel, and visualise in google maps.
* Requires API key from Google Maps Platform
* Generated interactive google map shows heatmap of city humidity, and the 6 hotels that fit the following criteria - 
	1. located within 5000m of cities with 
		1. a current temperature of between 70-80F
		2. a wind speed of less than 10mph
		3. a cloudiness level of 0%