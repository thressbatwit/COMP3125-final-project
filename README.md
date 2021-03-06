# COMP3125-final-project
Data Science Fundamentals project involving the 2018 Boston Red Sox season using Player Won-Loss Records

# Intro

This project is designed to analyze the 2018 Boston Red Sox season using datasets showing Player Won-Loss Records. Player Won-Loss records are statistics used to measure a baseball player's performance in the context of games. In other words, they help measure how much a certain player contributes to his team winning games, as a modern alternative to traditional pitcher wins and losses. 

Player Won-Loss records were invented by Tom Thress (my dad), and I was very interested in using their data in order to analyze what various factors contribute to a good baseball team. I chose to use these statistics to analyze the 2018 Boston Red Sox because I had recently moved to New England, and I wanted to learn more about the Red Sox history, and the 2018 team is considered one of the best baseball teams of the 2010s in many aspects.

There were several questions that I decided to look into using these datasets. Firstly, I wanted to identify the key players that contributed to the team's success in 2018. Next, I wanted to compare the Red Sox to the entire American League in 2018 and identify what particular aspects that they were good at. Finally, I wanted to compare them to the team that they beat in the World Series that year, the Los Angeles Dodgers, and identify approximately how much better the Red Sox were than the Dodgers.

All datasets were taken from www.baseball.tomthress.com


# Methods

For Parts 1 and 2, I first imported the data as a dataframe using Pandas. Then, I sorted the data based on key statistics that I wanted to highlight, and used MatPlotLib to create charts for those statistics.

For Part 3, I imported the data as a dataframe using Pandas, and split it up into two dataframes: one for the Red Sox, and one for the Dodgers. Then, I summed up the key statistics that I was looking at and used a formula to calculate the win probability for the Red Sox over the Dodgers

# Results

Part 1: The top 10 players in pWOPA (player wins above positional average) and pWORL (player wins above replacement level) were sorted and displayed to the console, in order to show which Red Sox players contributed the most wins over a. an average player at their respective position, and b. a replacement level player at their position. The top 10 players were the same on each list, but in a different order.
![image](https://user-images.githubusercontent.com/54991253/145659282-f7a003bb-55c4-428b-add5-d77287588865.png)
![image](https://user-images.githubusercontent.com/54991253/145659291-22999f36-fc99-4d98-b4f1-50d99a7183f0.png)


Part 2: The 15 American League teams were organized by net eWins for all 4 major categories: batting, baserunning, pitching, and fielding. For three out of the four categories, the Red Sox were one of the top 5 teams in the American League in net eWins in that category.

Batting: ![image](https://user-images.githubusercontent.com/54991253/145659361-1e118001-4aa4-4fb3-8b31-ebb16fef2626.png)

Baserunning: ![image](https://user-images.githubusercontent.com/54991253/145659381-1a6d87ec-d916-491e-8424-ff6ac330e4d3.png)

Pitching: ![image](https://user-images.githubusercontent.com/54991253/145659402-a53b8b30-1df5-45fb-bc9c-40634224f9c9.png)

Fielding: ![image](https://user-images.githubusercontent.com/54991253/145659427-771ae7ef-c0a6-4ee6-af9a-afda7ef403e6.png)


Part 3: Using the eWins and eLosses stats calculated for both the Red Sox and Dodgers, I was able to calcuate the probability of the Red Sox winning a single-game head-to-head matchup against the Dodgers (58.7%), as well as how many wins the Red Sox would get if they played the Dodgers for every game of a 162-game schedule (~95 wins)

# Discussion

Using alternate baseball statistics such as Baseball Player Won-Loss Records can really help gain in insight into what helps a Major League Baseball team win games. It can help a baseball statistician or even just a casual fan know what goes into a good or bad baseball team. Part one of my analysis showed which Red Sox players contributed the most to the team winning games in 2018, and the players whose performances during the course of the season excelled that of an average player at their position, or a replacement level player from the minor leagues. Part two showed what in-game factors the Red Sox excelled at compared to the rest of the league. Part 3 showed the effect of having the resources and advantages determined in parts 1 and 2, and showed how much of an estimated advantage the Red Sox had against their world series opponent.

There are many other questions that one could answer about a team, players, or even an entire league, with these statistics. Given that these stats show how much players contribute to their team winning games, they could provide an excellent base for researching some of the greatest players and teams of all time, and figuring out what made them so effective in their time. Machine learning could be used to make predictions about how certain players might be expected to perform in future seasons, and how that might be used in turn to make predictions for regular season standings and which teams make the playoffs. 
