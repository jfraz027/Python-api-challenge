# Python-api-challenge


## Part 1: WeatherPy

The goal is to create visualization for the weather of 500+ cities of varying distance from the equator. Utilize problem-solving skills to create a representative model of weather across cities. Primary tools - Python 

The first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude

![image](https://user-images.githubusercontent.com/99145651/165107717-844eea85-f1ab-430c-9bbf-32f32512beb2.png)


* Humidity (%) vs. Latitude

![image](https://user-images.githubusercontent.com/99145651/165107891-8c3f1eb3-8c2f-48e5-ad28-d619a9c9b6f1.png)


* Cloudiness (%) vs. Latitude

![image](https://user-images.githubusercontent.com/99145651/165108053-5c1c93b0-5e5f-4374-99be-b4b732037e8a.png)

* Wind Speed (mph) vs. Latitude

![image](https://user-images.githubusercontent.com/99145651/165108243-4af2474c-2ea2-44c7-8e44-419ff71a40fe.png)

Include a sentence of analytical explanation.

Compute the linear regression for each relationship separating the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
![image](https://user-images.githubusercontent.com/99145651/165125420-da414450-2d40-4836-b3c1-dcfcf07f9f6c.png)
![image](https://user-images.githubusercontent.com/99145651/165125534-0a91f798-29be-4150-a4bf-20eaac32cb0a.png)

* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
![image](https://user-images.githubusercontent.com/99145651/165125683-fc049a36-e3b1-4cde-852d-3a5ea17cfa49.png)
![image](https://user-images.githubusercontent.com/99145651/165125804-ee5dddfa-d7f5-4920-bf7a-f7d8084ba240.png)

* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
![image](https://user-images.githubusercontent.com/99145651/165125988-90a29a65-7c8a-488a-a852-276931a1cfd8.png)
![image](https://user-images.githubusercontent.com/99145651/165127710-7b8f9dd8-cc31-4997-bb11-f06bfa3840b1.png)

* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude
![image](https://user-images.githubusercontent.com/99145651/165127282-c89d6874-38f0-48f4-b113-b4aa4a036384.png)
![image](https://user-images.githubusercontent.com/99145651/165127346-345676c7-9964-4094-b2ee-531dad36aeee.png)

Inclusion of what the linear regression is modeling by describing relationships.

The analysis provides:

* 500 unique (non-repeated) cities based on latitude and longitude.
* Weather check on each of the cities using a series of successive API calls.
* Print log of each city as it's being processed, with the city number and city name.
* Save a CSV of all retrieved data and a PNG image for each scatter plot.

### Part 2: VacationPy

In addition, using Jupyter-gmaps and the Google Places, create a heat map that displays the humidity for every city from Part 1.
Using the following parameters:

  * A max temperature lower than 80 degrees but higher than 70.
  * Wind speed less than 10 mph.
  * Zero cloudiness.
  * Drop any rows that don't satisfy all three conditions. You want to be sure the weather is ideal.

![image](https://user-images.githubusercontent.com/99145651/165129012-6834b634-bb8b-4bf1-9518-2111d5caf5eb.png)


* Use Google Places API to find the first hotel for each city located within 5,000 meters of your coordinates.

* Plot the hotels on top of the humidity heatmap, with each pin containing the **Hotel Name**, **City**, and **Country**, as in the following image:

![image](https://user-images.githubusercontent.com/99145651/165129201-b62e42f9-93b5-4d30-a2a6-0a5963fc1049.png)

