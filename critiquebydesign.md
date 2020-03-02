# From the Stage - Data and the Future of Opera 

### OPERA America: The Data Gatherers of Opera 

Anyone who knows me knows that I adore opera. I cry when the curtain goes up, listen to opera on Spotify, and intern for an opera company. Within the US and Canada, the OPERA America organization serves companies nation-wide though providing resources, tracking attendance and performance data, supporting the creation of new works, and much more! OPERA America's goal is to support creators, performers, and administrative staff who make opera possible. One way they fulfill this mission is through data collection and publishing reports. To learn more about OPERA America, visit their website <a href="https://www.operaamerica.org" target="_blank">here.</a>

Source: <a href="https://www.operaamerica.org/content/about/index.aspx" target="_blank">https://www.operaamerica.org/content/about/index.aspx</a> 

### The Original Data Visualization

Each year, OPERA America publishes an Annual Field report, intended to give a holistic view of the state of the industry. For this assignment, I used data from the Annual Field Report: FY 2017. In early January 2020, they did publish the next iteration of this report. However, I am more familiar with the FY17 data, and I think it needed work. 

The full FY17 report can be found <a href="https://www.operaamerica.org/files/oadocs/financials/FY17_AFR.pdf" target="_blank">here.</a>  In addition to the visualization, this document from OPERA America also contains all the necessary data for the redesign.  I chose to focus on the chart at the bottom of page 5 titled "Percent of Total Operating Revenue." I've inserted a screenshot below. 

![OriginalVisualization](/OperaAmerica_PercTotalOperatingRev.png)

This specific chart refers to data regarding Budget 1 opera companies. Because there are so many member opera companies, OPERA America divides them by "Budget Groups" to compare similarly sized organizations. Budget 1 companies include The Dallas Opera, Houston Grand Opera, Los Angeles Opera, Lyric Opera of Chicago, Michigan Opera Theater, San Francisco Opera, the Santa Fe Opera, Seattle Opera, and Utah Symphony/Utah Opera. 

So why pick this graph? To be honest, I really didn't understand what it was trying to say. It's imperative for an opera company to know how it's getting funded. Particularly in recent years, many opera companies have been struggling financially for a number of reasons (that's a different data set). If I were an executive at a large opera company, I would need to have a complex understanding of the revenue streams that contribute to my operating budget in order to plan for the future and ensure I am running a sustainable operation. That's what I *wanted* this visualization to tell me. 


Source: <a href="https://www.operaamerica.org/files/oadocs/financials/FY17_AFR.pdf" target="_blank">https://www.operaamerica.org/files/oadocs/financials/FY17_AFR.pdf</a>     

### The Redesign Process

##### Critique

But that isn't what the visualization showed me. Looking at the chart above just confused me. Using Stephen Few's Data Visualization Effectiveness Profile, I critiqued the chart and learned where I wanted to improve it. Using this method, I assigned the chart low scores in usefulness, perceptibility, intuitiveness, aesthetics, and engagement. Many of those facets are interconneced. For one, the color scheme did not help me interpret the graph. On my computer screen, it was hard to distinguish the different shades of green. Different colored text on top of the labels did not help the case. I was looking for a connection between all 4 categories, and couldn't find a clear one. Earned income is very different from contributed income. The color scheme contributed to confusion regarding usefulness, perceptibiltiy, aesthetics, and engagement. I also didn't like that the stacked bar charts showed 3 non-consecutive years (2013, 2016, and 2017). I had just assumed it would show the past 3 years, so this impacted the intuitive nature of the chart. I wondered - why show only 3 years? If you are looking at trends, shouldn't you use all the data? This helped lead me to my wireframe design.

##### Wireframing 

I kept on wondering why OPERA America chose to show only those 3 years, despite having data for 2013 through 2017. That helped in my wireframing approach - I wanted to somehow show the data from across all 5 years. I wasn't sure the best way to do that, so I came up with 2 ideas, shown below! 

![Wireframe1](/Wireframe1part1.JPG)
![Wireframe2](/Wireframe1part2.JPG)


The most important thing to me was being able to show the trends. I also adjusted the colors to be, what I thought, more readable. Because Box Office Revenue is a type of Earned Revenue, I chose to make the both different shades of purple. While Opera America separated the two, they are related. Personally, I noticed that the scale I selected for the line chart was off because no one revenue stream accounted for more than 40% and my scale goes all the way up to 100%. 

When asking for feedback, I realized the colors I selected were not as helpful as I thought. The people understood how the first and second graph were related. However, one remarked they were confused with how the line graph overlapped with each other and another mentioned the area chart was just overwhelming with color. People commented that it was hard to distinguish between the different shades of purple at first. That was helpful insight, because it made me question why I grouped Box Office and Earned Income together (more on that later). They also mentioned it would be helpful to know the actual percentages of each revenue stream. 

The feedback on color, separation of revenue streams, and desire to know the hard data impacted my solution to this chart. 


### My Solution - An Area Chart

<iframe title="% of Total Cumulative Operating Revenue Over Time" aria-label="Interactive area chart" id="datawrapper-chart-5ojcY" src="//datawrapper.dwcdn.net/5ojcY/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="451"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}})}();
</script>

For my final redesign I decided to go with an Area Chart, but with some changes from my wireframed idea. For one, I decided to combine Box Office and Earned Revenue. In the arts world, we often talk about 3 revenue streams: Earned Income, Contributed Income, and Endowments (which is shown through this data as "Released Assets). In keeping with what is common in the industry, I decided to lump all Earned Income together. I also chose lighter colors than what I had originally drafted in my wireframe. Because there is a lot of color on the graph, I tried to pick something that would make it easy to look at. I also elected to go with an interactive portrayal, so the user can see more specifics on each year. 

#### What's the story? 

The main story is that all 3 revenue streams are almost equally accounting for the operating revenue of Budget 1 opera companies. This means that companies should focus on all 3 revenue streams, instead of primarily shifting their attention to Marketing and Sales or Development. It is worth nothing that when Earned and Contributed Revenue decrease, Released Assets increase. While more information is necessary to really understand this, I think this could suggest a withdrawal from an endowment fund or the restriction of funds for a specific capital campaign. At the end of the day, there is more work to be done on this chart, but I think my solution is more aesthetically pleasing and intriguing than the original. 


### Next for OPERA America 

This graphic and data comes from the FY17 report. Someone must have told Opera America they looked outdated, because the FY18 report, which was released early 2020, has a completely different look. If you are interested in seeing the "new and improved" Opera America report, you can find it <a href="https://www.operaamerica.org/files/oadocs/financials/FY18_AFR.pdf" target="_blank">here</a> 

[Back to Home](https://ascherry.github.io/cherry-portfolio/)

