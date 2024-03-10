# Project-2-Real-World-Data-Wrangling-with-Python
Project 2 of Data Analyst Nanodegree Program from Udacity.

## Project Overview

This project focuses on wrangling data from various sources and in different formats, cleaning it, and then aggregating it for insights. The aim is to demonstrate the ability to collect, assess, clean, and present data efficiently.

In this project, we have collected two datasets using two different methods.
Dataset 1 : It is a movie dataset containg information about various attributes related to movies and movie success. This has 4803 rows and 20 columns and was downloaded manually from kaggle.

Dataset 2 : It is also dataset related to movie. It has information about movie credits i.e., cast and crew information of movies. This dataset has 4803 rows and 4 columns. I chose this dataset as it was related to my first dataset. This data was gathered from a database using sqlite3 package(We created a database first from csv file and then gathered the data from that database).

## Files:
Project2_Data_Wrangling.zip :  This is a zip file containing all files related to this project( uploaded as single zip file as files were huge and couldn't be uploaded without compressing). 
This zip file contains the following files:
Data_Wrangling_Project_Starter.ipynb: Jupyter Notebook containing the main analysis code
Data_Wrangling_Project_Starter.html : html file of the project
tmdb_5000_credits: Dataset 2 csv file from which database is created origonally from kaggle
tmdb_5000_movies: Dataset 1 csv downloaded manually from kaggle.
movie_database: Database created from tmdb_500_credits csv
Database_creation_dataset2.ipynb: jupyter notebook containing steps of movie_database creation
Database_creation_dataset2.html: html file containing steps of movie_database creation
cleaned_combined_movies_data: Final dataset generated after cleaning and merging Dataset 1  and Dataset 2
README.md: This file providing an overview of the project.

## Installation

This project requires Python 3.x and the following Python libraries installed:

- NumPy
- pandas
- Matplotlib
- seaborn
- json
- sqlite3
- Jupyter Notebook

You can install the requirements by executing pip install command.

## Usage
To run this project, you will need to:

Clone the repository to your local machine:
git clone https://github.com/N-R07/Project-2-Real-World-Data-Wrangling-with-Python
Navigate to the project directory:
cd Project-2-Real-World-Data-Wrangling-with-Python

Open the Data_Wrangling_Project_Starter.ipynb jupyter notebook for going through analysis done in this project.

Contributing:
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request

## Research:
After gathering, assessing, cleaning and merging Dataset1 and Dataset2, we did exploration to find the thecorrelation between various movie attributes, such as budget, genres, and cast/crew information, with indicators of movie success like revenue and ratings.

## License
Distributed under Udacity Honor Code.

## Acknowledgments
The datasets are taken from kaggle.
https://www.kaggle.com/tmdb/tmdb-movie-metadata






