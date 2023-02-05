# Final-Project-Tableau

## Project/Goals
The  goal of this project was to build a visualization off a data set and to come up with an appropriate question to answer about the data. 

## Process
- Made a set of the top 10 players as  decided by player value, to use in various  visualizations   
- started with creating a visualization with a map. Mapped player nationalities  by the average player value for that nationality. I did need to combine England, Scotland, Wales  and Northern Ireland into the Country - United Kingdom.  
- made  scatterplots of player value against different variables. I played around with these and started with ones where I  expected higher value players  to be ranked higher in. From there I tried a bunch of different variables and picked out ones where the higher ranked palyers by value were not ranked as high in that value. 
- looked at the positions played by  the top 10 players ranked by average player value 

## Results
I chose Option 2 using the FIFA2018 Player Ratings dataset. 

Data Question: What are attributes of the top 10 players ranked by average player value. 

The FIFA data set had values that were strings and numbers. The nationality vaiable was a string that also provided a geographical location - country. There were no date vaiables. 

To learn more about the data set I created a bunch of scatter plots where I plotted different variables against value. Early on I felt player value would be an important variable to work with. I also created bar charts/histograms getting some more information on player age, player value and number of players per Nationality. I also played around different variables that you could map, nationality against count of nationality and average player value. 

The variables I determined to be important/focused my visualizations on were: value, nationality, name, preferred position, ball control, reactions, marking and interceptions. 

Map - I chose the map to average player value by nation. As the rest of the dashboard focuses on the top 10 Players by value I also included a filter so users can filter to just the top 10 players if they'd like. 

Text Table: I wanted a way to show player position, because I was interested to know if there were certain positions that may be valued higher. I also felt that maybe player position would have an effect on their score for different player attributes (ball control, reactions, marking and interceptions). Because there were so many combinations of preferred positions and only a couple of the top 10 players were similar I chose to show this information in a text table along with player names. I filtered this only to the top 10 players by average value so that it was not too clustered or too much to read. 

Scatter Plots: I wanted to show relationships between average player value and different attributes. I cherry picked the data to show here and narrowed down to 4 variables - ball control, reactions, marking and interceptions. The first two variables I chose were attributes I thought would be related to average player value - ball control and reactions. I next picked two variables where the attribute value was not as high for the top 10 players - marking and interceptions. My initial thought here was you might expect these top 10 players to be good at everything, but if you consider other factors it does make sense why the top 10 players might rate lower in some categories. I then placed a filter on these scatterplots which highlighted the top  10 players by average value. 



## Challenges 
A  challenge I had was coming up with a question to answer through the  visualization. I am  most interested in sport  and health data which is why I chose the FIFA data to work with. I also had challenges with making the dashboard visually appealing - I had an idea to use the FIFA logo colour as my base colour pallette, but it did seem a bit plain. 

## Future Goals
To take a deeper dive into variables selected. For example, the marking variable are the top players lower in that value because the players that are higher in the value play defence. It would also be interesting to condense preferred position played  into a smaller number of values to get more information out of that - it may take  some more soccer knoweledge to be able to do this in the most  accurate way. 
