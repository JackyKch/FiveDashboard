# Five Dashboard

## Analysis of my own 5v5 football weekly games using Data and Power BI

>### Context
As I was discovering Power BI, I quickly realized that, to get familiar with the tool, I should try to build my own model with real dimension tables and real fact tables. Thanks to the videos and stats offered by [LeFive](https://www.lefive.fr/) , I was able to collect data on my 5-aside football games and create visuals to analyze my games. 

>### Data Gathering
While thinking about creating this dashboard, my first objective was to record all the number of wins, goals and assists for each player. At the end of each game, we get videos of each goal with the scorer associated as we select on a tablet which player scored so that the scoreboard is updated while we play. We also get the full game's replay which can be useful sometimes when players forget to add their goals on the tablet.

To gather all this data, I manually enter information about games (date, field, location), players (name, footed), teams and events occuring during the game. To do so, I have different tables in a Google Sheets that I supply after every game played. Beforehand, I designed a Power BI model that would be able to transcribe the information I needed.

>### Creating the dashboard

When creating the dashboard, I had different lines of thinking which would become the different pages in my dashboard.

- Standings:

![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/standings.png)

In this page, I wanted a simple view on the players who won the most games, the top scorers and the players with the most given assists. As I started this project in October, I couldn't get the assists for the two games played in September because they deleted the videos.

- Goal Analysis: 

![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/goal%20analysis.png)

- Assist Analysis: 

![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/assist%20analysis.png)

- Match Analysis: 

![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/match%20analysis.png)

- Player Report: 

![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/match%20analysis.png)

- Field Report: 

![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/field%20report.png)

