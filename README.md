# visualizing-gender-gap
The Department of Education Statistics released a data set with information on bachelor's degrees awarded to women between 1970 and 2012. Randal Olson, a data scientist from the University of Pennsylvania, cleaned this data set, and made it available on his personal website. The data set, titled `percent-bachelors-degrees-women-usa.csv` can be found [here](www.randalolson.com/wp-content/uploads/percent-bachelors-degrees-women-usa.csv). The code can be viewed in `00_Visualization.ipynb`, and the final visualization can be viewed by itself in `gender_degrees.png`.

Presentation is an important part of data analysis. In this project, I aim to visually present the gender gap in various fields. The pandas package was used to work on the data set, and matplotlib was used to visualize the data. 

The following design decisions were made:

- Since there are several graphs to be displayed, the dashboard was divided into three columns, 'STEM', 'Liberal Arts', and 'Other'.
- The colors of dark blue and orange (for women and men respectively) are used to ensure legibility for color blind individuals.
- A dashboard with fewer graphs is most aesthetically pleasing without chart borders, however, in this case, left and bottom chart borders are included to improve readability.
- x-axis labels are only shown on the bottom-most graph for each column to reduce clutter.
- Additionally, the top and bottom graphs in each column label the lines representing men and women.
