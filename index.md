---
title       : Sentiment Analysis of US Leaders
subtitle    : Using Twitter Stream to determine effectiveness of US Leaders
author      : Ritesh Sinha
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : standalone # {standalone, draft}
knit        : slidify::knit2slides
---

## Sentiment Data Analysis of US Leaders

1. For US elections 2016, There is lot of buzz.
2. This looks a close race this time, with uncertainty as who will win this time.
3. Mining social media can give a insight to leader's popularity.

--- .class #id 


## Using Shiny App to distribute 

1. Having the analysis is one thing, but showing this to masses is another.
2. This could become a herculean task, if we want to show on a web platform.
3. Potentially this could lead to lot of learning and time.

--- .class #id 

## R Ecosystem to the rescue

1. Thankfully, there is R and there is R Studio.
2. Even better, we have shiny to do a number of things.
3. The application can be coded in R, and it can published on web for further usage.
4. It can be an interactive user interface, where user can chose Leader name.

--- .class #id 

## Details of the application

1. A simple user interface.
2. Selection panel contains Leader list in a dropdown.
3. Check boxes provide type of sentiments - Positive, Negative and Neutral
4. A list of dates which user can chose.
5. Based on above three selection, the map is shown to the user with data points in Red, Green and Yellow.


--- .class #id 


## About the data

1. This app uses 6799 rows of Data from Twitter for analysis.
2. It has got 16 leaders.
3. These leaders belong to Democratic and Republican party.
4. The url of the app is : https://hnhenk10.shinyapps.io/developing-data-product-shiny



