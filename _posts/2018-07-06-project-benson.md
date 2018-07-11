---
l
ayout: post
title: Week 1 of Bootcamp in the Books - Project Benson
---

The first week of being a Metis student and a west coaster was exhilirating to say the least! We hit the ground running right from day one. We completed our first project of the program, Project Benson. This had to do with analyzing MTA subway data. 

## The Problem

A non-profit called WomenTechWomenYes (WTWY) is hosting an annual gala at the beginning of the summer. They are looking to fill up the event with people that are passionate about increasing the participation of women in technology. In order to generate interest in the event, they are placing street teams at the entrances to subway stations to hand out flyers. Our job was to analyze MTA turnstile data (and others) to generate a recommendation for which subway stations these street teams should be placed.

## Datasets

My group utilized a variety of different data sets. Our primary source was the MTA data (as required). We also took a look at Yelp data and US Census data. This allowed us to make a recommendation based on a variety of different factors, rather than just pure volume of a subway station.

## Analysis

We primarily used the pandas and numpy modules to conduct our analysis. It was a great experience learning how to use and manipulate dataframes. I can see how they are very useful in the life of a data scientist. Once we created dataframes for our data, we manipulated it in a way that was optimal to display and present.

## Results

Below are the top 10 results we obtained from our MTA data analysis. We defintley wanted our conclusions to be amongst these 10 stations.

![image-20180710213945216](https://github.com/harm8717/harm8717.github.io/blob/master/_posts/mtagraphs.png?raw=true)

Below is the summary of the US Census data we analyzed. We also wanted to consider these neighborhood demographics when making a decision. 

![Demogrphaics](https://github.com/harm8717/harm8717.github.io/blob/master/_posts/demographics.png?raw=true)


Below are the results we pulled from the Yelp API. This summarizes the zip codes with the highest number of popular restaurants. We also wanted to consider these data as a additional feature to consider when doing targeted marketing.

![image-20180710214448697](https://github.com/harm8717/harm8717.github.io/blob/master/_posts/image-20180710214448697.png?raw=true)

## Conclusion

In the end our group recommended the following

- 34th Street Penn Station - Highest overall volume, as well as high income demographics and a large amount of popular restaurants
- 14th St Union Sq - Top 5 in NYC in terms of volume, but among the highest when it comes to popular restaurants
- 86 St - In the top 10 in terms of commuter volume, but mainy selected due to Census data. One of the highest median incomes, as well as the highest ratio of women out of neighborhood in NYC, thus making it an ideal area to target with street teams

## Final Thought

This project was a great introduction to the world of data science. I walked away from this project with a much better understanding of what it might be like to actually work for an organization as a data scientist and it is very cool!

Thanks to my team: Belle, Tarek and Irene!

