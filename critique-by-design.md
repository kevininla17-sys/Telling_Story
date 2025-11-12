| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Health Spending as a Share of GDP — MakeoverMonday Redesign
## Step one: the visualization

Original Visualization:
https://www.oecd.org/en/data/indicators/health-spending.html

I chose this OECD chart because it shows how much different countries spend on healthcare compared to the size of their economy. It’s based on trusted data and is useful for people like policymakers, journalists, and students who want to compare countries. However, the chart is not very easy to read or compare. The countries are labeled diagonally, which makes it harder to scan. The dark bars all look the same, so it’s hard to notice patterns or groupings. There’s also no clear average line or color coding to give more context. I saw an opportunity to redesign it in a way that makes the information easier to understand — for example, by sorting the countries clearly, adding color by region, and showing the overall average.

## Step two: the critique

I used Stephen Few’s checklist to look at how clear and useful the original chart is. The chart does a good job showing real data from a trusted source, and it’s easy to see that the United States spends much more on health than other countries. But it’s missing some helpful context. There’s no average line or extra information to show what’s normal or how things have changed over time.

The chart is also a bit hard to read. All the bars are the same dark color, and the country names are tilted, which makes it harder to compare quickly. It’s clean but also plain — there’s nothing that really helps you see patterns, like which regions spend more or less.

## Step three: Sketch a solution

<div class='tableauPlaceholder' id='viz1762920782598' style='position: relative'><noscript><a href='#'><img alt='Health Spending as % of GDP — 2019 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;He&#47;Health_SpendingPrototype&#47;Prototype&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Health_SpendingPrototype&#47;Prototype' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;He&#47;Health_SpendingPrototype&#47;Prototype&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1762920782598');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Step four: Test the solution

I shared my redesigned chart with three students to get feedback — two from the MISM program and one from the MMMP program. I asked them to tell me what they thought the chart showed, who they thought it was for, and if there was anything confusing or missing.

Feedback I received:
  1. Round the numbers to two decimal places to make the chart look cleaner.
  2. Add a vertical line that shows the average spending for each year so it’s easier to compare countries.
  3. Use different colors for different regions or continents to help people see patterns.

What I learned:
The feedback helped me see that even small details can make a big difference in clarity. People liked the overall layout but wanted more context and color to guide their eyes. Based on their comments, I made four changes: I rounded all numbers, added a vertical average line, used colors to show regions, and replaced abbreviations with full country names. These changes made the chart easier to understand at a glance and more engaging for viewers.

## Step five: build the solution

Final Visualization:
<div class='tableauPlaceholder' id='viz1762919811344' style='position: relative'><noscript><a href='#'><img alt='Health Spending as % of GDP — 2016 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;RQ&#47;RQG8P6G7D&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;RQG8P6G7D' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;RQ&#47;RQG8P6G7D&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1762919811344');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

For the final version, I used Tableau to rebuild the chart from scratch using the OECD data. I kept the same measure — health spending as a percentage of GDP — but redesigned how it looks and how people interact with it.

First, I created a horizontal bar chart sorted from highest to lowest, so viewers can quickly see which countries spend the most. I added a year slider, so users can choose which year they want to view. Then, I made several changes based on the feedback I received:
1. Rounded the values to two decimal places for a cleaner look.
2. Added a vertical line showing the average spending for that year.
3. Colored the bars by region or continent to show patterns between areas.

What I learned:
I noticed that even the simplest shapes, colors, and page layouts can be powerful ways to deliver information to the audience. Small design changes can make a big difference in how people understand and connect with the data. I also learned how to use Tableau features like filters, calculated fields, and average lines to make a visualization both informative and engaging.

## References
Data: https://data.world/makeovermonday/2020w42

## AI acknowledgements
I used an LLM to solve technical issues in Tableau.

