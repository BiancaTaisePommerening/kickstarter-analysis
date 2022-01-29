# Kickstarting with Excel 

## Overview of Project

### Purpose 
The purpose of this project is to analyze the events of Kickstarter' plays by month starting in 2010 till 2017.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The analysis of Outcomes Based on Launch Dates was performed by creating a pivot table and pivot chart that demonstrated the successful, failed and canceled kickstarter' plays throughout the months in order to display visually the peaks and downs of each type of outcomes.

![Outcomes_based_on_Launch_Date](https://github.com/BiancaTaisePommerening/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

The analysis of Outcomes Based on Goals was performed by creating a table and a line chart that shows the total number of successful, failed and canceled Kickstarter' plays based on goal ranges, as well as the overall total amount of projects and the percentage each type of outcomes represented from the total of projects of a specific range.

![Outcomes_Based_on_Goals](https://github.com/BiancaTaisePommerening/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)



### Challenges and Difficulties Encountered

Some difficulties were encountered while using IFS formula and adding the range/criteria, specially when I had to add 3 different of them. The obstacle was overcome by trying quite a few times, using google for examples of the formulas, watching a couple of videos, and reaching out to colleagues from the course.
Also when trying out the IFS formula, an attempt was made to filter the subcategory 'Plays' directly from the dataset, which didn't work quite well, so the solution was to filter it by adding it as a range/criteria inside the IFS formula.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?


1. No matter which month, successful kickstarter’ plays were higher than failed and canceled ones.

2. For the successful kickstarter’ plays there is a high peak in May and then a low peak in December. While the failed kickstarter’ plays had very little change throughout the year. In addition, the canceled kickstarter’ plays also had little to know change and were always on very low numbers. 


- What can you conclude about the Outcomes based on Goals?

By the point where the goal surpasses $20,000 the rate of successful kickstarter’ plays start to decline and get unbalances where it then goes up again on the $35,000 range but then it falls to 0% on the $45,000 mark. 
So it seems like in order to have a constant successful kickstarter results, the goal shouldn’t be above $20,000.


- What are some limitations of this dataset?

One limitation could be the fact that the dataset is 5 years old already could be a problem, because on this case where the subject of analysis is about Kickstarters, outdated data could implicate on having a result that doesn't represent the present scenario.
The fact that only a set of countries is been used could be another limitation as it is unknown if it is just a subset or the complete set of data available.
In addition, there is a limitation where currency is not consistent throughout the dataset, possibly making unrealistic to compare them considering that the real value is difference for each country.

- What are some other possible tables and/or graphs that we could create?

The exact same analysis could be added for each country separately, so they can be analyzed individually. 
Also, a table could be added with the conversion of the currencies and hoe much value they hold for each country.
