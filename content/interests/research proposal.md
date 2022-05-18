---
title: Research Proposal
date: 2021-11-02T08:10:29-04:00
draft: false
showReadingTime: false
hideSummary: true
hidemeta: true
ShowBreadCrumbs: true
ShowPostNavLinks: false
---

# CS580S2022

## Assignment 9

### Written Work for Final Deliverable

#### Name

Liam Black

#### GitHub Account Name

LiamBlack3

---
```
1. What is the area of your research in your proposed project idea? What is your specific proposed idea and why is it important? Motivate with references as relevant.

Data Analytics for nba player data specifcally using touch tracking and advanced stats to compare against +/- statistics. I would like to conduct a player analysis to answer the question of why the plus minus statistic is innacurate in determining player value, and what is a better way to scout player skill.

2. What is already known in the literature about this problem area; where does your project’s concentration of your own interests lie in this area? What goals have you set for this project? Motivate with references as relevant.

PLayer statistics but the more general stats like PPG APG AND RBG, goals is to look at advanced stats and give player scouting based off of that. Create databases that are relational where I can look at individual player statistic and make conclusions from them. Since the plus minus statistic is already known  and used, my interests lie in debugging why that statistic is not the most accurate in determing player skill. My interest will be creating graphs and linear models of relationships between statistic to find the most positive correlation between variables amongst players. My goals are to create a database without using sql and have many players statistics in there from a season or more and be able to query it to find those answers of how do we best determine a players skill from their stats.

3. What is the Gap between the field and the knowledge of the area? Why is this gap present and what are the implications of the gap and what is your solution to try to bridge this gap? Motivate with references as relevant.

The gap is that +/- is an inaccurate statistic, look at handtracking and advanced statistics to debunk those mainstream statistics. To try and bridge these gaps I will preform a statistical analysis that shows how there are a multitude of outside factors that affect the +/- statistic and if it is innacurate, by creating graphs and looking at correlations between statistics and outcomes of games and player averages over a season. I would also like the answer the question that if there is a better way to calculate a players individual skills and specialties using advanced rather than typical statistics. I will be refrencing the handtracking data which is taken from high speed motion camera's and use that to get my own player analysis and then compare it to the already calculated plus minus statistic to see which better represents a players impact in a game regardless of outcome.

4. Using specifics, what is/are the research question(s) that motivate your research project?

Are +/- stats accurate?
what does handtracking data look like for the best team versus the worst team?
can hand tracking data predict wins and losses?


5. Discuss the scope and feasibility of this work. For instance, what are the limits in your area of research? How far do you indent to follow this research question?

I have to used previous nba data because current is always changing during the season, unless I am able to implement a prediction. One limit to the area of my research is total size, if I were to do all active players in the NBA that would certainly be a lot. I would like to predict player tendancies and team strategies based off of the touch tracking data and I would like to follow it for each nba team with at least their starting players.

6. Discuss the prototype you developed to demonstrate feasibility. Give an overview of its design and implementation. Discuss any data and existing software/libraries/tools that were necessary for the development of your prototype.

Prototype created a database and then conducted querries on it. I used spacy and sqlite. Inside this prototype I used a sqlite database that contained data from one specific team and statistics for the players on that team and ran queries in a terminal where sql commands did not have to be known to run. I would like to give users the ability to find out information and specialties of players without having to know player information other than their name and without having to know database commands.

7. What evidence is there that the prototype will provide any support for your project? How will your prototype be helpful in the planning, execution and completion of your research project?
Prototype showed me how to create a database and search for matches in a text file although I moved to an alternative dataset. This gave me a baseline understanding of how to query a database but I would like to expand it, connecting my database with python and allowing for an innteractive terminal. I have two main goals in this project which is to show why plus/minus stats are innacurate for determing player worth on the court, and then to have an interactive output that allows someone to search for a starting player on a team and then to be able to see their overall impact on the team and which areas they contribute the most to when they are on the court.


8. Discuss the experiment that you performed involving the prototype. What were the hypothe- ses and research question(s) of your experiment and what steps were taken to respond to them?

Experiment hypothesis was testing to see if plus minus stats are in concordance with points scored in a game by a player or does it depend on the team they are playing. I created a database with sql and imported two tables and then imported sql into python and queried the results in an interactive terminal. I allowed the users to choose options to query from in the output so that all they had to worry about was analyzing the results given.


9. Discuss the results of the experiment. What was learned from applying these steps which will be helpful to the completion of your project and the achieving the main goals of your research project?

Rsults proved the specific part of my hypothesis! The results I found is that the theory of scoring more points on average does not mean a higher +/- rating meaning that just because a player has a career high in a game it does not mean they contributed most on the court according to the calculation of the +/- stat. From applyying these steps I learned how to create a datbase in sql with  a part of the data set that I will be using, I used the starters for only one team here. I also was able to get my database into a python file so that I would be able to setup options that the user can choose from to pretty much answer questions I have given. I also then displayed results in the terminal for the user to analyze themselves and come up with their own conclusions.

10. How did you explain and visualize your results from your experiment so that they could be understood by those who are not in your field of research? Explain how these visualizations could be used in your research project to help explain its foundations.

I visualized them with a comparison in the terminal but I would like to visualize them with a statistical graph.
The visualization I displayed in the output of my experiment showed the data but the user still had to describe what it meant for them to get an understanding of why the question was asked. I would like to display in the future what I know is the outcome of individual players specialties while displaying a linear model to show that my results are significant and backed by evidence.
11. What ethical concerns are involved with your research? How will you recognize them and how will you handle them once they are apparent?

One ethical concern is this is these players own data and preformance enhancing data has its ups and downs in sports and I will be able to recognize them once the predictive stage of my experment is doen as I would like to use my data to predict future outcomes and tendancies but I also have to realize the future is the future and no matter what there will always be an outside factor, could be small or large that will influence my data so I just have to try and control it best I can.


12. What are the next steps to develop and complete your research project.

There are several areas like I would like to upgrade with my project. I beleive I have a good foundation starting point on a small scale for my porject. The first change I would like to make is to use a different more relevant database than sql, which is nosql. Upgrading to nosql will make my project look better for companies and employers looking at it as it will give me knowledge of another database and just broaden my skills overall. I would also like to upgrade the dataset by putting it to a scope of all 30 NBA teams with the inclusion of at least 5 players per team, one per position . Having a larger databsse allows me to speak for all the teams in the nba and allows me to make the most comparisons I can when determining player value because every team plays eachother in a season, so it makes sense to me to include all teams. Another part I would like to upgrade is my user-friendly terminal output. Keeping the same functionality where the user needs to know no database commands is vital to me. To keep this functionality I will continue to implement options in the termianl where I would like the user to select a team and then a player from that team displaying their position and some statistic that shows their value. To get this answer of a players value is where my work behind the scenes performing a statistical analysis comes in. I would like to see correlations between points socred or assists passed or rebounds grabbed by comparing those stats with the hand tracking data that is obtained for the motion cameras. With these comparisons I hypothesize that I will see discrepensies from the +/- statistic and players efficiency with the ball and how that helps their team score which I believe will give a better way to describe a players value to a team. When that is concluded I would then be able to show models of significance that show how the plus/minus stat is innacurate and be able to see player tendancies with the ball and how those tendancies each game contribute to wins or losses to then display how good a player is in an area.
```
---

(Did you remember to add your name and GitHub account name and date to the top of this document?)
