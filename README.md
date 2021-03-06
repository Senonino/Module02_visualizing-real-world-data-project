#<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Dream team... on budget...
*Olivia Tonkin, Albrecht Mariz, Senan Jadeed*

*Data Analysis February 2020, Berlin, 2020-02-14*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
Most of us have played the famous football game FIFA or at least heard of it. When you play on the manager mode and you want to build your team, but you face a lot of challenges and the most important of them is the high price for good quality players.
In this project we are trying to come up with a scientific way to do that and still save some money for ice cream afterwards.

## Questions & Hypotheses
We will be trying to accomplish the following tasks:

1. Buy 33 top players with a small budget of 900 million euro. "Nowadays a super star player is worth around 200 million Euro".

2. All 33 players should be younger than 26, because the aim is to build a team for the future.

3. The rating for each player should be higher than 80 on the fifa_20 scale and lower than 86, because if we go higher the prices would go crazy.

The only hypothesis we have is that those tasks are still achievable regardless of the inflated players' prices.        



## Dataset
To answer those questions, we worked with a data set that covers all players in the football game fifa_20. We downloaded the dataset from Kaggle.com. the older versions of FIFA are also available so a more in-depth study of how the player prices are increasing could be done in the future.

[Link dataset](https://www.kaggle.com/stefanoleone992/fifa-20-complete-player-dataset)


## Database
We created different data frames for the different versions of FIFA. After that and we did run some in depth analysis such as scatter plots, linear regression, logistic regression and some more.
Those data frames have been cleaned then merged and were reduced to the columns that we thought are interesting for our study.

## Workflow
The workflow was as follows:
1. Definition of topic and gathering possible data sources
2. Definition of questions that can be asked/topics that can be analyzed
3. Comparing data sources and decision which data sources to use
4. Cleaning data
5. Merging data
6. Running analysis with those data to gain insights (to our questions), incl. use of plots
7. Preparing presentation based on our dream team insights (Google slides)
8. Finalizing folder and file structure



## Organization
For communication we mainly used:
1. Slack

After definition of topic we set up
1. GitHub repository

For gathering possible data sources everyone worked on his own.
cleaning the data was relatively easy and then we did group analysis to every aspect we thought might be interesting.

The repository is set up as follows:


### Main Notebook:
[FIFA Analysis & Visualization](https://github.com/Senonino/Module02_visualizing-real-world-data-project/blob/master/2_fifa_Analysis%20%26%20Visualization.ipynb)

[Readme](https://github.com/Senonino/Module02_visualizing-real-world-data-project/blob/master/README.md)

### Subfolder with following content:
##### Only one Folder called Extras: 

contains all the photos and files that we used in preparing the presentation.


##### 2. Export files (*.csv*):
dream_team_on_budget.csv


## Links

[Repository](https://github.com/Senonino/Module02_visualizing-real-world-data-project)

[Slides](https://github.com/Senonino/Module02_visualizing-real-world-data-project/blob/master/Dream%20Team.pdf)
