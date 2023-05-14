# Time Series Data Visualization

**This project focuses on visualizing time series data using line charts, bar charts, and box plots. The dataset used contains the number of page views each day on the freeCodeCamp.org forum from May 9, 2016, to December 3, 2019. By leveraging the power of Pandas, Matplotlib, and Seaborn, you will gain insights into the patterns of visits and identify yearly and monthly growth trends.**

### Project Tasks

To complete this project, you need to accomplish the following tasks:

1. Import the data from the "fcc-forum-pageviews.csv" file using Pandas. Set the index to the date column for easier data manipulation.
2. Clean the data by filtering out days when the page views were in the top 2.5% or bottom 2.5% of the dataset.
3. Implement the draw_line_plot() function, which utilizes Matplotlib to create a line chart similar to "examples/Figure_1.png". The chart should display the daily freeCodeCamp Forum page views from May 2016 to December 2019. The x-axis should be labeled as "Date," and the y-axis should be labeled as "Page Views." The title of the chart should be "Daily freeCodeCamp Forum Page Views 5/2016-12/2019."
5. Implement the draw_bar_plot() function, which generates a bar chart similar to "examples/Figure_2.png". The chart should represent the average daily page views for each month, grouped by year. The legend should display month labels, and its title should be "Months." The x-axis should be labeled as "Years," and the y-axis should be labeled as "Average Page Views."
Create the draw_box_plot() function that employs Seaborn to draw two adjacent box plots, similar to "examples/Figure_3.png." These box plots should illustrate the distribution of values within a given year or month and how it changes over time. The first chart should have the title "Year-wise Box Plot (Trend)," and the second chart should have the title "Month-wise Box Plot (Seasonality)." Ensure that the month labels on the bottom of the second chart start from "Jan," and both x and y axes are correctly labeled. The necessary data preparation commands are already provided in the starter code.

### Project Structure

The project repository includes the following files:


- fcc-forum-pageviews.csv: The dataset file containing the data on the freeCodeCamp.org forum page views per day.
- time-series.ipynb: The main notebook that contains the Python code that analyses the data and creates the visualizations.

### Acknowledgments
This project is based on the curriculum of freeCodeCamp.org, specifically the Data Analysis with Python course.
