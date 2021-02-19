### **Analysis of Christie Neighborhood Vs "Richmond, Adelaide, King" Neighborhood In Toronto**

**_PROBLEM_**

How can we find the best neighborhood in Toronto based on a given set of criteria? This project aims to provide a recommendation on the best neighborhood that satisfies some given criteria based on the distance from one location to another and ratings (between 0 to 10) for a particular given location (venue).

**_ANALYSIS_**

The analysis is based on the “Category” column because it contains the requirements a potential user would specify. For this analysis, two categorical values were used; “Restaurant” and “Gym.” Using these two categories would give an insight into the best gym or restaurant that are around the neighborhoods of interest. The figure below is a snapshot of what a typical data frame would look like.

![DATAFRAME](https://user-images.githubusercontent.com/36754815/108545632-0812db80-72b6-11eb-8ff0-d6a631d901af.PNG)

**_GOAL_**

To calculate the rantings (scale of 0 - 10) and the distance of each venue (either restaurant or the gym) from the location of interest within a neighborhood.

**_RESULTS_**

![RESULT TABLE](https://user-images.githubusercontent.com/36754815/108546095-a56e0f80-72b6-11eb-84be-b31dff16103f.PNG)

1. Result Obtained From The "Christie" Neighborhood

![Christie](https://user-images.githubusercontent.com/36754815/108545018-3c39cc80-72b5-11eb-85e1-cd4d55e4c377.PNG)

2. Resule Obtained From The "Richmond, Adelaide, King" Neighborhood

![RAK](https://user-images.githubusercontent.com/36754815/108545104-58d60480-72b5-11eb-9dde-54757a7d37ea.PNG)

**_OBSERVATION_**

         Based on the plots provided above, it was observed that no result for the “Gym” category was found for the neighborhood of Christie, and 3 results were found for the “Restaurant” category. However, a total of 8 results was obtained for the “Adelaide, Richmond, King” neighborhood” with an even split between the “Gym” and “Restaurant” category. The number of results obtained from both neighborhoods could be a potential deciding factor as the “Christie” neighborhood offers fewer options based on the number of restaurant and gym venues available.

        Further, the bar plots are displayed in order of increasing distance from the starting location and average rating. For the “Christie” location the best restaurant around is “Rasa” with an 8.9 rating, and it is also the farthest away from the starting location with 1.5 km. Conversely, the closest restaurant is “Actinolite” with a shorter distance of 609 meters, but with a less impressive rating of 7.6. However, for the “Adelaide, Richmond, and King” location with a handful of results for both the “Gym” and “Restaurant” category, this location is worth looking into. The best “Restaurant” around is “The Keg Steakhouse + Bar” with a rating of 8.8 and 78 meters from the starting location. The best “Gym” around is called “Equinox” with a rating of 8.4 and 315 meters away from the location of origin. These two locations are considered the best for this neighborhood because they have the highest rating and the closest distances in their respective categories.

**_CONCLUSIONS_**

In this study, I analyzed the search results on two neighborhoods; “Christie” and “Adelaide, Richmond, and King” based on the “Gym” and “Restaurant” categories. I calculated the individual distances between each result from the location the search was made and calculated the average rating for every location (venue) returned. A cluster of the results around each neighborhood was built based on proximity, and bar plots were generated in order of increasing distance and ratings. It was observed that “Adelaide, Richmond, and King” neighborhood had the best results both under the “Gym” and “Restaurant” category. It was also noted that all the restaurants result for “Adelaide, Richmond, and King” are within a radius of 500 meters which is closer in distance than the best restaurant in “Christie” neighborhood with a distance of 610 meters. Below is a summary of the results from both locations. Based on the analysis and observation made, I conclude that “Adelaide, Richmond, and King” is a better neighborhood for someone looking to relocate to a new location with interests in good gyms and restaurant locations.


