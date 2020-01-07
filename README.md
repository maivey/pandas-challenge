# Academy of Py

![Education](Images/education.png)

This script is for the following scenario: Having spent years analyzing financial records for big banks, you've finally scratched your idealistic itch and joined the education sector. In your latest role, you've become the Chief Data Scientist for your city's school district. In this capacity, you'll be helping the  school board and mayor make strategic decisions regarding future school budgets and priorities. As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your responsibility is to aggregate the data to and showcase obvious trends in school performance.

## Prerequisites
This script requires imports of the following:
```code
import pandas as pd
from IPython.display import display, HTML
```

The report includes each of the following:

### District Summary

* Creates a high level snapshot (in table form) of the district's key metrics, including:
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### School Summary

* Creates an overview table that summarizes key metrics about each school, including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### Top Performing Schools (By Passing Rate)

* Creates a table that highlights the top 5 performing schools based on Overall Passing Rate. Includes:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### Bottom Performing Schools (By Passing Rate)

* Creates a table that highlights the bottom 5 performing schools based on Overall Passing Rate. Include all of the same metrics as above.

### Math Scores by Grade\*\*

* Creates a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

* Creates a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

* Creates a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Includes in the table each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### Scores by School Size

* Repeats the above breakdown, but this time groups schools based on a reasonable approximation of school size (Small, Medium, Large).

### Scores by School Type

* Repeats the above breakdown, but this time groups schools based on school type (Charter vs. District).
