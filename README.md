# TennisGS
#### Data name
Tennis Major Tournament Match Statistics
#### Data URL 
https://archive.ics.uci.edu/ml/datasets/Tennis+Major+Tournament+Match+Statistics

#### Short summary of the project and datasource :
The goal of this project is to predict the gender of a tennis player from the match stats of 2013 Grand Slam Tournaments, and along the way showcase the Python skills learned during this course.

In order to do so we are going to use the a collection of datasets from the UCI database with the grand slam matches statistics for 2013. There are 8 datasets, one per Grand Slam and Gender.

#### Aims
The aims in preprocessing are the following:
1. Merge the 8 datasets into a unique dataset with new columns for tournament and Gender. The issues are that the columns and players names accross the different datasets are not spelled in the same manner.
2. The dataset has a lot of missing data which should be imputed.
3. Create a new players data set with the stats corresponding to each player per match, for estimation purposes.

#### Visulation
The aims in the visualization are the following:
1. Show if the main statistics in tennis (Aces, Break Points and Unforced Errors) are comparable between surfaces, gender and rounds.

#### Estimation
The aims in the estimation are the following:
1. Perform a logistic regression and try to predict whether a player is male or female.


