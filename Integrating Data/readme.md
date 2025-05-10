# Integrating Data Folder

## Contents
After obtaining all of the different datasets and saving them to CSV files, I wrote code in a Jupyter Notebook to integrate these datasets into one main dataset. This main dataset is a called csv file is called election_results_with_county_fuel_and_pop. This CSV file is also loacted within this folder. In addtion to provide more context on the final merged data frame the data dictionary is listed below. 

### Table 1: Data Dictionary

| Field               | Type    | Description                                                                 |
|---------------------|---------|-----------------------------------------------------------------------------|
| state               | Text    | Name of State                                                               |
| county              | Text    | Name of County                                                              |
| trump votes         | Numeric | Number of votes for Trump in each county for each state                     |
| clinton votes       | Numeric | Number of votes for Clinton in each county for each state                   |
| total votes         | Numeric | Total number of votes in each county for each state                         |
| trump vote %        | Numeric | The percentage of votes for Trump in each county                            |
| clinton vote %      | Numeric | The percentage of votes for Clinton in each county                          |
| electric vehicle %  | Numeric | The total percentage of electric vehicle (EV, hybrid electric, plug-in EV) |
| population          | Numeric | The total population based on US Census data for each county               |
| voter turnout %     | Numeric | The percentage of voters in each county                                     |



