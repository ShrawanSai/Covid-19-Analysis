# Covid-19-Analysis


During the pandemic, watching the news about the Covid spread in India was almost the only thing I did on TV. But then the data analysis and visualizations that are diaplayed on TV honestly don't convey as much information and lack providing an intuitive understanding.

This is just my attempt at making some interesting visualizations and conclusions/intuitions with the data available.


I have used the API from covindia.com to collect the data.
Unlike many resources, this source had an easy to access way to get the district-wise covid-19 spread data.


Presently, I have 2 ipynbs:
1. Covid-19 State-wise analysis: This notebook basically fits a gaussian curve along the datapoints for number of new cases recorded till date. It fits and plots a logistic curve for a state for the total cases till date and predicts the new number of cases to come by simple extrapolation

2. The second one is a interactive plotly graph that plots the total cases till date against the new number of daily cases for all states. You can also compare the graphs for 2 or more states seperately for a comparitive study.
