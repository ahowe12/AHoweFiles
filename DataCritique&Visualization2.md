# Data Critique and Visualization 2

Return to [portfolio](https://ahowe12.github.io/Alena-Howe-s-Portfolio/)

*Data source:*

“Museums, Art Galleries, Historical Sites, & Similar Institutions.” Museums, Art Galleries, Historical Sites, & Similar Institutions. USA Data. Accessed November 9, 2019. https://datausa.io/profile/naics/museums-art-galleries-historical-sites-similar-institutions#wage_ethnicity. 

*Original visualization:*

For this assignment, I wanted to find a data set that tells a story about salaries and diversity in the museum field. These are two popular topics in the field and have experienced positive change over the past few decades. However, there is still a lot of progress yet to be made, and there is a need for more accurate and comprehensive data on these trends. 

The best data source I could find was on Data USA’s website under the Museums, Art Galleries, Historical Sites, & Similar Institutions section. The visualization that caught my attention is the “Wage by Race & Ethnicity in Common Jobs” bar chart. The data for this chart was provided by the Census Bureau ACS PUMS 1-Year Estimate.  

![Original visualization](/Wages from Data USA.png)


*Wireframes*

![wireframes](/Wireframes.jpg)

When remaking this visualization, I wanted to focus on one occupation at a time. Since the target audience is museum professionals, I decided to focus on the “archivists, curators and museum technicians” occupation. In my wireframes, I experimented with ways to reflect changes over time. My first wireframe is a step in the right direction, but a bar chart still isn’t the best visualization. In my second wireframe, I experimented with a line graph, which is a better representation of changes in average salary over time. By roughly plotting the data, it’s easy to see that the original visualization was inaccurate and misleading.  

The user feedback that I got from a friend and my roommate was to use colors that are easier to read – my wireframes were colored using pen and some of the colors were hard to tell apart. My friends were able to understand what my visualization was trying to communicate, but they also shared my skepticism about the data’s completeness and meaning. The lesson that I learned is that even though the data came from a reliable source, like USA Data or the Census Bureau, that doesn’t mean that the data is complete enough to represent the story that the visualization is trying to tell. By remaking the chart, I’m going to show that the data is flawed and unfit to show wage changes by race/ethnicity.  

In my initial sketch, I started labeling the year increments, beginning with 2014, at the origin. The problem with this was that at first glance it looked as if the years started at zero. I was advised to shift the increments to the right. I put a dashed mark on the x-axis to emphasize that the distance between the 2014 mark and the origin didn’t represent one year but rather the chart started at 2014. 


*Final Visualization*

![Final visualization](/MuseumLineChart.png)

My first reaction to the original visualization was that a lot was going on. The chart compared the average annual salaries of six race/ethnicity groups across five occupations over four years, but only one year could be analyzed at a time. This made comparing changes over time difficult. The order of the occupation groups changed from year to year. The y-axis average salary increments changed when toggling between years. And, the bars for each of the race/ethnicity groups weren’t labeled. The viewer had to hover her cursor over each unlabeled box in the key to learn which color corresponded to each race/ethnicity group. These issues made me want to re-visualize the data in a way that focused on one occupation, showed salary changes over time, and had set salary increments. The number of issues with interpreting the original charts made me suspicious about what the data was actually communicating. 

In the wire framing process, I experimented with simplifying the data – I worked with one occupational group: archivists, curators, and museum technicians. This is the occupation of greatest interest to the target audience (museum professionals). By roughly plotting the data in a line graph, my suspicions about the accuracy/completeness of the data were confirmed. Average wages by race don’t vary that much from year to year. And, from year to year, an entire race/ethnicity just doesn’t disappear from the field – that’s what the data shows for the “other race” group. 

My redesigned data visualization was made in Tableau and achieves the goals discussed directly above. It focuses on showing that the fluctuations in wages by race/ethnicity in a subset of museum occupations (e.g. archivists, curators, and museum technicians) between 2014 and 2017 is due to flawed/insufficient data. 

I identified the primary audience for this data/visualization as museum or non-profit arts professionals working in leadership and human resources roles (essentially the people in charge of pay and workforce diversity). The original visualization wasn’t very effective at reaching this audience, because the occupation groups were broad, and the majority of them didn’t reflect the jobs worked by museum staff (such as advancement and education). For this exercise, I focused on the most relevant occupation to better appeal to the audience and explore my suspicions about the data. 

When making my visualization, I realized that this entire data set it meaningless. In addition to all the issues stated above, there is no explanation of the rationale used to form the occupation groupings. Although archivists, curators, and museum technicians all work at museums, these are completely different jobs. The job differences include pay amount and method and required education/experience). It’s also unclear how the data were collected. Were the same museums surveyed each year? Were the same positions at that museums tracked? How large was the data set? What external factors influenced salary changes? What was the margin of error? 

In an ideal world, I would have an informative description of where the data came from as well as an explanation for why the drastic fluctuations occurred from year to year. Unfortunately, Data USA doesn’t provide that explanation. As previously mentioned in my wire framing summary, this exercise taught me that even though the data came from a reliable source, like USA Data or the Census Bureau, that didn’t mean that the data was complete enough to tell an accurate, meaningful story. By remaking the visualization with a more appropriate method, this became clear. 
