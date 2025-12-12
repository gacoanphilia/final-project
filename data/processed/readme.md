|variable          |class     |description |
|:-----------------|:---------|:-----------|
|year              |int64     |season year | 
|home_team         |object    |home team |
|away_team         |object|away team
|winner            |object|winning team
tie                |object|if a tie, 'losing' team as well
|day               |object|day of week
date               |datetime64[ns]|date
time               |object|time of game start
pts_win            |int64|points by winning team
pts_loss           |int64|points by losing team
yds_win            |int64|yards by winning team
turnovers_win      |int64|turnovers by winning team
yds_loss           |int64|yards by losing team
turnovers_loss     |int64|turnovers by losing team
home_team_name     |object|home team name
home_team_city     |object|home team city
away_team_name     |object|away team name
away_team_city     |object|away team city
kickoff_time       |datetime64[ns]|kickoff time, merging date with time|
week_num           |int64|week enumeration
total              |int64|total attendance
home               |int64|home attendance
away               |int64|away attendance
attendance         |int64|weekly attendance
wins               |int64|wins 0-16
loss               |int64|losses 0-16
points_for         |int64|points offensive
points_against     |int64|points defensive
points_differential|int64|points_for-points_against
margin_of_victory  |float64|(scored-allowed)/games played
strength_of_schedule|float64|avg opponent quality measured using SRS
simple_rating      |float64|
offensive_ranking  |float64
defensive_ranking  |float64
playoffs           |object
sb_winner          |object
home_score_diff    |int64
team_tier          |category
