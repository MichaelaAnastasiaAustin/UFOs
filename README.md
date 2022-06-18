# UFOs

## Background

The basis of this assignment was to create a dynamic webpage-- a webpage that accepts user inputs and adjusts accordingly-- to display UFO sighting data. Our initial task was to create an HTML page with an attention grabbing header, article summary and brief article, as well a table to hold and neatly display the date. We also created a filter table button that allowed us to filter the table by a user-specified date. (See image below).

![webpage](https://github.com/MichaelaAnastasiaAustin/UFOs/blob/main/static/images/webpage_img.png)

## Overview

In order to create a more in-depth analysis of UFO sightings, we have been tasked with updating the webpage so that users can filter for multiple criteria at the same time. In particular, we were asked to add the following table filters: city, state, country, and shape.

## Resources

- Data source: [data.js](https://github.com/MichaelaAnastasiaAustin/UFOs/blob/main/static/js/data.js) 

- Software: HTML, Bootstrap, CSS, Visual Studio Code

## Results
We successfully modified our code so that the webpage displays and filters by five search criterion: date, city, state, country, and shape. (See image below).

![allfilters[(https://github.com/MichaelaAnastasiaAustin/UFOs/blob/main/static/images/all-filters.png)

In order to access the data, a user can enter their search criterion in one, or all of the search boxes. For example, if a user was interested in searching for UFO sighting in the city "Fresno", they would enter "Fresno" into the city search box, and press enter. Then, the webpage would automatically update to filter for results that include the city name "Fresno". (See image below).

![fresno](https://github.com/MichaelaAnastasiaAustin/UFOs/blob/main/static/images/fresno-filter.png)

Similarly, if a user would like to search for UFO sightings with multiple criterion, they would follow the same process. For example, if someone was interested in UFO sightings in California with a triangle shape, they would enter "ca" into the "Enter State" filter and "triangle" into the "Enter Shape" filter, and press enter. The webpage would update to show only UFO sightings that were in California AND triangle-shaped. (See image below).

![tri-ca](https://github.com/MichaelaAnastasiaAustin/UFOs/blob/main/static/images/triangle-ca-filters.png)


## Summary

### Drawbacks of Webpage
One drawback of the table is that the data filter forces users to enter a date in xx/xx/xxxx format. This prevents users from doing a more general date search, such as by year "2010". By limiting the date filter to a specific date, this search criteria might be tedious for users.

### Recommendations
To further the development of this webpage, please review the following recommendations: 
1. Add a sixth table filter: Comments. This filter would allow users to search by specific observations or details such as "New Years Eve" or "orange" or "fireworks". By adding a "Comments" filter, users would have the ability to creatively search for UFO sightings based on their personal interests.

2. Clean up the data. There are inconsistencies throughout the data, which is not very visually appealing, and also might make it difficult for users to access the data they search for. For example, there are some city names with parentheses in them "London (Canada)", and neither city name nor state and country names are capitalized. The duration column has several variations in how time is measures "10:00" vs "noticed from dusk to dawn", and there are also spelling mistakes throughout the table. To make the table more professional, the data should be edited and revised.


