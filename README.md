# Objective
Correlation Between Headshot Percentage and Player Performance:
- Aim: To investigate if players who are more proficient in aiming (indicated by headshot percentage) perform better overall in terms of win rate and K/D ratio.
- Expected Outcome: A positive correlation is anticipated, where higher headshot percentages are associated with higher win rates and K/D ratios.

## Player Performance
- Win % [win_percent]
- KAST (Kill, Assist, Survived, Traded) [*kd_ratio] 
- ACS (Average Combat Score) [score_round]
- Damage Delta per Round [damage_round]

## Discussion

Based on tracker.gg's metric for player's performance, it is based on a few players' characteristics; those being win percentage, KAST (Kill, Assist, Survived, Traded), ACS (Average Combat Score) and Damage Delta per Round. Win percentage is the percentage of wins that a player has in ranked overall. For example, if a player wins six out of ten games, the player has a 60% win percentage. KAST 

Due to the limitation of our dataset, KAST can only be calculated using KDA, omitting two factors that is Survived and Traded. Therefore, the metric that we'll be using to measure a player's performance are:

- Win percentage
- KDA ratio
- Average Combat Score
- Damage Delta per Round