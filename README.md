# Movies-ETL

## Overview

The purpose of this study is to create a data pipeline that Amazing Prime Video can use to transform the movie data they collect on a daily basis. The code begins by extracting data from Wikipedia and Kaggle. We then transform the Wikipedia data by employing several data cleaning functions to remove any unnecessary data rows and columns, combine any columns with the same type of data, to rename our columns, and to parse through columns with data that uses different formatting. The code then tranforms the Kaggle data to prepare the two datasets for a merge. The two data sets are then merged into one data frame that is then loaded to SQL where we can retrieve the total number of rows for the movie and ratings data sets.
