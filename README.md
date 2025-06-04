BACKEND
Develop API services capable of retrieving weather forecasts for a specific location. The application should:
1.
2.
3.
4.
5.
Accept a zip code from users as input.
Provide the current temperature at the requested location as its primary output.
Offer additional details, such as the highest and lowest temperatures, and an extended forecast, as bonus features.
Implement caching to store forecast details for a duration of 15 minutes for subsequent requests using the same zip code.
Display an indicator to notify users if the result is retrieved from the cache.
The latitude and longitude for a zip code can be fetched using the geocoding API service provided by
https://nominatim.org/release-docs/develop/api/Search/. Then, lookup weather for latitude and longitude using https://open-
meteo.com/en/docs. Both these services are open-source and do not require an API key. As always, be mindful of the number
and frequency of requests you are making to these services.
You should adhere to the Spring/Spring Boot patterns you are familiar with, including the utilization of Controllers, Models,
Services, and Repositories.
