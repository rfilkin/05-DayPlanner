# 05-DayPlanner

This is a day planner that can be used to organize one's work day, on ah hourly basis from 9am to 5pm.

The top of the page will display the current weekday, month, and day of the month.

Clicking in each cell allows the user to enter notes for each hour of the day. 
Clicking the save button on any row will save the content of all rows into local storage. This data will persist upon closing or refreshing the page.

The cells on the page will dynamically change color according to the current local time.
- gray cells are in the past for today
- red cell is the current hour
- green cells are hours that have yet to happen today

On the backend, the moment.js library has been imported as moment.min.js.
The code used for the script is contained in the html file instead of in a separate script file.

# deployed version:
https://rfilkin.github.io/05-DayPlanner/
