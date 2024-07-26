Info 2201 Final Project

# Project Overview
For this project, I analyzed the 4 front runners from the 2023-2024 season MVP race regular season performance and compared their regular season performances, which put them in the conversation for MVP in the first place. I wanted to see how much their play fluctuated during the season and how well their play impacted their team as well as how well their play made a case for them to win the MVP.
I used Moneypuck (https://moneypuck.com/index.html) a source that utilizes more than surface statistics, I looked into statistics crossing all situations (5v5, 5v4, 4v5, etc): 'season', 'name', 'team', 'position', 'situation', 'games_played', 'icetime', 'shifts', 'OnIce_F_goals', 'OnIce_F_shotAttempts', 'penalityMinutesDrawn', 'I_F_shifts', 'onIce_corsiPercentage', 'offIce_corsiPercentage', 'onIce_fenwickPercentage', 'offIce_fenwickPercentage','I_F_primaryAssists', 'I_F_secondaryAssists', 'I_F_points', 'I_F_goals', 'I_F_hits', 'I_F_mediumDangerShots', 'I_F_highDangerShots', 'I_F_mediumDangerGoals', 'I_F_highDangerGoals', 'I_F_oZoneShiftStarts', 'I_F_dZoneShiftStarts', and 'I_F_neutralZoneShiftStarts'.
With Moneypuck's wealth of data, I could get a good look into each MVP finalist who played in the 2023-2024 season and their relative statistics. 

# Data Source
For this project, I gathered my data from Moneypuck, primarily the Data page, where I found skater data for the 2023-2024 season. The Moneypuck Data Page.(https://moneypuck.com/data.htm)

The data is in CSV format, available with the 2023-2024 regular season statistics for all skaters that saw ice time. The CSV provides me with statistics ranging from Games played to adjusted and expected statistics such as expected goals and expected shots on goal. 

Pros: Easy access and publicly available to all. Updated with data from every season for every player, every team, and every metric. 

Cons: Less historical data, the data only dates back to the 2008-2009 season. Potentially an overload of data and metrics depending on the case and the usage.

# Data Pulling
I gathered my data for this analysis from the Moneypuck website, navigating to the data tab and downloading the relevant skater CSV files to pursue my analysis. (https://moneypuck.com/data.htm)

I downloaded the data directly from the website where it was already in CSV format. To do this I needed to navigate to the data page, select the relevant CSV files for regular season statistics, and use the download options provided on the site to export the data.

# Data Cleaning: 
During the cleaning process, I ended up making decisions that shaped the whole analysis. 

I first ran my CSV file to see what metrics and columns I wanted to move on without and to see what was relevant to my analysis. The initial running of the CSV pushed out 4620 rows and 154 columns, more than enough data than I would need. I removed unnecessary statistics such as expected statistics and adjusted statistics, I also decided to only use metrics that would be relevant for all four MVP candidates and would not benefit one player over the other three. Additionally, I addressed formatting issues and ensured that the data was properly structured for the analysis I was conducting.

Selected: The metrics that I selected were key performance metrics. Those metrics include but are not limited to, situation, games played, ice time, shifts, On Ice for Goals, On Ice For Shot Attempts, penalty Minutes Drawn, On Ice Corsi Percentage', Primary Assists, Secondary Assists, Points, Goals, Hits, Medium Danger Shots, High Danger Shots, Medium Danger Goals, HDanger Goals, Offensive Zone Shift Starts, Defensive Zone Shift Starts, Neutral Zone Shift Starts.

I selected these metrics due to their relevance in evaluating the four NHL MVP candidates and their metrics, primarily in the specific context of the four-man MVP. I decided that metrics like expected and adjusted figures are relevant due to certain players benefiting more than others due to better line pairing and overall better team play.

# Reflection on Visualization:



