# Overview

This was a quick two week project for me to learn data analysis using Python's pandas library. I had a lot of fun seeing how I can take raw data and condense it down into something that is usable.

I grabbed 3 data sets from Kaggle.com.
* [Corona Virus data](https://www.kaggle.com/imdevskp/corona-virus-report)
* [Country population data](https://www.kaggle.com/tanuprabhu/population-by-country-2020)
* [Country income data](https://www.kaggle.com/frankmollard/income-by-country)

I used these three datasets to answer some questions I had about Covid-19. Using this data I was able to create some graphs to help answer my questions. These files have a lot of data on them, one main portion of the code is to shrink the data down into pieces that I can use to analyze. 


[Software Demo Video](http://youtube.link.goes.here)

# Data Analysis Results

Does population effect the number of Covid-19 cases?
Yes, in general the greater the number of people in a country the more Covid-19 cases. I also looked into population density and how that effected case numbers. I was a little surprised to see that density had less impact than sheer population. When comparing population density and cases their is not much of a correlation . 

Does wealth effect the number of Covid-19 Deaths?
Yes, in countries with a higher GPD less people died. From the results that I pulled wealth has a fairly direct correlation  with the amount of deaths from covid-19. I was not too surprised  to find this from my data.

# Note
All of this research is done with data provided by others. The information's accuracy is at the mercy of those who created the data. Other factors such as availability to take covid-19 tests, and people's choice to take tests may skew the data. 

# Development Environment

Jupyter Notebook
Visual Studio Code

Python 3 with the pandas library

# Useful Websites

* [Youtube - ploting](https://www.youtube.com/watch?v=a9UrKTVEeZA)
* [Youtube - pandas](https://www.youtube.com/watch?v=vmEHCJofslg&list=PLHfziVnBCsVDLr_Ss7jMlHbBznPmpWxH5&index=18)

# Future Work
Some items that could be improved
* Plots that overlay each other for better representation of data
* More specific plots to show more detail of less countries
* Use more math to find averages between cases and wealth
