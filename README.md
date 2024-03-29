# Ages of Formula 1 GP Winners
# Motivation

As a sports fan over the last summer full of covid cancellations and delays in pro sports leagues I desperately looked for something to fill the void. Formula 1 was one of the only sport on throughout the summer so naturally I got invested in it. As I am still a novice fan in the sport having only watched one season I thought I would do some some statistical analysis on some questions that I had. Although, my question has changed multiple times I finally found some that interested me, "How does age affect GP wins in formula 1?", "Are some tracks better the older or younger a driver is?", and "Has the ages of winning drivers changed over time?".

# Data Process

I got my data from a Formula 1 statistics website titled Stats F1 (https://www.statsf1.com/en/statistiques/pilote/victoire/age.aspx). From here I took the data from the top 110 youngest drivers to win a Grand Prix in formula history as well as the data from the top 110 oldest drivers to win a Grand Prix in formula one history (Only including up to the first race of 2021). I then copied this data into excel and had to do a little bit of cleaning. To start with I had to remove hyperlinks from the Names of the Drivers and the tracks. From there I had to seperate out the tracks from the years of the races so that I could analyse both of those variables differently. Additionally, the ages of the driver were to the day so I had to make a column of just the year so it would be simpler to analyse. Lastly, there are repeats of names but I did not delete them as sometimes the same driver won at a young age and a older age so it did not make sense to delete them as the age of the driver at the time of winning a GP is what's important.

# Visualizations

![](https://github.com/jcohanlon/Data_115_Personal_Data_Set/blob/main/Final%20Scatter%20Plot.png)

To start with I made a scatterplot showing the ages of Grand Prix winners from the first race in 1950 to 2020. This plot gives the viewer an idea of hte ages of formula one drivers overall and how the age of winning formula one drivers have slightly changed over time. For example, from the 50's to the 60's the winning drivers seem to be older than the modern day grand Prix winners. Additionally, it shows that the majority of Grand Prix winning drivers seem to be within the age groups of 25 and 35.

![](https://github.com/jcohanlon/Data_115_Personal_Data_Set/blob/main/Age%20of%20Driver%20to%20win%20GP%20Hist.%20five%20yrs..png)

This next visalization is a histogram that gives the viewer an idea of how many drivers have won GP's by age. This graph supports the last graph as it shows how the majority of Grand Prix winning drivers are between the ages of around 25 and 34. Additionally, it shows that the ideal age to win in Formula One seems to be around 31 and 32. Performance younger than that seems to slowly increase as drivers get more experience well performance once you get older than that seems to drop off quite drastically and quick.

# Analysis

![](https://github.com/jcohanlon/Data_115_Personal_Data_Set/blob/main/Boxplot%20Distribution%20of%20Drivers%20Ages.png)
![](https://github.com/jcohanlon/Data_115_Personal_Data_Set/blob/main/Boxplot%20Distribution%20by%20Year%20%26%20Age.png)
![](https://github.com/jcohanlon/Data_115_Personal_Data_Set/blob/main/Boxplot%20Distribution%20by%20Track%20and%20Age%20Done.png)

I first and foremost wanted to see how ages impacted winning Grand Prix's in Formula One and I think I did that. For my analysis I evaluated the summary statistics as well as made the box plots visable above. The youngest age of a driver to win a Grand Prix is 18, the first quartile is 27, the median is 31, the mean is 31.03, the third quartile is 34, and the max is 53 with an IQR of 7. This means that the ideal ages in a formula one driver career seems to be a seven year period between the ages of 27 and 34 with the absolute prime age to be a GP winning formula one driver being 31. The only outliers in the ages of drivers winning a GP based off of the first boxplot were Luigi Fagioli (53) in the 1951 French GP, Giuseppe Farina (46) in the 1953 German GP, and Juan Manuel Fangio (46) in the 1957 German GP. This finding led me to making the next box plot to see if there was a trend in ages of GP winners throughout the years as the only three outliers were both older and all in the first decade of the sports history. This boxplot shows that yes although overall the ages of GP winning drivers has been mostly consistent in the earlier years they were slightly older on average. Lastly, I wanted to see if any tracks favored older or younger drivers and that is why I made the final box plot. Again, overall the tracks seem to be mostly consistent on how the ages of the drivers impact winning but there were some tracks that stood out. For, example Germany and Indianapolis seem to have an advantage to older drivers while Portugal, Turkey, Luxemborg, and Abu Dhabi seem to be better for winning if the driver is younger.
