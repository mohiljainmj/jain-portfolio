# Assignment 3 & 4 Critique by Design

# Step one: Find a Data Visualization

# Introduction 

The graph that I have selected for this assignment to critique and redesign is called [COVID19 Global Totals as of March 04,2020](https://quinterojs.medium.com/covid-19-infection-growth-rates-lagged-mortality-rates-and-other-interesting-statistics-ff39f5408a21). This graph is available on the following link : 

![alt text](https://miro.medium.com/max/2000/1*LsE11cXBSt43Q9peeMW-WA.png)
 
This visualization was released by Center for Systems Science and Engineering at John Hopkins University. This visualization has been derived by leveraging data from multiple sources, including the World Heakth Organization, Centers for Disease Control and Prevention, European Centre for Disease Prevention and Control and  National Hurricane Center. The following points entail why I selected to critique this graph:

1. The graph is used to represent one of the most critical, life wreaking and havoc creating disease that hit our world since 2019: COVID19. Initially thought of as just a common flu, this disease completely turned the historically timeline into two categories- pre and post pandemic due to the deadly nature of this disease. Being on its receptive end, all our families across have been affected by this, including mine too. Despite scientific advancements, we released that pandemic is above science and research when it comes to human life.
2. COVID 19 completely transformed the way we live our lives now. Quarantine, vaccines, lock downs, social distancing etc are a things commonly heard and practiced in every household these days.  Sanitisers and masks are part of our daily attire now.
3. This graph depicts statics around the that are commonly used my medical staff, researchers, health care organizations, government of the countries, private industries and firms, aviation industries, citizens of the nations and the like.
4. On a perfunctory glance, I could see that though this data represents critical statistics, however, it misses to depict them in a clearly pattern. For instance, firstly, the value for each of the date across the 3-month period for the four parameters is not getting conveyed. Because of the wavy trend of the 4 parameters(increasing/decreasing), it gets really difficult to understand the actual absolute value for each of the them for any particular date.

  
# Step two: Critique the Data Visualization
I have considered the below metrics to analyse and critique the data visualization as per the google form:
- Usefulness
- Completeness
- Truthfulness
- Perceptibility
- Aesthetics
- Intuitiveness
- Engagement

In my opinion, the colour scheme chosen to represent each of the four different categories stood out really well. However, there are a couple of further observations and recommendations that I have entailed below:
- Usefulness:  The value for each of the date across the 3-month period for the four parameters is not getting conveyed. Because of the wavy trend of the 4 parameters(increasing/decreasing), it is really difficult to understand the actual absolute value for each of the them for any particular date. Thus, In my opinion it is not fulfilling the usefulness metric as the user is unable to analyze the trend and get the absolute value for the parameters defined.
- Completeness: The graph looks complete, however the I felt that the graph could have been depicted in a simpler way by segregating each of the parameter separately in 4 different graphs
- Truthfulness: The graph has been picked from a verifiable source and thus is conveying the actual COVID19 statistics till March 2020 for COVID19. However, here, as can be seen for 03-01-2020 and 03-04-2020, there are no “In treatment” COVID 19 cases which could have been elaborated why that is the case
- Perceptibility: There are a couple of things I observed here. Firstly, the trend graph is built one on top of each other and thus there is no proper demarcation value to understand the difference. After analysing it for quiet some time, I found out that at Some places the trend lines for some parameters , for instance, “in treatment” value had a huge increase in the trend initially, however, then towards the end it became 0. Despite the proper identification of the 4 parameters, it was taking a lot of eye travel to understand them. Secondly, the choice of colours could have been improved. Fourthly, I feel that the depiction across the months rather than dates would give the user better idea of the COVID19 trend.
- Aesthetics: The graph is labelled well – the chart tittle and the X and Y axis however, I feel there have been a poor choice of color palette. This could have been selected on the basis of “severity” for each of the parameter. For instance, the grave “Deaths” parameter could have been demonstrated in Red. I also feel that a pie chart can be used and instead of classifying it by categories (Death, Confirmed, Recovered, In Treatment) we can classify it on the basis of months (January, February, March).
- Intuitiveness: The graph was not Intuitive and required extensive time and effort to understand various things which I feel could have been demonstrated in a simpler fashion. I also believe, that any COVID19 statistics is a data which has been used quiet extensively in the field of research and medicine and a graph like this is not bringing out that value to understand the trend.
- Engagement: The cursory glance at the graph does not capture the eyes instantly. It takes time to get engaged in the graph and understand what it is trying to convey

# Step three: wireframe a solution

I created an initital wireframe of my solution, which was a simple pen and paper sketch, as shown below. Here I created four different charts to show the number covid cases across January to March 2020.

![alt text](https://github.com/mohiljainmj/jain-portfolio/blob/main/WireFrame_1.jpeg?raw=true)

# Step four: Test the solution

After I had finished making the wireframes, I got feedback from two people - User 1 and User 2 and gained invaluable insights from their opinions.

<b> User 1 - </b> 

1. Can you tell me what you think this is? <b><i>COVID 19 Dashboard</i></b>
2. Can you describe to me what this is telling you? <b><i> It is telling me about the number of covid cases in the first three months of the pandemic.</i></b>
3. Is there anything you find surprising or confusing? <b><i> The graph does not talk about the location.</i></b>
4. Who do you think is the intended audience for this? <b><i> Everyone. </i></b>
5. Is there anything you would change or do differently? <b><i> I would be doing the below mentioned changes.</i></b> 
<b><i> - Update the titles of the graphs as they sound similar to one another.</i></b>
<b><i> - Update the name of the dashboard.</i></b>
<b><i> - Instead of keeping blue, add different colors for different types of cases. As the color blue looks neutral.</i></b>
<b><i> - Add total number of cases for each category at the end of each bar.</i></b>

<b> User 2 - </b> 

1. Can you tell me what you think this is? <b><i>COVID 19 Dashboard</i></b>
2. Can you describe to me what this is telling you?<b><i>It is telling me about the number of COVID 19 cases in the first three months of the pandemic.</i></b>
3. Is there anything you find surprising or confusing?<b><i>The arrangement of the graphs.</i></b>
4. Who do you think is the intended audience for this?<b><i>Healthcare workers, researchers and general population.</i></b>
5. Is there anything you would change or do differently?<b><i>I would be doing the below mentioned changes.</i></b>
<b><i> - I would rearrange the graphs. Displaying Confirmed, In Treatment, Recovered and Death.</i></b>
<b><i> - I would add active cases and recovered cases widgets.</i></b>
<b><i> - I would provide a legend for the blue color used.</i></b>
<b><i> - Chart titles need to be aligned with what is being displayed.</i></b>

# Step five: Build your solution 

<div class="flourish-embed flourish-chart" data-src="visualisation/7781695"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
