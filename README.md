README
Author: Karan Kianfar
Class: CRP 456 – Programming in GIS
Date: December 2025

Purpose of the Code: This tool analyzes income data by calculating the percentage of households earning less than $10,000 per year in each Census Tract. It joins Census income data to Census Tract boundaries, creates a new feature class with an income percentage field, and generates a histogram of the income distribution

The tool uses the following datasets:

	1. Census Table S1901 (Income in the Past 12 Months)
	2. Census Tract Boundaries (Story County-a GeoJSON file)

to Run the Code Package
  Open ArcGIS Pro and add the toolbox (Income_Analysis.tbx) to your project.
  Open Income Analysis Tool from the toolbox.
  Select the required inputs:
  Income CSV (S1901)
  Census Tract GeoJSON
  Output feature class location
  Join fields
  Output PNG file location
  Display option
  Click Run.


The tool produces two main results:

	1.A final feature class that contains Census Tracts with a new field showing the percentage of households earning less than $10,000. This allows the user to map and visualize low-income areas.
	2.A histogram PNG that shows the distribution of these income percentages across all tracts, giving a quick visual summary of how many households fall into the low-income category.
