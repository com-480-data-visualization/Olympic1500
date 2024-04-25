# Project of Data Visualization (COM-480)

| Student's name | SCIPER |
| -------------- | ------ |
| Paul McIntyre | 302264 |
| Elisa Bianchi | 300928 |
| Laetitia Wilhelm | 298015 |

## Milestone 2 (26th April, 5pm)
Here is the [website](https://laetitia-wilhelm.github.io/index.html) on which we will display the following visualization ideas.

**10% of the final grade**
### Visualization ideas:
We came up with the following 3 visualization ideas:
  - **Analyzing Race Strategies via Split Times**: Through interactive visualizations, we want to understand and categorize race strategies and tactics by analyzing split times. This will offer viewers a granular understanding of athletes' performance throughout a race, allowing for deeper insights into their strategic approaches. We will go through the strengths and weaknesses of each strategy and the context in which they succeed or fail.
  - **World Map Medal Distribution by Country**: Using geographical visualization techniques, we want to create a dynamic world map showcasing medal distributions by country. Users will be able to interact with the map, accessing detailed information about each country's medal count upon clicking, thereby providing a comprehensive overview of global athletic achievements. This can be applied with a single focus on gold medals per country or alternatively on total medals per country. We must consider how to handle multiple performances per country (take only the best performance, take top-k performances, take top-k athletes' best performances). 
  - **Top-k Countries Race Times as a Time-Series Bar Chart**: Through a time-series bar chart, we want to illustrate the chronometric performance trends of the top-k countries across various sporting events. This visualization will offer a chronological perspective, allowing users to discern patterns and fluctuations in athletic performance over time. This can also be applied per gender.
  
### Extra Ideas:
  - **Video Animation of Time-Series Bar Chart**: We'd like to generate a video animation of our time-series bar chart over time, providing an entertaining and informative way to display our findings to viewers.
  - **Quiz on Optimal Racing Strategy**: We could create a quiz on which racing strategy is optimal given a specific context (e.g., how fast we are relative to our competition), engaging users in interactive learning experiences.
  - **Analyzing Race Strategies via Split Ranks**: in the same way as split times, we could analyze the ranks of each athlete in a race at every split, as wind resistance is a primordial factor to consider. This shows us more practical tactics and less theoretical data at the risk of oversimplifying an athlete's race performances. 

### Tools and Lectures:
Here are our proposed visualization tools as well as the corresponding lectures:

**Analyzing Race Strategies via Split Times**:
You can find the sketch for this visualization tool [here](https://github.com/com-480-data-visualization/Olympic1500/blob/master/data/paces.jpg).
  - **Reading CSV Files with D3.js (Based on "D3.js" Lecture)**: I'll start by leveraging my knowledge from the "D3.js" lecture to read the split time data from a CSV file. Using D3.js, I'll load the data into my web page to prepare it for visualization.
  - **Creating Line Plot Visualization (Based on "Data" Lecture)**: Using the insights I gained in the "Data" lecture, I'll make a line plot visualization showcasing the mean speed per split of 1500m Olympic finalists per 100 meters. Each line on the plot will represent a different athlete's performance for a given Olympic 1500m Final.
  - **Categorizing Race Strategies (Based on "Data" Lecture)**: Once these first steps are completed, I'll analyze the data to categorize the racing strategies employed by the athletes. Drawing upon concepts from the "Data" lecture, I'll identify patterns such as "sit and kick," "negative split," "front running," and "even pace."
  - **Creating a Landing Page (Based on "Basic Web Development" Lecture)**: To showcase my project effectively, I'll utilize HTML and CSS skills acquired from the "Basic Web Development" lecture to craft a visually appealing landing page. This page will host and reference all of our visualization tools and provide context and explanation for the project in a simple but complete overview.

**World Map Medal Distribution by Country:**
You can find the sketch for this visualization tool [here](https://github.com/com-480-data-visualization/Olympic1500/blob/master/data/Visua2Draw.pdf). This part of the visualization will be composed of 2 to 3 graphs, each showing some information about the number of medals that each country won over the years.
  - **Creating an Interactive Map (Based on "Maps" Lecture):** I want to create a world map showing the total number of medals that each country won from 1896 to 2016. It will not focus on the specific types of medals they won. The countries will be labeled with a color gradient. If you point at a country, a small datasheet will appear with its name, the total number of medals, and details (gold, silver, bronze, number of participations).
  - **Transmitting a Coherent Message (Based on "Perception" Lecture):** I will choose the correct color gradient based on this lecture, so the website visitor will get the correct information from the first look at the map.
  - **Interaction with the Map (Based on the "Interaction" Lecture):** If you point at a country, a small datasheet will appear with its name, the total number of medals, and details (gold, silver, bronze). If you click on the country's name, another graph will appear showing the evolution of medals won per year. I will use the concept of Layering presented in Lecture 5 to display the medal details (gold, silver, bronze). One objective is also to be able to zoom in on the year axis.
  - **Further Idea (Based on the "Tabular Data" Lecture):** Create a Stacked Area Chart showing the evolution over time of the number of medals won per year. This graph would enable us to get a more nuanced vision of performances over the years for each country. For clarity, it will only take into account the k-most represented countries.

**Top-k Countries Race Times as a Time-Series Bar Chart:**
You can find the sketch for this visualization tool [here](https://github.com/com-480-data-visualization/Olympic1500/blob/master/data/race_bar_track.PNG).
  - **Loading and Preprocessing Time Data (Based on "Data" and "Tabular Data" Lectures):** Using JavaScript to load and preprocess the race time data from various international competitions. The preprocessing will involve sorting and selecting the top-k performances of each year for visualization.
  - **Designing the Time-Series Bar Chart (Based on "Designing Viz" and "D3.js" Lectures):** After preparing the data, the design phase will begin. Here, I'll use principles from the "Designing Viz" lecture to structure our time-series bar chart, ensuring it is intuitive and effective. The D3.js library will be crucial in implementing the dynamic elements of the bar chart, such as transitions to show changes over time.
  - **Animating the Bar Chart (Based on "More Interactive D3.js" Lecture):** To make the visualization engaging, I will animate the bar chart so that viewers can observe the changes in performance over time. Techniques from the "More Interactive D3.js" lecture will be applied to introduce smooth transitions and updates to the chart as new data points are selected or as the timeline progresses.
  - **Interaction and Responsiveness (Based on "Interactions" Lecture):** The final aspect of our visualization will focus on user interaction. Using skills from the "Interactions" lecture, I will implement interactive elements such as tooltips, clickable legends, and slider controls that allow viewers to select specific years or events, enhancing the user experience and providing deeper insights into the data.
