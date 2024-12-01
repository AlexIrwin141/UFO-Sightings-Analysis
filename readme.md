UFO Sighting Data Analysis

This project explores UFO sightings data to try and uncover patterns and insights using Python. The analysis focuses on various aspects, including geographical distribution, trends over time, and relationships between sighting attributes (shape).

The primary focus includes:

Proportions of sightings by time of day and country.
Trends in the shapes of UFOs reported over the years.
Geographical distribution by latitude and longitude.

The analysis is presented as a Jupyter Notebook with various data visualization techniques to present the results.

Features
Stacked bar charts to visualize sightings by time of day for selected countries.
Line plots to explore proportions of UFO shapes over time.
Analysis of geographical trends, including hemispherical breakdowns.

Data Source
This data was obtained from Kaggle (https://www.kaggle.com/code/hakeemtfrank/ufo-sightings-data-exploration/input) which was in turn obtained from NUFORC. It runs up until September 2013.

The data includes records of UFO sightings worldwide, with the following columns:

datetime
city
state
country
shape
duration (seconds)
duration (hours/min)
comments
date_posted
latitude
longitude

I will not be using all of this information so there will be a fair amount of cleaning up.

Note: The dataset is not uploaded here due to file size limitations. You can download it directly using the link above to reproduce the analysis.

Usage
Clone this repository:

git clone https://github.com/your-username/ufo-sighting-analysis.git
Install the required Python libraries:

pip install -r requirements.txt

Download the dataset from the source link and place it in the appropriate folder.

Open the Jupyter Notebook:

jupyter notebook UFO_Watch.ipynb
Run the cells to explore the analysis and visualizations.
Libraries Used:

pandas: For data manipulation and cleaning.
matplotlib: For creating static plots and visualizations.
seaborn: For statistical data visualization.
geopandas: For geospatial data analysis and mapping.
numpy: For numerical computations.

Acknowledgments
Data Source:
UFO sightings dataset was accessed from https://www.kaggle.com/code/hakeemtfrank/ufo-sightings-data-exploration/input.

General UFO sighting research from NUFORC. Also thanks to The Vancouver Sun https://ufobc.ca/Reports/banneryear.htm and UPI https://www.upi.com/Top_News/2008/08/09/UFO-sightings-at-peak-in-Britain/21751218298699/ for some insights.

