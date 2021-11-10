# Assignment 3 & 4 Critique by Design

# Step one: Find a Data Visualization

# Introduction 
I decided to critique and redesign the visual on the following link: [COVID - 19 cases around the globe](https://quinterojs.medium.com/covid-19-infection-growth-rates-lagged-mortality-rates-and-other-interesting-statistics-ff39f5408a21) The reason I chose this visualization because I felt that COVID - 19 has become an integral part of our lifestyle. A person for once can get out of his/her house without a mobile phone, but he/she cannot leave the house without a mask and a sanitizer. This visualization was released by Center for Systems Science and Engineering at John Hopkins University. The source for this visualization was built using data from multiple sources, including the WHO, CDC, ECDC, NHC, and DXY. On further analysis, I found out that the visualization had missed out certain crucial information firstly, the value for each of the date across the 3-month period for the four parameters is not getting conveyed. Because of the wavy trend of the 4 parameters(increasing/decreasing), it gets really difficult to understand the actual absolute value for each of the them for any particular date. 

The following is a moment-in-time analysis of the coronavirus as of March 4th, 2020. The initial visual is shown below:

![alt text](https://miro.medium.com/max/2000/1*LsE11cXBSt43Q9peeMW-WA.png)

# Step two: Critique the Data Visualization

In my opionion, the following things don’t work and can be improved upon in this visual:

1.  I would prefer a bar chart to represent the different categories of cases to depict a clearer picture. For instance separating out all the 4 categories into 4 different bar charts-Confirmed, In treatment, Recovered and Deaths would be logical and visually appealing.
2.  The 'k' on the Y-Axis can be eliminated and can be added in Y-Axis Label.
3.  Then, I would prefer to depict the data month wise instead of date wise. This would portray a clear trend(increasing/decreasing) of COVID 19 cases across the globe.
4.  There are too many colors in a single graph, which diverts the attention from the actual data. We can separate them in different graphs by displaying different color schemes by using a neutral color (for instance blue).
5. This can also be achieved by using a Pie Chart where instead of classifying it by categories (Death, Confirmed, Recovered, In Treatment) we can classify it on the basis of months (January, February, March).
6. Lastly, I will specify the absolute value for each category so that the audience has a clearer picture.

# Wireframe 
I created an initital wireframe of my solution, which was a simple pen and paper sketch, as shown below
![alt text](https://github.com/mohiljainmj/jain-portfolio/blob/main/WireFrame_1.jpeg?raw=true)

# Step four: Test the solution

User 1 - 
1. Update the labels of the graphs.
2. Change the name of the dashboard.
3. If we can change the bar chart colors and add different colors for different types of cases. Blue color looks neutral.
4. The graph does not talk about the location.
5. Add numbers at the end of each bar.

User 2 -
1. Rearrange the graphs.
2. Add Active Cases and Recovered Cases widget.
3. Provide a legend for the color used.
4. Titles need to be aligned with what is being displayed.

# Step five: Build your solution 

<div class="flourish-embed flourish-chart" data-src="visualisation/7781695"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
