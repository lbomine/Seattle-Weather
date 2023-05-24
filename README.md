# Seattle Weather • Data 3320, Spring 2023
Uses data science methodology to determine whether it rains more in Seattle, WA than in St. Louis, MO.

## Requirements
To complete this project, Google Colaboratory is used as the main software. This is a web-based IDE for Python (programming language). Python libraries are also utilized to help clean and plot the data. GitHub is used to store the files of this project and make it easily accessible for reference when working with the data.

## Data
Precipitation measured daily in Seattle and St. Louis from January 1, 2017 to December 31, 2022. The data sets [`seattle_rain.csv`](https://github.com/lbomine/Seattle-Weather/blob/main/seattle_rain.csv) and [`stl_rain.csv`](https://github.com/lbomine/Seattle-Weather/blob/main/stl_rain.csv) were downloaded from the National Centers for Environmental Information NOAA Climate Data Online [search tool](https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND).

## Data Preparation
Used this [Data Preparation Notebook](https://github.com/lbomine/Seattle-Weather/blob/baa2ed9345a54c1d58e15cec5f93c4fe488f9b2a/Seattle_St.%20Louis_Data_Preparation.ipynb) to import the data sets and prepare the data.
<br> <br> Steps Taken:
- Inspected the contents of each data set.
- Converted data types of columns of the data frames to the correct types.
- Removed unnecessary parts of the data sets.
- Identified missing values in the data sets. Imputed or removed NaN values.
- Joined the Seattle and St. Louis data frames, keeping only the date and precipitation values.
- Ensured that the data frame is in a tidy, or long, format.
- Renamed the columns to follow best practices of being lowercase, snake_case, and understandable.
- Created derived variables that will be useful in the analysis.
- Exported the [clean data set](https://github.com/lbomine/Seattle-Weather/blob/baa2ed9345a54c1d58e15cec5f93c4fe488f9b2a/clean_seattle_stl_weather.csv).

## Data Analysis
Used this [Analyis Notebook](https://github.com/lbomine/Seattle-Weather/blob/65e9fef5ac96625d67d0f46c32413ba224628f1c/Seattle%20St.%20Louis%20Complete%20Analysis%20Leiana%20Omine.ipynb) to analyze the cleaned data set and produce all necessary results for the final conclusion. Additional questions were proposed to assist our understanding and interpretation of the data.
<br> <br> Questions:
1. Did the mean precipitation in Seattle and St. Louis change over the years? If so, how did it change and do they differ from eachother?
2. How many days of rain does Seattle have in comparison to St. Louis? Which city has more days of rain?

Through my analysis, I found that St. Louis had more precipitation than Seattle. However, Seattle had more days of rain. A more in depth visualization of this conclusion can be viewed in the [Communicating Results](https://github.com/lbomine/Seattle-Weather/blob/b9a68dc37bd2b431ef043f489e5314749121b245/Seattle%20St.%20Louis%20Communicating%20Results%20Leiana%20Omine.pdf) report.

## Author
Leiana Beatriz Omine - Student at Seattle University

## License
Materials in this repository may be reused but not modified.
