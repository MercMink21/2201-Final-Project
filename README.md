Info 2201 Final Project

# Project Overview

For this project, I analyzed the 4 front runners from the 2023-2024 season MVP race regular season performance and compared their regular season performances, which put them in the conversation for MVP in the first place. I wanted to see how much their play fluctuated during the season and how well their play impacted their team as well as how well their play made a case for them to win the MVP.
I used Moneypuck (https://moneypuck.com/index.html) a free online source that utilizes more than surface statistics, I looked into statistics crossing all situations (5v5, 5v4, 4v5, etc): 'season', 'name', 'team', 'position', 'situation', 'games_played', 'icetime', 'shifts', 'OnIce_F_goals', 'OnIce_F_shotAttempts', 'penalityMinutesDrawn', 'I_F_shifts', 'onIce_corsiPercentage', 'offIce_corsiPercentage', 'onIce_fenwickPercentage', 'offIce_fenwickPercentage', 'I_F_primaryAssists', 'I_F_secondaryAssists', 'I_F_points', 'I_F_goals', 'I_F_hits', 'I_F_mediumDangerShots', 'I_F_highDangerShots', 'I_F_mediumDangerGoals', 'I_F_highDangerGoals', 'I_F_oZoneShiftStarts', 'I_F_dZoneShiftStarts', and 'I_F_neutralZoneShiftStarts'.  
With Moneypuck's wealth of data, I could get a good look into each MVP finalist who played in the 2023-2024 season and their relative statistics. 

# Data Source

For this project, I gathered my data from Moneypuck, primarily the Data page, where I found skater data for the 2023-2024 season. The Moneypuck Data Page.(https://moneypuck.com/data.htm)

The data is in CSV format, available with the 2023-2024 regular season statistics for all skaters that saw ice time. The CSV provides me with statistics ranging from Games played to adjusted and expected statistics such as expected goals and expected shots on goal. The data is primarily numerical all across the board. There is one restriction I noticed with this data set despite its depth of statistics, and that is the plus/minus metric. While the dataset does make up for it in another area such as Shots and Goals for and against when a player is on the ice, it can be somewhat nuanced.

Pros: Easy access and publicly available to all. Updated with data from every season for every player, every team, and every metric. 

Cons: Less historical data, the data only dates back to the 2008-2009 season. Potentially an overload of data and metrics depending on the case and the usage.

# Data Pulling

I gathered my data for this analysis from the Moneypuck website, navigating to the data tab and downloading the relevant skater CSV files to pursue my analysis. (https://moneypuck.com/data.htm)

I downloaded the data directly from the website where it was already in CSV format. To do this I needed to navigate to the data page, select the relevant CSV files for regular season statistics, and use the download options provided on the site to export the data.

# Data Cleaning

During the cleaning process, I ended up making decisions that shaped the whole analysis. 

I first ran my CSV file to see what metrics and columns I wanted to move on without and to see what was relevant to my analysis. The initial running of the CSV pushed out 4620 rows and 154 columns, more than enough data than I would need. I removed unnecessary statistics such as expected statistics and adjusted statistics, I also decided to only use metrics that would be relevant for all four MVP candidates and would not benefit one player over the other three. Additionally, I addressed formatting issues and ensured that the data was properly structured for the analysis I was conducting.

Selected: The metrics that I selected were key performance metrics. Those metrics include but are not limited to, situation, games played, ice time, shifts, On Ice for Goals, On Ice For Shot Attempts, penalty Minutes Drawn, On Ice Corsi Percentage', Primary Assists, Secondary Assists, Points, Goals, Hits, Medium Danger Shots, High Danger Shots, Medium Danger Goals, HDanger Goals, Offensive Zone Shift Starts, Defensive Zone Shift Starts, Neutral Zone Shift Starts.

I selected these metrics due to their relevance in evaluating the four NHL MVP candidates and their metrics, primarily in the specific context of the four-man MVP. I decided that metrics like expected and adjusted figures are relevant due to certain players benefiting more than others due to better line pairing and overall better team play.

# Reflection on Visualization

Following up with cleaned data the visualizations were able to become more clear, however, the analysis could have been more thorough in its deep dive into each player's visualizations before comparing them with others.

Comparative bar charts showing points, primary assists, and secondary assists allowed for surface-level comparison. Visuals such as the shooting chart do a good job of emphasizing the quality of offense the MVP candidates contributed to their teams, with a high volume of high and medium-danger shots and goals, setting them apart from teammates and players across the league. Other possible visuals in the future could be historical data to capture how well the candidates played this season compared to the previous seasons, this would help reveal if this was a fluke season for the individuals. Another useful visual could be comparing players to their teammates to measure how much ahead of their teammates - those that benefit from the same system and style of play - they are in various performances and statistical categories. 

# Storytelling

The analysis I did is helpful for a variety of stakeholders ranging from sports stats connoisseurs, sports analysts, fans, and commentators, all of whom would be interested in understanding MVP candidates in depth and not just the talking points. The analysis could potentially also have impacts on sports bettors, especially going into this next season for those placing future bets on potential MVP winners. Understanding players, their overall play, tendencies, and their metrics compared to other top players can play a role in betting decisions for many individuals in the fast-growing marketplace of betting. 

This analysis is also helpful in helping consumers understand the true value a player brings to their team and positions. The analysis will help consumers see and understand why some of the candidates have the metrics they do, for example, why a player has so many goals could be attributed to them being patient and taking high-quality shots rather than just ripping pucks at the net. This analysis can also do a great deal in the future when it comes to the so-called threshold of top-tier play, this past season set many benchmarks and will be used often in the future for comparison of productive seasons for players. Others should pay attention to the cleaning process, they should pay attention to using relevant statistics rather than a surplus of statistics, simply put, less is more. 






