| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


> Important note: this template includes major elements of Part I, but the instructions on Canvas are the authoritative source.  Make sure to read through the assignment page and review the rubric to confirm you have everything you need before submitting.  When done, delete these instructions before submitting.

# Outline
> Include a high-level summary of your project.  This should be a couple paragraphs that describe what you're interested in showing with your final project. 
 
Pittsburgh is exploring options to expand high-speed broadband availability, including the possibility of a public or open-access network. While affordability and digital equity are part of the discussion, a major unanswered question is whether municipal broadband could also stimulate new business formation, a critical driver of Pittsburgh’s long-term economic competitiveness.

This project investigates that question by analyzing six U.S. cities that deployed municipal, public open-access, or privately built fiber networks. Using difference-in-differences comparisons against carefully selected control metros, the analysis estimates how each network model influenced new business formation after rollout. These real-world case studies are then used to generate a forecast of the potential impact on Pittsburgh if the city were to adopt a public or open-access broadband model. The final project aims to translate this research into a clear, accessible data story for policymakers, stakeholders, and residents interested in local economic development.

> A project structure that outlines the major elements of your story.  Your Good Charts text talks about story structure in Chapter 8 - you should describe what you hope to achieve.  Make sure the outline is detailed enough that we can see how you anticipate your story unfolding.  You can incorporate your Story Arc from the in-class exercise along with your user stories and one sentence summary to make the topic even more clear. 

This project is organized as a four-part story. It begins by introducing Pittsburgh’s current broadband situation and the question of whether public or open-access internet could help create more new businesses. Next, it looks at six U.S. cities that have already rolled out municipal, open-access, or private fiber networks and compares their new business trends to similar control cities. These case studies show how different broadband models affected local entrepreneurship. The third part applies those observed effects to Pittsburgh’s baseline of about 4,500 new businesses per year to estimate how much growth the city might see under a public or open-access model. The project ends by summarizing what these findings mean for Pittsburgh and why broadband infrastructure could be an important tool for strengthening the local economy.

## Initial sketches
> Post images of your anticipated data visualizations (sketches are fine). They should mimic aspects of your outline, and include elements of your story.  

<img width="1389" height="1181" alt="image" src="https://github.com/user-attachments/assets/55aa1803-6b2c-4b33-a7d6-5364e433fae0" />

# The data
> A couple of paragraphs that document your data source(s), and an explanation of how you plan on using your data. 

This project uses publicly available data from the U.S. Census Bureau’s Business Dynamics Statistics (BDS), which provides annual counts of new business births for all U.S. metropolitan areas. These data allow consistent tracking of pre- and post-broadband trends in the six cities that adopted municipal, open-access, or private fiber networks, as well as in their matched control metros. Broadband rollout years were compiled from public city documentation, municipal announcements, and FCC filings to define the treatment periods used in the comparisons. For Pittsburgh, the BDS series is used to establish the current baseline of roughly 4,500 new business births per year. The project then applies the observed percentage effects from the treated cities to this baseline to estimate how different broadband models might impact Pittsburgh’s entrepreneurial activity. All cleaned datasets and supporting files will be uploaded to the GitHub repository for transparency.

> A link to the publicly-accessible datasets you plan on using, or a link to a copy of the data you've uploaded to your Github repository, Box account or other publicly-accessible location. Using a datasource that is already publicly accessible is highly encouraged.  If you anticipate using a data source other than something that would be publicly available please talk to me first. 

| Name                                                                 | URL                                                                                                                                                        | Description                                                                                                                     |
| -------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| Business Dynamics Statistics (BDS) – Annual Datasets                 | [https://www.census.gov/data/datasets/time-series/econ/bds/bds-datasets.html](https://www.census.gov/data/datasets/time-series/econ/bds/bds-datasets.html) | Primary dataset used for annual establishment births at the metro level; fully public and maintained by the U.S. Census Bureau. |
| U.S. Census Bureau – Metropolitan Statistical Area (MSA) Definitions | [https://www.census.gov/programs-surveys/metro-micro.html](https://www.census.gov/programs-surveys/metro-micro.html)                                       | Provides publicly accessible definitions and codes for U.S. MSAs used when matching treated and control cities.                 |
| FCC Broadband Deployment Reports & Public Filings                    | [https://www.fcc.gov/reports-research/maps](https://www.fcc.gov/reports-research/maps)                                                                     | Publicly available FCC sources used to verify broadband rollout timelines and municipal network documentation.                  |

# Method and medium
> In a few sentences, you should document how you plan on completing your final project. 

The final project will combine Tableau for interactive data visualizations and Shorthand for the narrative presentation. Tableau will be used to build small-multiple trend lines, treatment-control comparisons, summary effect visuals, and the Pittsburgh forecast chart. These visuals will then be embedded into a Shorthand-style scrolling story, allowing the narrative to unfold in a structured and visually engaging way. This method aligns with course expectations and supports a clear, audience-friendly data story.

## References
U.S. Census Bureau. (2024). Business Dynamics Statistics (BDS) datasets. https://www.census.gov/data/datasets/time-series/econ/bds/bds-datasets.html
U.S. Census Bureau. (2024). Metropolitan and micropolitan statistical areas (MSAs). https://www.census.gov/programs-surveys/metro-micro.html
Federal Communications Commission. (2024). Broadband deployment maps and reports. https://www.fcc.gov/reports-research/maps
Electric Power Board (EPB) of Chattanooga. (n.d.). EPB Fiber Optics network overview. https://epb.com
Greenlight Community Broadband (Wilson, NC). (n.d.). About Greenlight. https://www.greenlightnc.com
UTOPIA Fiber. (n.d.). UTOPIA Fiber network information. https://www.utopiafiber.com
City of Huntsville. (n.d.). Huntsville municipal broadband announcements. https://www.huntsvilleal.gov
Google Fiber. (n.d.). Network build and service areas. https://fiber.google.com

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._
