# belly-button-challenge

## Welcome to the Belly Button Biodiversity Dashboard Challenge! 🎉

Dive into the world of belly button microbes with this interactive dashboard project. This repo is designed to help you visualize and explore the fascinating data on microbial species that inhabit human navels. Here’s a guide to everything you’ll find in this repository and what you need to do.

## What’s Inside

* index.html: The main HTML file that serves as the structure for your dashboard.
* samples.json: A JSON file containing the dataset of microbial species found in belly buttons, including their abundance and metadata.
* static folder: Contains static resources like stylesheets and JavaScript files used for building the dashboard.

## Project Overview

#### Create a Bar Chart:
This chart will show the top 10 Operational Taxonomic Units (OTUs) for each selected sample. The bar chart helps visualize which microbial species are most common in different samples.

#### Build a Bubble Chart:
This chart will display each sample with bubbles representing different microbial species. The size and color of the bubbles will represent the abundance and type of each species.

#### Display Metadata:
The dashboard will include a panel displaying detailed metadata for each sample, such as demographic information.

#### Interactive Dashboard:
The dashboard will update all visualizations dynamically based on user selections from a dropdown menu.

## Instructions

* Fetch the Data:
Utilize the D3 library to read and process the samples.json file.
* Create and Update Charts:
* Develop a horizontal bar chart and a bubble chart to display the microbial data.
Ensure that all charts update when a new sample is selected from the dropdown menu.
* Design and Layout:
Design a user-friendly layout for the dashboard that showcases the bar chart, bubble chart, and metadata panel.


## Tips & Tricks

* Debugging: Use browser developer tools to inspect your data and troubleshoot any issues.
* Documentation: Refer to the D3.js documentation and Plotly.js documentation for assistance with creating visualizations.