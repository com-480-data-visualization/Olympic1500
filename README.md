# Project of Data Visualization (COM-480)

| Student's name | SCIPER |
| -------------- | ------ |
| Paul McIntyre | 302264 |
| Elisa Bianchi | |
| Elise Wilhelm | |

[Milestone 1](#milestone-1) • [Milestone 2](#milestone-2) • [Milestone 3](#milestone-3)

## Milestone 1 (29th March, 5pm)

**10% of the final grade**

This is a preliminary milestone to let you set up goals for your final project and assess the feasibility of your ideas.
Please, fill the following sections about your project.

*(max. 2000 characters per section)*

### Dataset

> Find a dataset (or multiple) that you will explore. Assess the quality of the data it contains and how much preprocessing / data-cleaning it will require before tackling visualization. We recommend using a standard dataset as this course is not about scraping nor data processing.
>
> Hint: some good pointers for finding quality publicly available datasets ([Google dataset search](https://datasetsearch.research.google.com/), [Kaggle](https://www.kaggle.com/datasets), [OpenSwissData](https://opendata.swiss/en/), [SNAP](https://snap.stanford.edu/data/) and [FiveThirtyEight](https://data.fivethirtyeight.com/)), you could use also the DataSets proposed by the ENAC (see the Announcements section on Zulip).

Datasets:
  1. [Summer Olympics: 1500m winning times 1896-2020](https://www.statista.com/statistics/1098589/olympics-1-500m-gold-medal-times-since-1896/)
  2. [Summer Olympics: Men's 1500m medal table 1896-2020](https://www.statista.com/statistics/1117683/olympics-mens-1-500m-medal-table-since-1896/)
  3. [Olympic history: longitudinal data](https://figshare.com/articles/dataset/Olympic_history_longitudinal_data_scraped_from_www_sports-reference_com/6121274)
  4. [World Athletics Website (Olympic Split Times)](https://worldathletics.org/competitions/olympic-games/the-xxxii-olympic-games-athletics-7132391/results/men/1500-metres/final/result)


### Problematic

> Frame the general topic of your visualization and the main axis that you want to develop.
> - What am I trying to show with my visualization?
> - Think of an overview for the project, your motivation, and the target audience.

We want to analyze and visualize Olympic 1500 metre data through time in a complete and innovative way. Our target audience is sport fans curious to learn more about statistics, tactics and trends of Olympic 1500 metre races. It is in this frame of mind that we unpack and visualize various factors, showing similar trends in race evolution that we will try to categorize.
 
### Exploratory Data Analysis

> Pre-processing of the data set you chose
> - Show some basic statistics and get insights about the data

1. This dataset provides us with the name, sex, country, year and winning Olympic time.
2. This dataset provides us with the medal count by country in the Men's 1,500m at the Summer Olympics from 1896 to 2020.
3. Each row in this dataset is an individual athlete’s individual performance in an Olympic event.
4. We use this source to complete missing information with event-specific split times from the World Athletics Website, for example: 2020 and 2024 longitudinal data.

You can find the notebook with the preliminary insights [here](data_exploration.ipynb).

### Related work


> - What others have already done with the data?
> - Why is your approach original?
> - What source of inspiration do you take? Visualizations that you found on other websites or magazines (might be unrelated to your data).
> - In case you are using a dataset that you have already explored in another context (ML or ADA course, semester project...), you are required to share the report of that work to outline the differences with the submission for this class.

2 sport articles inspired us to develop this project:
- “Changes in running biomechanics during the 2017 IAAF world championships men's 1500 m final”. This paper mentions kinematic and kinetic characteristics of middle-distance athletes. The paper claims, in its introduction, that the predominant pacing profile of male 1500 m championship runners is to gradually increase speed from 300 m until the finish. We will verify this by analyzing split times of Olympic 1500m finalists.
- “Women’s 1500m Time Analysis time analysis – 2017 IAAF World Championships". This paper includes graphs of position and mean speed per 100m in 2017 Women’s 1500m World Championships. The paper elegantly displays plots of position and mean speed per 100m split over the 1500m World Championships. We will reuse their illustrative techniques to effectively visualize split times and split positions.

Our approach is original because we apply a successful pre-existing visualization to a broader dataset to enlargen the scope of race time splits over time.

## Milestone 2 (26th April, 5pm)

**10% of the final grade**


## Milestone 3 (31st May, 5pm)

**80% of the final grade**


## Late policy

- < 24h: 80% of the grade for the milestone
- < 48h: 70% of the grade for the milestone

