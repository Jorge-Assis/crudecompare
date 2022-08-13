# Crudecompare Dashboard

### Overview

With this project I implemented a dashboard on a Jupyter Notebook to compare crude oil grades traded in the international market.
The used dataset is in the csv file found in the data folder. It is a compilation of 200 different crude oil assays and the Crudecompar Dashboard will focus on
three main parameters, API degree, Sulphur content and Total Acidity Number. More information about the topic is found [here](https://medium.com/@jeyenry/what-are-the-15-most-expensive-crude-oil-in-the-world-part-1-e830ce3a3767).

### How to use

To use the crudecompare dashboard, run all the cells of the crudecompare_dashboard.ipynb file. An interface will be displayed as shown on the figure below.

![alt text](/figures/interface.JPG "Interface")

1. Select the reference crude oil grade.
2. Select the source countries.
3. Select the quality parameters to be used on the comparison.
4. Chose the number of grades to compare
5. Click on the Submit button.

The result will be a table showing the grades ranked by proximity to the reference grade. In addition, the ranking is also displayied on a chart. Depending on
the number of quality parameters selected, the chart dimension will be 3d, 2d or 1d.

An additional Show Clusters button is available to display all the crude oil grades on a clustering classification chart. More details of Crudecompare Dashboard applications can be found [here](https://medium.com/@jeyenry/what-are-the-15-most-expensive-crude-oil-in-the-world-part-2-4213d1649e5f). 


