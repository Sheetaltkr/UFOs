# UFOs

## Overview of Project:

### Purpose
- Create a webpage and dynamic table to display UFO sightings information and an article on town Mcminnville, Oregon using HTML and Javascript. The information consists of countries, cities, states, type of sighting
- Enable data manipulation on the webpage using data filters
- Add multiple filter criteria using city, state, country, and shape table filters.

### Background
Dana, a data journalist is given the opportunity to write about her hometown McMinnville Oregon. Mcminnville is famous for its sightings and even  has an annual gathering of UFO enthusiasts. For this assignment, Dana has access to a JavaScript file filled to the brim with sighting information like countries, cities , states, type of sighting. Her plan is to first use Javascript to display the data as a table. Javascript provides a way to manipulate the data by adding filters. Before posting the article online, Dana wants to put everything together in a tidy HTML page; Her article, the table of data to support her findings, and easy to use filters to fine tune the results.

## Results: 
#### Webpage UFO Sightings

![UFO Sightings](https://github.com/Sheetaltkr/UFOs/blob/main/static/images/ufo_main.png)

The website displays the article "UFO Sightings: Fact or Fancy?" which talks about UFO sightings and Aliens. The website also displays UFO sightings data in tabular form below the article. This data can be filtered using the criteria present on the left side of the table. The criteria includes:
- Date
- City
- State
- Country
- Shape

User needs to enter the filter criteria in the textboxes below the labels and press enter. If the sightings table has the data as per the filter, the corresponding data would be displayed in the table.
User can select multiple criteria at the same time.

The webpage results as per different criteria as shown below:

1) Date filter: "1/2/2010"

![UFO Sightings](https://github.com/Sheetaltkr/UFOs/blob/main/static/images/ufo_date.png)

3) City filter: "phoenix"

![UFO Sightings](https://github.com/Sheetaltkr/UFOs/blob/main/static/images/ufo_city.png)

5) State filter: "co"

![UFO Sightings](https://github.com/Sheetaltkr/UFOs/blob/main/static/images/ufo_state.png)

7) Country filter: "ca"

![UFO Sightings](https://github.com/Sheetaltkr/UFOs/blob/main/static/images/ufo_country.png)

9) Shape filter: "triangle"

![UFO Sightings](https://github.com/Sheetaltkr/UFOs/blob/main/static/images/ufo_shape.png)

## Summary:
**Drawback**

- The webpage is case-sensitive and does not return results if the filter criteria text case does not match to that of the data stored in data file.
- Date textbox does not have calendar popup to select dates. User needs to manually enter the date in specitic format.
- No click button present to indicate the action for applying the filter.

**Recommendations**
- Drop down lists could be added for filter textboxes
- The webpage filter mechanism should be case-insensitive
- There could be two date input boxes to select a range of dates 

