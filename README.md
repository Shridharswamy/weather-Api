# weather-Api

Building a Backend API for Weather Forecast using Python as the Programming language and Flask as the framework and testing the api with postman

For execution of script follow these steps


#step1
run this script in the vs code make sure you have installed python on your device and also make sure the required libraries are installed like flask,requests


#step2
after hitting the run button in the terminal you will see the base url like http://127.0.0.1:5000 just open this in your browser.
by default this link is selected when you open this link you will see 404 error to fetch the weather you have to append this base url with api endpoint
/weather?location=city name #replace the city name with the name of the city of which you have to get the weather data
add this above url with city name to base url and then you will get the weather data ex:-http://127.0.0.1:5000/weather?location=Bidar
Thats it now you can see the json file NOTE:-make sure your script is running parallely in vs code

![p1](https://github.com/Shridharswamy/weather-Api/assets/150256209/9ba9e219-fb9a-475e-8b79-16c2d07d3a21)

First pic shows to open the base url displayed in the terminal after running the script in vs code

![p2](https://github.com/Shridharswamy/weather-Api/assets/150256209/873c9d76-6fd3-4fe2-84af-84d9edab83f4)


OUTPUT
![p3](https://github.com/Shridharswamy/weather-Api/assets/150256209/15aaf1fc-fc1c-400e-8b0a-bbb2a35a2bc3)


after following all the steps you will get the result in json file you can also change the city name and try with other locations
after getting the output copy that url in your browser and test the api with postman

![p4](https://github.com/Shridharswamy/weather-Api/assets/150256209/d5b35227-8ddb-41c5-b0af-42f04acb7df5)
