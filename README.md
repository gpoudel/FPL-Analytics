
# fplAnalytics
www.fplAnalytics.com


## Intorduction
www.fplanalytics.com is a hobbyist website for the lovers of the Fantasy Premier League (https://fantasy.premierleague.com/) - a fantasy football game based on English Premier League. It uses the official APIs from the site for data inputs and processes them for fantasy managers to analyze for greater insights. Other than daily updates of price rise/fall and injuries/suspensions/fitness of the players. There are many data tables, charts and visualizations to help the fantasy managers to make a better picks based on info and stats.

## Description
The main operations/tasks needed to build and keep this site alive are:
* Gathering open data directly from official FPL website (https://fantasy.premierleague.com/)
* Data Engineering (cleaning, formatting, storing, etc.)
* Data Visualization and Publishing

The FPL data set by nature is very dynamic – not only it changes during the weekends when most of the football is being played but also every moment as the participants of the game would trade players and manage their teams just like trading real stocks and managing stock portfolios all the time. Thus, the programming scripts (written in R) needed to handle constantly changing data and keep the website as updated as possible with minimum manual intervention.

All the data gathering, engineering and visualization work in this project are done in **exclusively in R language**. I have used **Python** and tools like **Microsoft Power BI** and **Tableau** for my own analysis of data and logic building but those contents are not published to the web.

Other than mentioned above, the frontend is created with **HTML, CSS, Bootstrap and JavaScript**.

## Examples
Here are some of the examples from the main site (www.fplAnalytics.com)
* [Player Status Table](https://gpoudel.github.io/gitFPL/fplBoardLive/2016/PlayerStatus.html) (Interactive Data Table)
* [Points distribution Treemap](https://gpoudel.github.io/gitFPL/fplBoardLive/2016/playerPtsTreemap.html) (Multilayered interactive treemap)
* [Transfer Anomaly detection](https://gpoudel.github.io/gitFPL/fplBoardLive/2016/TransferAnomaly.html) (Interactive Data Viz.)
* [Player's points per game per million cost](https://gpoudel.github.io/gitFPL/fplBoardLive/2016/ptsPerGamePerMillViz.html) (Intreactive Bubble Chart)

## Note
* The scripts files are not here yet, so far the repo is only used to host HTML/Javascripts contents.
* Plans to add the scripts (R, Python) used for automatic generation of web files to this repo at later stage

## Bonus
![Alt text](https://gpoudel.github.io/gitFPL/fplBoardLive/2016/fpltwitter.png "A wordcloud image created in 'R' by mining twitter for term 'FPL'")
A wordcloud image created in 'R' by mining twitter for term 'FPL' 
