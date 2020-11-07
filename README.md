# Tableau
***

[Link to presentation](https://public.tableau.com/views/CitiBike_16046784681780/AugustAnalysis2018-2020?:language=en&:display_count=y&publish=yes&:origin=viz_share_link) (I suggest using the 'Full Screen' option to view the report.

### August Citi Bike Data
***

This Tableau report uses [citi bike data](https://www.citibikenyc.com/system-data)

I took the last three years of data for the month of August. August was chosen because it's traditionally one of the peak months for Citi Bike usage.
<br>

Interesting Phenomena:
* Between 2018 and 2020, not only did existing stations grow in popularity, but more stations are present in 2020 than in 2018
* Users lying about their age is a realatively commonplace, with the most popular choice being 1969
* Data of users before 1950 was excluded, as it tended to show a small number of people logging very long bike rides
* Users to take the most rides tend to be in the 25-35 age range
* As a general trend, the younger the user, the longer their average trip
* From 2018 to 2020, the days of the week that saw the greatest increase in usage are Saturday and Sunday
  * This might indicate a greater trend of users riding for pleasure rather than commuting
* While the growth seen from 2018 to 2019 didn't continue into 2020, this is most likely due to COVID-19
* The overal number of rides held relatively steady from 2019 to 2020
  * I would expect the growth to pick back up after COVID-19 abates


### Cleaning Script
***
* The Clean and Combine jupyter notebook simply takes all csv files in a given directory and concatenates them into a single file.
* It also preforms a single cleaning step of removing any rows of data that don't have values for station name or station id.
* The data files were not included due to their size
