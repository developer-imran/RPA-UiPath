# RPA-UiPath

Weather API-jSON 

=> Do follow below 2 steps before running the process.

1) Sign-up into openweathermap.org to get apiKey.
2) Login and Generate API Key, Copy and paste in apiKey variable default value in the process.

=> Next Run the process

3) Process will try to get the city names from city_list excel file and for every city name loop will run.
4) HTTP_GET request will going to hit, with the combination of URL +  city name + API key.
5) After Success Response it is going to get the temperature and humidity, and it will save into same row of city name, in the city_list excel file.
6) You can open city_list file in the project directory to check out temperature and humidity.

check out repository contents.

