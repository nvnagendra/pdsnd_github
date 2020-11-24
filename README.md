### Date created
project created on 21 Nov 2020.

### Project Title
__US bikeshare exploration project__

### Description
In this project, we are evaluating the descriptive statistics of the bikeshare data across different cities and user groups in US.

### Pre-requisite system setup
* I used the following IDE, packages and software to execute this project:
    * Python 3, NumPy, and pandas installed using Anaconda
    * Visual Studio Code
    * Terminal on Mac
* It is advisable to have something similar or  the exact setup on your machine to execute this package. 

### Files used
1. following were the input files were used for the project:
    1. chicago.csv
    2. washington.csv
    3. new_york_city.csv
1. Following is the code file that needs to be executed: 
    1. bikeshare.py

### The Datasets:
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

    Start Time (e.g., 2017-01-01 00:07:57)
    End Time (e.g., 2017-01-01 00:20:53)
    Trip Duration (in seconds - e.g., 776)
    Start Station (e.g., Broadway & Barry Ave)
    End Station (e.g., Sedgwick St & North Ave)
    User Type (Subscriber or Customer)

The Chicago and New_York_City files also have the following two columns:

    Gender
    Birth Year

### Expected Output
* Following is the output upon executing the code

* Popular times of travel (i.e., occurs most often in the start time)
    * most common month
    * most common day of week
    * most common hour of day
* Popular stations and trip
    * most common start station
    * most common end station
    * most common trip from start to end (i.e., most frequent combination of start station and end station)
* Trip duration
    * total travel time
    * average travel time
* User info
    * counts of each user type
    * counts of each gender (only available for NYC and Chicago)
    * earliest, most recent, most common year of birth (only available for NYC and Chicago)


### Method to execute the code
* Clone the project
* Prerequisite
    * You must have installed python and libraries like numpy and pandas.
* Run the project
    * Open the terminal
    * Run python bikeshare.py

### Credits
* https://www.python-course.eu/python3_input.php
* https://stackoverflow.com/questions/23294658/asking-the-user-for-input-until-they-give-a-valid-response
* https://stackoverflow.com/questions/2847386/python-string-and-integer-concatenation
* https://stackoverflow.com/questions/19377969/combine-two-columns-of-text-in-dataframe-in-pandas-python