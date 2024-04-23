# Project of Data Visualization (COM-480)

| Student's name | SCIPER |
| -------------- | ------ |
| Paul McIntyre | 302264 |
| Elisa Bianchi | 300928 |
| Laetitia Wilhelm | 298015 |

## Milestone 2 (26th April, 5pm)

**10% of the final grade**
### Visualization ideas:
We came up with the following 3 visualization ideas:
  - **Analyzing Race Strategies via Split Times (Paul)**: Through interactive visualizations, we want to understand and categorize race strategies and tactics by analyzing split times. This will offer viewers a granular understanding of athletes' performance throughout a race, allowing for deeper insights into their strategic approaches. We will go through the strengths and weaknesses of each strategy and the context in which they succeed or fail.
  - **World Map Medal Distribution by Country (Laetitia)**: Using geographical visualization techniques, we want to create a dynamic world map showcasing medal distributions by country. Users will be able to interact with the map, accessing detailed information about each country's medal count upon clicking, thereby providing a comprehensive overview of global athletic achievements. This can be applied with a single focus on gold medals per country or alternatively on total medals per country. We must consider how to handle multiple performances per country (take only the best performance, take top-k performances, take top-k athletes' best performances).
  - **Top-k Countries Race Times as a Time-Series Bar Chart (Elisa)**: Through a time-series bar chart, we want to illustrate the chronometric performance trends of the top-k countries across various sporting events. This visualization will offer a chronological perspective, allowing users to discern patterns and fluctuations in athletic performance over time. This can also be applied per gender.
  
### Extra Ideas:
  - **Video Animation of Time-Series Bar Chart**: We'd like to generate a video animation of our time-series bar chart over time, providing an entertaining and informative way to display our findings to viewers.
  - **Quiz on Optimal Racing Strategy**: We could create a quiz on which racing strategy is optimal given a specific context (e.g., how fast we are relative to our competition), engaging users in interactive learning experiences.
  - **Analyzing Race Strategies via Split Ranks**: in the same way as split times, we could analyze the ranks of each athlete in a race at every split, as wind resistance is a primordial factor to consider. This shows us more practical tactics and less theoretical data at the risk of oversimplifying an athlete's race performances. 

### Tools and Lectures:
Here are our proposed visualization tools as well as the corresponding lectures:

**Analyzing Race Strategies via Split Times (Paul)**:
  - **Reading CSV Files with D3.js (Based on "D3.js" Lecture)**: I'll start by leveraging my knowledge from the "D3.js" lecture to read the split time data from a CSV file. Using D3.js, I'll load the data into my web page to prepare it for visualization.
  - **Creating Line Plot Visualization (Based on "Data" Lecture)**: Using the insights I gained in the "Data" lecture, I'll make a line plot visualization showcasing the mean speed per split of 1500m Olympic finalists per 100 meters. Each line on the plot will represent a different athlete's performance for a given Olympic 1500m Final.
  - **Categorizing Race Strategies (Based on "Data" Lecture)**: Once these first steps are completed, I'll analyze the data to categorize the racing strategies employed by the athletes. Drawing upon concepts from the "Data" lecture, I'll identify patterns such as "sit and kick," "negative split," "front running," and "even pace."
  - **Creating a Landing Page (Based on "Basic Web Development" Lecture)**: To showcase my project effectively, I'll utilize HTML and CSS skills acquired from the "Basic Web Development" lecture to craft a visually appealing landing page. This page will host and reference all of our visualization tools and provide context and explanation for the project in a simple but complete overview.
