# udacity-dsnd-project1
Udacity DataScience Nanodegree Project 1 - AirBnB Data Exploration

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Data Descriptions](#data)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code was developed and tested using Python 3.6.7, and pandas version 0.25.0, with the standard Anaconda install and the package `basemap` for visualizing results in map-view.
Basemap installations were run using conda as follows:
    
    1) `conda install basemap`
    2) `conda install -c conda-forge basemap-data-hires`
    
Pandas upgrade to 0.25.0 was installed with pip3 as follows:
    
    3) `pip install pandas==0.25.0`
    
The code should run with no issues using Python versions 3.6 + and pandas version 0.25.0+

## Project Motivation<a name="motivation"></a>

For this project, I was interested in using Seattle AirBnB data to better understand:

    1) Are hippies really dirty: do the hippy neighborhoods in Seattle have lower AirBnB cleanliness ratings?
    2) Are communal AirBnB listings more common in hippy neighborhoods: Which neighborhoods have the highest proportion of shared-living listings?
    3) Which factors contribute most to the cleanliness rating?

## Data Descriptions <a name="data"></a>

The full set of files related to this course are stored on kaggle at the following link: https://www.kaggle.com/airbnb/seattle/data, originally obtained from http://insideairbnb.com/get-the-data.html.

The following Airbnb activity is included in this Seattle dataset:

  1) `listings.csv`: full descriptions of listings and average review score
  2) `reviews.csv`: unique id for each reviewer and detailed comments
  3) `calendar.csv`: listing id and the price and availability for that day
  
  For this analysis, I only used the `listings.csv` file.

## File Descriptions <a name="files"></a>

There is 1 Jupyter notebook in this repository to showcase work related to the above questions.  Each of the notebooks is exploratory in nature, and include markdown cells to explain and describe the exploration process.  

The notebooks that are related to the analysis presented in the medium blog (see below) are located here:

    1) airbnb/ipynb/seattle_airbnb_neighborhood_exploration.ipynb

The other notebooks in the scratch_ipynb folder include additional related exploratory analaysis that preceded the two notebooks listed, and include some potentially useful information, but are outside the scope of this project.

## Results<a name="results"></a>

The main findings of the code can be found at the post available here: [whered-the-hippies-go](https://medium.com/@bridgethass/whered-the-hippies-go-aee4b0876dc7).

## Licensing, Authors, Acknowledgments <a name="licensing"></a>

Data is provided by [insideairbnb](http://insideairbnb.com/get-the-data.html) and hosted on [kaggle](https://www.kaggle.com/airbnb/seattle/data), which also includes the licensing information. The code here is licensed under open source GNU General Public License v3.0, and is free to use as you wish, with no guarantees :)
