# Seattle Weather | Data 3320, Spring 2023
Uses data science methodology to determine whether it rains more in Seattle, WA than in St. Louis, MO.

## Data
Precipitation measured daily in Seattle and St. Louis from January 1, 2017 to December 31, 2022. The data sets [`seattle_rain.csv`](https://github.com/lbomine/Seattle-Weather/blob/75fdb7a94f59254160ca0f527539d6acaa3f9049/seattle_rain.csv) and [`stl_rain.csv`](https://github.com/lbomine/Seattle-Weather/blob/75fdb7a94f59254160ca0f527539d6acaa3f9049/stl_rain.csv) were downloaded from the National Centers for Environmental Information NOAA Climate Data Online [search tool](https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND).

## Data Preparation
Used Google Colab [Notebook](https://github.com/lbomine/Seattle-Weather/blob/12bc68869b880534f0341b3a19e2a0e7f997fab2/Leiana%20Omine%20-%20DATA%203320%20Seattle%20St.%20Louis%20Data%20Preparation.ipynb) to import the data sets and prepare the data.
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
