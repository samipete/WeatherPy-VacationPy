# WeatherPy-VacationPy
![cities image](/output_data/cities_map.png)
This project utilizies the OpenWeatherMap & Geoapify APIs to visualize the weather of over 500 cities in the northern and sourthern hemispheres. 

This project is broken down into two parts:
    
    1.WeatherPy:
        - creates plots to show the relationship between weather variables and latitude.

        - computes and shows linear regression for each relationship and provides a discussion about the linear relatioship 

    2. VacationPy:
        - uses geoviews and the Geoapify API to create a map which displays a point for each city and indicates humditiy relative to the size of the point (shown in the first image)

        - creates a dataframe which finds ideal weather conditions for a potential vacationer: (max temperature lower than 30 degrees but higher than 18, wind speed less than 5 m/s, zero cloudiness)

        - finds the first hotel located within 10,000 metres 
        
        - adds the hotel name and the country as additional information in the hover message for each city in the map.
![hotels_image](/output_data/hotel%20hover%20message.png)