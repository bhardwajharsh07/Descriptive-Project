# Descriptive-Project

## Problem Statement  

Analyse the performance metrics of football players (e.g., goals, assists, passes, tackles) from any one League to identify top performers and trends over time. The key tasks involved are:
*	Explore the distribution of goals and assists by player.
*	Analyse the correlation between player position and performance metrics.
*	Visualize trends in player performance over seasons.  

## Dataset

The dataset contains features realted to players and their performance metrices. The dataset description is as follows:
* Id: Unique identifier assigned to each player record
* Name: Full name of the football player
* Age: Age of the player during the given season
* Citizenship: Nationality or country of citizenship of the player
* Height: Player’s height measured in centimeters
* Weight: Player’s weight measured in kilograms
* Season: Football season for which the performance data is recorded
* Team: Club or team represented by the player in that season
* Jersey: Jersey number worn by the player
* Position: Playing position (e.g., Forward, Midfielder, Defender, Goalkeeper)
* YellowCards: Total number of yellow cards received in the season
* RedCards: Total number of red cards received in the season
* OffSides: Number of offsides committed by the player
* TotalGoals: Total goals scored by the player
* GoalAssists: Total assists provided by the player
* TotalShots: Total shots attempted by the player
* ShotsOnTarget: Number of shots that were on target
* GoalsConceded: Goals conceded (primarily applicable to goalkeepers)
* ShotsFaced: Number of shots faced (primarily applicable to goalkeepers)
* UpdateTime: Timestamp indicating when the record was last updated

## Approach

Cleaned and preprocessed multi-season football player data by handling missing values, removing irrelevant features, and standardizing data types.  
Engineered key performance metrics (Goals per Match, Shot Accuracy, Age Groups, Defensive and Goalkeeping features) to enhance analytical and predictive insights.  
Performed EDA and statistical testing (T-test, ANOVA, Chi-square) to identify significant performance patterns across positions and age groups.  
Trained and evaluated Linear Regression models to predict player performance, achieving high accuracy and forecasting future season outcomes.

## Outcomes

Successfully analyzed multi-season Premier League player data to identify key performance indicators influencing goals, appearances, and disciplinary behavior.  
Built Linear Regression models that achieved strong predictive performance, explaining up to 93% variance for goal scoring and 96% for goalkeeper performance.  
Statistically validated performance differences across positions and age groups using T-test, ANOVA, and Chi-square tests, confirming meaningful patterns in player behavior.  
Generated data-driven forecasts for future seasons, demonstrating the model’s practical usefulness for player evaluation and performance prediction.
