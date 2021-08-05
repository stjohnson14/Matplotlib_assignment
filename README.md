### Pharmaceutical Data Analysis Project

In this case study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study.

My tasks were broken down into the following:

* Check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

* Use the cleaned data for the remaining steps.

* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

![1](https://user-images.githubusercontent.com/84537717/128413610-a6e0c12a-02b9-4947-9463-7241ca9df078.PNG)

* Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

![3](https://user-images.githubusercontent.com/84537717/128413659-e8bb9d9c-9e3d-4b05-9e3c-772584f6cda2.PNG)

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

![5](https://user-images.githubusercontent.com/84537717/128413735-ec8c23af-219a-45e9-ad44-f0b97c510c1a.PNG)

* Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

![6](https://user-images.githubusercontent.com/84537717/128413801-ca1255cf-57c4-4c29-995b-6b980ee7d37c.PNG)

* Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

![7](https://user-images.githubusercontent.com/84537717/128413921-455f0139-be46-4326-b019-67a9d71453a5.PNG)



