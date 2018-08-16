# Analysis 

### 1. Visualization & Analysis of weather of 800+ cities across the world was done on various factors like Temperature, Humidity, Cloudiness and Wind-speed with respect to the distance from the equator.

### 2. The main objective was to showcase the relationship between the aforesaid factors.

### 3. For this analysis, approx. 2000 coordinate pairs of Latitude and Longitude were randomly generated. Citypy, a python library was used to generate city names for respective coordinates. 

### 4. A weather-check was performed on each of the cities using a series of successive API calls from OpenWeatherMap, after selecting unique non-repeat observations. Point of interests were plotted against latitude using Matplotlib and Seaborn libraries.

# Conclusion

### 1. 'Equatorial Climate' is a type of Tropical Climate in which there is no dry season. 
### 2. They receive abundant rainfall. 
### 3. It is usually found at the Latitudes within five degrees of the Equator.
### 4. The natural vegetation of this region is 'Tropical Rainforest'.

# Further Details of the project are as follows:-

 Web Visualization Dashboard (Lattitude)

## Background

### HTML and CSS were used to create a visualization dashboard.
### Analysis was done.

Individual pages (total 7) for each plot and a means by which we can navigate between them. These pages contain the visualizations and their corresponding explanations. 

## The website's  7 pages include:

## * A landing page index.html containing:
  * An explanation of the project.
  * Links to each visualizations page.

## * Four Visualization pages were created each with:
###   * A descriptive title and heading tag.
###   * The plot/visualization itself for the selected comparison.
###   * A paragraph describing the plot and its significance.
  They are:-
###   1. cloudliness.html
###   2. humidity.html
###   3. maxtemp.html
###   4. windspeed.html

## * A Comparisons page :
###   * Contains all of the visualizations on the same page so we can easily visually compare them.
###   * Uses a bootstrap grid for the visualizations.
###   * The grid was visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

## * A Data page :
###    * It  Displays a responsive table containing the data used in the visualizations.
###    * The is a bootstrap table component.
###    * The data comes from exporting the `.csv` file as HTML, or converting it to HTML using csv-to-html table conversion tool, e.g. [ConvertCSV](http://www.convertcsv.com/csv-to-html.htm).

## Nvigation Menu:

### * Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
### * Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
### * Provides links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
### * It was made responsive (using media queries). The Navigation Menu has similar behavior.

## Factors Considered:

### * 1. Data from [HW06](../../HW06-WebAPIs) was considered.
### * 2. Cities dataset i.e. from cities.csv was used.
### * 3. CSS media query was used for the navigation menu and the rest of the body of the pages.
### * 4. using bootstrap Website was made to work at all window widths/sizes including mobile screen size, `navbar` component for the header on every page, the bootstrap table component for the data page, and the bootstrap grid for responsiveness on the comparison page.

# Finally, the website was deployed to github pages.