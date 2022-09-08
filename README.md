# Plotly_Biodiversity

## Overview

This project visualizes bacterial data for each volunteer in a scientific study. Specifically, volunteers should be able to identify the top 10 bacterial species in their results.

## Technology and Requirements

* Data Source: BellyButton_bar_chart_starter_code.js, BellyButton_bubble_chart_starter_code.js, BellyButton_bubble_chart_starter_code.js and index.html
* Data Tools: ECMAScript, JavaScript, JSON and IO (Web Server)
* Software: ES6+, ECMAScript and Visual Studio Code

## Results
### Deliverable 1 - Horizontal Bar Chart
Code is written to create the arrays when a sample is selected from the dropdown menu.

Code is written to create the trace object in the buildCharts() function, and it contains the following:
* The y values are the otu_ids in descending order.
* The x values are the sample_values in descending order
* The hover text is the otu_labels in descending order.
* The layout array in the buildCharts() function creates a title for the chart.

When the dashboard is first opened in a browser, ID 940’s data is displayed in the dashboard, and the bar chart has the following:
* The top 10 sample_values are sorted in descending order
* The top 10 sample_values as values
* The otu_ids as the labels

Results with detail analysis:
Code is written to create the arrays when a sample is selected from the dropdown menu.

Code is written to create the trace object in the buildCharts() function, and it contains the following:
The y values are the otu_ids in descending order.
The x values are the sample_values in descending order
The hover text is the otu_labels in descending order.

### Deliverable 2 - Bubble Chart
The code for the trace object in the buildCharts(); function does the following:
* Sets the otu_ids as the x-axis values
* Sets the sample_values as the y-axis values
* Sets the otu_labels as the hover-text values
* Sets the sample_values as the marker size
* Sets the otu_ids as the marker colors

The code for the layout in the buildCharts(); function does the following:
* Creates a title
* Creates a label for the x-axis
* The text for a bubble is shown when hovered over

When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard. All three charts should also be working according to their requirements when a sample is selected from the dropdown menu.

### Deliverable 3 - Gauge Chart
The code to build the gauge chart does the following:
* Creates a title for the chart.
* Creates the ranges for the gauge in increments of two, with a different color for each increment.
* Adds the washing frequency value on the gauge chart.
* The indicator shows the level for the washing frequency on the gauge.
* The gauge is added to the dashboard.
* The gauge fits in the margin of the <div> element.
* When the webpage loads, the bar and bubble chart are working according to the requirements in Deliverable 1 and 2, respectively, and the gauge chart is working according to the requirements listed for this Deliverable

### Deliverable 4 - Dashboard Customizations
* Font family has been set to Montserrat
* Jumbotron contains a background image as seen below:

![bacteria](https://github.com/heartgears/Plotly_Biodiversity/blob/main/Challenge_Files/Images/Bacteria_UT_Austin.jpeg)
