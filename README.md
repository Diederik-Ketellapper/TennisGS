# TennisGS
Data name : Tennis Major Tournament Match Statistics
Data URL : https://archive.ics.uci.edu/ml/datasets/Tennis+Major+Tournament+Match+Statistics
Short summary of the project and datasource :
The goal of this project is to predict the gender of a tennis player from the match stats of 2013 Grand Slam Tournaments, and along the way showcase the Python skills learned during this course.

In order to do so we are going to use the a collection of datasets from the UCI database with the grand slam matches statistics for 2013. There are 8 datasets, one per Grand Slam and Gender.

Aims :
The aims in preprocessing are the following:

Merge the 8 datasets into a unique dataset with new columns for tournament and Gender. The issues are that the columns and players names accross the different datasets are not spelled in the same manner.
The dataset has a lot of missing data which should be imputed.
Create a new players data set with the stats corresponding to each player per match, for estimation purposes.
The aims in the visualization are the following:

Show if the main statistics in tennis (Aces, Break Points and Unforced Errors) are comparable between surfaces, gender and rounds.
The aims in the estimation are the following:

Perform a logistic regression and try to predict whether a player is male or female.
Download :
Our data is divided into 8 different datasets, one per Grand Slam and per Gender.

The datasets can be retrieved from the above provided URL, first goal is to download them.
Then we will merge it into a unique dataset and append a column for sexes and for the different tournaments.
