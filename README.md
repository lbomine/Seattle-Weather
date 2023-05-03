# Seattle Weather • Data 3320, Spring 2023
Uses data science methodology to determine whether it rains more in Seattle, WA than in St. Louis, MO.

## Requirements
To complete this project, [Google Colaboratory](https://colab.research.google.com/) is used as the main software. This is a web-based IDE for Python (programming language). Python libraries are also utilized to help clean and plot the data. [GitHub](https://github.com/) is used to store the files of this project and make it easily accessible for reference when working with the data.

## Data
Precipitation measured daily in Seattle and St. Louis from January 1, 2017 to December 31, 2022. The data sets [`seattle_rain.csv`](https://github.com/lbomine/Seattle-Weather/blob/75fdb7a94f59254160ca0f527539d6acaa3f9049/seattle_rain.csv) and [`stl_rain.csv`](https://github.com/lbomine/Seattle-Weather/blob/75fdb7a94f59254160ca0f527539d6acaa3f9049/stl_rain.csv) were downloaded from the National Centers for Environmental Information NOAA Climate Data Online [search tool](https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND).

## Data Preparation
Used this [Data Preparation Notebook](https://github.com/lbomine/Seattle-Weather/blob/12bc68869b880534f0341b3a19e2a0e7f997fab2/Leiana%20Omine%20-%20DATA%203320%20Seattle%20St.%20Louis%20Data%20Preparation.ipynb) to import the data sets and prepare the data.
<br> <br> Steps Taken:
- Inspected the contents of each data set.
- Converted data types of columns of the data frames to the correct types.
- Removed unnecessary parts of the data sets.
- Identified missing values in the data sets. Imputed or removed NaN values.
- Joined the Seattle and St. Louis data frames, keeping only the date and precipitation values.
- Ensured that the data frame is in a tidy, or long, format.
- Renamed the columns to follow best practices of being lowercase, snake_case, and understandable.
- Created derived variables that will be useful in the analysis.
- Exported the [clean data set](https://github.com/lbomine/Seattle-Weather/blob/12bc68869b880534f0341b3a19e2a0e7f997fab2/clean_seattle_stl_weather.csv).

## Data Analysis
Used this [Analyis Notebook]() to analyze the cleaned data set and produce all necessary results for the final conclusion. Additional questions were proposed to assist our understanding and interpretation of the data.
<br> <br> Questions:
1. Did the mean precipitation in Seattle and St. Louis change over the years? If so, how did it change and do they differ from eachother?
2. How many days of rain does Seattle have in comparison to St. Louis? Which city has more days of rain?
3. What is the max precipitation for each month in Seattle and St. Louis? Which city has more precipitation?

<br> Through our data analysis, we find that St. Louis has more rain than Seattle. St. Louis has less rainy days but an even distribution of rain throughout the year. Seattle has a lower mean precipitation per year and overall a lower max precipitation in comparison to St. Louis. However, Seattle has a higher frequency of rainy days throughout the year. Thus, we conclude that Seattle rains more than St. Louis. A more in depth visualization of this conclusion can be viewed in [Communicating Results]().

## Author
Leiana Beatriz Omine - Student at Seattle University

## License
Materials in this repository may be reused but not modified.
