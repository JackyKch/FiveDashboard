# Five Dashboard

## Analysis of my own 5v5 football weekly games using Data and Power BI

>### Context
As I was discovering Power BI, I quickly realized that, to get familiar with the tool, I should try to build my own model with real dimension tables and real fact tables. Thanks to the videos and stats offered by [LeFive](https://www.lefive.fr/) , I was able to collect data on my 5-aside football games and create visuals to analyze my games. 

>### Data Gathering
While thinking about creating this dashboard, my first objective was to record all the number of wins, goals and assists for each player. At the end of each game, we get videos of each goal with the scorer associated as we select on a tablet which player scored so that the scoreboard is updated while we play. We also get the full game's replay which can be useful sometimes when players forget to add their goals on the tablet.

Before gathering all the data, I designed a Power BI model that would be able to transcribe the information I needed. I tried different model designs before finding the one that was able to deliver the key indicators that I wanted to analyze.

To gather all this data, I manually enter information about games (date, field, location), players (name, footed), teams and events occuring during the game. To do so, I have different tables in a Google Sheets that I supply after every game played. And thanks to the Google Sheets connector available in Power BI Desktop, I simply refresh my dashboard everytime I add the data from a game to get the updated numbers.

>### Creating the dashboard

When creating the dashboard, I had different lines of thinking which would become the different pages in my dashboard.

- Standings:

![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/standings.png)

In this page, I wanted a simple view on the players who won the most games, the top scorers and the players with the most given assists. As I started this project in October, I couldn't get the assists for the two games played in September because they deleted the videos.

- Goal Analysis: 

![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/goal%20analysis.png)

In this second page, I wanted a focus on the goals scored during the game, see the best scorers overall and during a single game. I also took a look at the goal distribution by body parts and by quarters of the game as we usually play 1-hour games. The last visual allows me to see how much goals we scored at each game. 

- Assist Analysis: 

![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/assist%20analysis.png)

In this third page, I wanted to see the same thing as the previous page but this time with the assists.

- Match Analysis: 

![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/match%20analysis.png)

This page allows us to have a look at a specific game choosen thanks to the two slicers at the top. It gives the players of the two different teams, the individual stats of each player, the event's timeline and a little visual to see how the game evolved according to the goals scored. 

- Player Report: 

Player Report v2            |  Player Report v3
:-------------------------:|:-------------------------:
![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/player%20report_v1.png)  |  ![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/player%20report_v2.png)


The Player Report gives us an insight on how a player performs. We see various statistics on the goals scored and assists given by a player for whom I retrieved the preferred foot. Thanks to this page, we can see if a player is good with both of his feet when shooting or passing but also if this player is stronger at the beginning or the end of a game. In the most recent version, I added a table visual showing the last results for the player chosen. 

- Field Report: 

![alt text](https://github.com/JackyKch/FiveDashboard/blob/main/images/field%20report.png)

Finally, the idea for this last page came from a discussion with one of the player who said that he never performed well when playing in field number 3. Therefore, I calculated statistics by field in order to see the players with the most wins, goals and assists for each field.

