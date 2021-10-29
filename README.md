# Microsoft Movie Recommendation

## Overview

Microsoft has approached us for recommendations on how they should approach stepping into the movie industry. We've analyzed various data sets (listed below) and will describe our findings and final recommendations throughout this document.  

Data Sets:
* imdb ratings
* rotten tomatoes
* various reviews
* movie budgets

## Business Understanding

We'll be looking to answer the following questions to help us better understand the layout of the movie industry. This will help us provide clear and succicnt guidance for Microsoft's movie endeavor. 

* Are there genres more popular than others?
* Does runtime matter?
* Is there a rating that outperforms others?
* Is there any correlation between net profit and budget?

## Data Understanding and Analysis

The first analysis we wanted to perform was checking to see if there was a clear winner in terms of genres so that we'd be able to provide Microsoft with clear direction for building out their team and their first film. We combined two different IMDB tables and cleaned up data to give us a list of roughly 72,000 records containing genre and average rating where we were then able to dig further and graph the highest performers. We put a floor of 100 votes in order to remove some type of skew by a movie having a few extreme ratings. 

By the graph below, we can see that Fantasy and Adventures have a higher average rating in comparison against other genres. There's certainly a trend bias in the movie industry where just because the last 11 years of data shows us these two genres as a favorite, doesn't necessarily mean we'll see the same trend over the next 10.

If you want to see we came to the following conclusion in more detail, feel free to check out the below link:


![image](https://user-images.githubusercontent.com/73855593/139341591-6f4cdd90-be41-476b-98e9-588b9b62b06b.png)

![image](https://user-images.githubusercontent.com/73855593/139341610-e7c7e95f-a907-46f0-bf4c-b541818b1946.png)

As we can see by these graphs if there is a bigger budget there is a bigger return on investment.

![image](https://user-images.githubusercontent.com/12703065/139083630-f594ab5b-c264-4cdf-ac3b-a34b980478a6.png)

In general film runtime doesn't have a large effect on the rating, however a longer movie has slightly higher ratings

![image](https://user-images.githubusercontent.com/73855593/139341330-c33497b6-b8cb-4b22-b275-def7c3abe60d.png)
![image](https://user-images.githubusercontent.com/73855593/139341375-a3433c9e-fcb3-4437-86cd-d8c5a9a4522c.png)


Rated R movies have the highest potential for profits, however PG-13 movies are consistently profitable.

![image](https://user-images.githubusercontent.com/73855593/139341420-9139e8ea-f667-4a5a-94d4-74e3100259b3.png)

Buena Vista, Warner Bros. and Universal Studios are leading the industry so it's important to look into what they're doing correctly

## Conclusion
After analyzing the data, we recommend that Microsoft takes the following approaches when producing their own movie
* Have a large enough budget
* Make sure the movie is long enough to tell the story necessary
* Aim for a pg-13 rating
These strategies will reduce risk and maximize potential profits.

[Project Notebook](https://github.com/meowkaiser/STRONGEST_Project1/blob/main/Final_notebook.ipynb)

[Presentation](https://docs.google.com/presentation/d/10B_Zq0XGJDtXAyG_2E6W3330rtobWPxK3R64iI1TK6U/)
