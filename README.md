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

    1) which variables are best predictors for the overall review score?
    2) do review scores vary significantly between different neighborhoods?
    3) which neighborhoods provide the best value (ratings/price ratio)?

## Data Descriptions <a name="data"></a>

The full set of files related to this course are stored on kaggle at the following link: https://www.kaggle.com/airbnb/seattle/data, originally obtained from http://insideairbnb.com/get-the-data.html.

The following Airbnb activity is included in this Seattle dataset:

  1) `listings.csv`: full descriptions of listings and average review score
  2) `reviews.csv`: unique id for each reviewer and detailed comments
  3) `calendar.csv`: listing id and the price and availability for that day

## File Descriptions <a name="files"></a>

There are __ Jupyter notebooks in this repository to showcase work related to the above questions.  Each of the notebooks is exploratory in nature, and include markdown cells to explain and describe the exploration process.  

There is an additional `.py` file that runs the necessary code to obtain the final model used to predict salary.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/...).

## Licensing, Authors, Acknowledgments <a name="licensing"></a>

Data is provided by http://insideairbnb.com/get-the-data.html and hosted on https://www.kaggle.com/airbnb/seattle/data, which also includes the licensing information. The code here is licensed under open source GNU ..., and is free to use as you would like! 
