
Analysis of Rental Housing Market


CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Packages
 * Workflow
 * Authors
 * Requirements


INTRODUCTION
------------
This analysis is done as part of the R-Bootcamp module from HS 2020. 
The aim of the analysis within this scope is to experiment with the different functionalities and methods introduced in this course to answer some analytical and hypothetical research questions.


PACKAGES
--------
For the visualisation extra packages needed to get installed:
- tidyverse
- mice
- plotly
- shiny
- esquisse


WORKFLOW
--------
After importing the Rental Housing Market data from the website: <https://datenportal.info/wohnungsmarkt/wohnungsmieten/>, data gets joined with another dataset.
The second dataset includes the number of residents in the cantons and gets joined to the first one.
After data preparation the graphical analysis is done.

Herefore there are 5 aims to get answered in the following analysis:
1. Analyze the rental price in relation to living space
2. Analyze per canton what types of apartments are mostly available
3. Show where are the most expensive apartments (canton)
4. Show where are the biggest apartments
5. Is there a relationship of the population in the canton and size of apartments?

In the graphical analysis different functions like:
plot, ggplot, plotly, qplot, boxplot and pairs get used.

For the 5 mentioned aims the analysis is described in the section: Graphical Analysis and Analysis.
As an extract of the analysis:
- It shows that there are 5 different types of apartments("Wohnung, Studio, Maisonettewohnung, Loftwohnung, Attikawohnung").
- The most expensive apartment is located in Zürich with 31'800 Swiss Francs per month.
- Whereas the biggest apartment available for rental is located in the canton of Graubünden and it has an area of 400 square meter


The last chapter is a chapter of our choice.
Here we looked at the package called "esquisse". This package is an interactive "shiny" gadget to create "ggplot2" charts in a browser.
Selecting out data you can test different plots.


AUTHORS
-------
This analysis is done by Fiseha Amine and Martina Schüpbach-Wolf.


REQUIREMENTS
------------
To run the R-code version 1.3.1093 at least needs to be installed.










     
