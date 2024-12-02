# data-sourcing-challenge
This repo analyzes NASA datasets to predict Geomagnetic Storms (GSTs) based off of data of Coronal Mass Ejections (CMEs), defined as massive bursts of plasma originating from the sun. We'll make a GET request to the NASA API to return GST and CME data. We take the data and convert it to a JSON format. We can print the JSON results to check that the data is properly formatted. From there, we create a Pandas DataFrame and use various methods to clean up the data and eventually merge two DataFrames. 

<b>Sources</b></br>
Module-06-Sourcing-AI-Project-Data/Class-3/Activities/01-Evr_API_Warm_Up/Unsolved/nasa_CMEs.ipynb</br>
Module-06-Sourcing-AI-Project-Data/Class-2/Activities/07-Ins_OpenWeatherDataFrame/Unsolved/open_weather_dataframe.ipynb</br>
Module-06-Sourcing-AI-Project-Data/Class-2/Activities/04-Stu_Under_Lock_And_Key/Unsolved/env_variables_nasa_requests.ipynb</br>
Module-06-Sourcing-AI-Project-Data/Class-2/Activities/09-Ins_ExceptionHandling/Unsolved/exception_handling.ipynb</br>
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.merge.html: left_on and right_on for merge</br>
Xpert Learning Assistant: axis=1 to apply fn to every row in a column. Definition of Series. Further help with astype method arguments</br>