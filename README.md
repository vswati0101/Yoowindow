#### Weather App | Open Weather Api | Retrofit & Kotlin Coroutines | FusedLocation 


#### API Call is 5 Days/3 hours Forecast 

1. Search Weather By Current Location | FusedLocation 
2. Search Weather By City 
3. Get notification to bring umbrella if its raining 


###### For today's forecast I get the system's current date and filter out the objects that contain the weather of today and store them in a today's weather list 
###### If the timestamp in today's forecast list matches or is the nearest to curernt time then I display that weather object as current weather 

###### For upcoming forecast I add all those objects to a new list whose timestamp does not match with today's current date and also whose timestamp is 12:00 PM so I display the upcoming Mid-Day forecast of each day

###### Shared Preferences have played an important role where I store search query (city name) and when the app exits, shared preference gets cleared

##### Images

![Untitled design (1)](https://github.com/vswati0101/Yoowindow/assets/140166757/594907d8-b9e4-4173-970b-d94a9eeb4a11)

##### Note: insert your api key before running the app 

