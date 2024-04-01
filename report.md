HW 8, CS 625, Spring 2023
================
Aishwarya Ramesh
Apr 20, 2023

## Project - Implement Final Chart

## Assignment

Use principles from data journalism/storytelling to refine one of your
proposed charts from HW7. You must include a headline that summarizes
the main point of your chart (as opposed to a title that only describes
your chart) and appropriate axis labels. You also should include
annotations or context as needed. This will be your final chart, so care
should be taken in choosing fonts, colors, and other design/aesthetic
aspects.

You may use any tool of your choice to complete this assignment. (But be
particularly careful about using Tableau as it may not as easily
customizable as the other options, and customization is a large part of
this assignment.)

## Title - Unemployment Rate Forecast

### Dataset

I chose two employment data set from the below link. You can find both
the excel data set in the repo as **Unemployment Per US State First Data
set** and **Unemployment Rates Second Data set** respectively.

[First Dataset
Link](https://www.kaggle.com/datasets/justin2028/unemployment-in-america-per-us-state)

[Second Dataset
Link](https://www.kaggle.com/datasets/pasicebear/us-unemployment-rates-per-state-20172021)

The first data set contains the year, state, Labour Force/State, State
Population, Total Employment/State and Total Unemployment/State. From
the given data set we can compare/analyse the unemployment/state graph
from 2017-2022.

In the second data set, we can find unemployment rates from 2017 to 2022
for every state in US. After downloading the data set from the above
mentioned link, I opened it in open refine to further clean the data. I
trimmed the leading and trailing whitespace from the string and exported
the data set and saved it in the repo.

### Questions and chart proposed in HW7

1.  Which US state had the highest unemployment rate in the given
    period?

    I plotted a bar graph and a line chart for the above question in my
    previous assignment.

2.  How did the unemployment rates in the US change over time during the
    period covered by the data set, and were there any notable trends or
    patterns?

    Below is the bar graph for the above question in my previous
    assignment.

![Initial Graph](HW7%20Image.png)

### Refined Chart

I want to retain the second question mentioned above for HW8 because it
visualizes the unemployment rate over the selected time period for every
state in the United States. This time, I refined the chart and came up
with a final visualization chart which helps in overall analysis of the
problem statement.

**Final Question:** How has the unemployment rate varied across
different counties and states in the United States over time and were
there any notable trends or patterns?

![Final Graph](Final%20Chart.png)

From the previous chart (HW7), we could observe the state with the
highest unemployment rate where as we could not analyse the year in
which it was at its peak where as from the final chart above, we can
visualize that the unemployment rate has increased potentially in the
year 2020, specifically in California, Texas, Las Vegas and New York we
can see a drastic increase in the unemployment rate. From the above
analysis, we can conclude that many people were unemployed during the
year 2020 due to Covid crisis where the situation across the world was
hard. Cities/Area like California, Texas and New York experienced a
major downfall in the employment during these tough times.

From HW7 Chart, we can observe that the visualization is done by
unemployment rate per state instead if we include time period as well we
can visualize the problem statement more precisely. In the final chart
above, you can notice that for each state the values are taken from
2017-2022 where we can analyze the unemployment status for every state
and for every particular year. On the Y-axis, we have unemployment rate
and on X-axis we have state and year. Also, the value for every state is
denoted with different colours and the values are labelled for more
precision.

**Use of Visualization Principles**

The following visualization principles from the semester were
incorporated into the final chart:

1.  Appropriate Chart : For this visualization, a line chart was used
    because it can be used to compare the values of a categorical
    variable (states) with a quantitative variable (unemployment rates).

2.  Data Labels: Data labels were added to provide precise information
    about the unemployment rates for each state over a given perion of
    time.

3.  Color Palette: To make sure that the colors used in the graph are
    aesthetically pleasing and distinct from one another, a color scheme
    was carefully chosen.The modified chart’s cool-warm color scheme
    effectively illustrates the differences in unemployment rates
    between states.

4.  Font Size and Style: The x-axis and y-axis labels, as well as the
    chart title, were given custom font size and style using the font
    size and font weight options. This improves the text’s legibility
    and aesthetic appeal.

**Annotations:** The chart is sorted based on alphabetical order of the
states for the year 2017-2022 for easy comparison. The x-axis is labeled
with states and year, the y-axis represents the unemployment rates for
every state. The chart has contrasting colors for simple visualization
and a title that encapsulates its key message. If more context or
annotations are required to offer more explanations or insights into the
data, they can be added.

**Findings:** If we observe the chart more carefully, we can note that
for every state the unemployment rate has increased in the year 2020.
Choosing a chart also accounts for a better analysis for which I have
used a line chart which depicts precise results for the unemployment
forecast analysis. I would like to conclude that from the above analysis
I could understand that the unemployment crisis was massive in the year
2020.

### Final Thoughts

Choosing a proper employment data set was a challenge to me. I had to
choose the data set which had a time period and unemployment value for
every state for the given time period. I spent majority time in finding
the right data set for my analysis and developing the charts. Splitting
the project into 3 separate assignment was also helpful, we could
complete the task without any confusion and could come with a proper
analysis and visualization for the problem statement.

## References

- Dataset,
  <https://www.kaggle.com/datasets/justin2028/unemployment-in-america-per-us-state>

- Tableau Topics,
  <https://www.simplilearn.com/tutorials/tableau-tutorial/what-is-tableau>

- Open Refine Tutorials,
  <https://multimedia.journalism.berkeley.edu/tutorials/openrefine/>

- Rstudio, <https://rmarkdown.rstudio.com/authoring_basics.html>
