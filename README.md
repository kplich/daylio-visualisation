# daylio-visualisation
Jupyter Notebook for creating a plot of moods throught time.

## How to use:
### Export your Daylio data as a CSV file and add it to the folder.
### Add the moods.csv file:
**Required format:**
\<mood description\>,\<mood value\>,\<lower limit value\>,\<upper limit value\>,\<color name\>
 - mood description is an ordinary string,
 - mood, lower limit and upper limit values are float values with dot as a decimal separator (e.g. 2.5)
 - color name must be [recognized by matplotlib](https://matplotlib.org/examples/color/named_colors.html)
### Add events.csv file:
**Required format:**
\<date\>,\<event description\>
 - date must be in format YYYY-MM-DD
 
 ## Limitations:
  - only supports a single entry per day
  - only supports Polish and English

## Examples:
![Example one](https://raw.githubusercontent.com/kplich/daylio-visualisation/master/daylio%20plot.jpg)
![Example two](https://raw.githubusercontent.com/kplich/daylio-visualisation/master/example.png)
