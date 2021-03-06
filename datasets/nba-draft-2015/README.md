# NBA Draft 2015

This folder contains data behind the story [Projecting The Top 50 Players In The 2015 NBA Draft Class](http://fivethirtyeight.com/features/projecting-the-top-50-players-in-the-2015-nba-draft-class/).

`historical_projections.csv` contains historical results of the NBA draft projection model, 2001-2015.

Header | Definition
---|---------
`Player` | Player name
`Position` | The player's position going into the draft
`ID` | The player's identification code
`Draft Year` | The year the player was eligible for the NBA draft
`Projected SPM` | The model's projected statistical plus/minus over years 2-5 of the player's NBA career
`Superstar` | Probability of becoming a superstar player (1 per draft, SPM >= +3.3)
`Starter` | Probability of becoming a starting-caliber player (10 per draft, SPM >= +0.5)
`Role Player` | Probability of becoming a role player (25 per draft, SPM >= -1.4)
`Bust` | Probability of becoming a bust (everyone else, SPM < -1.4)

This dataset was scraped from [FiveThirtyEight - nba-draft-2015](https://github.com/fivethirtyeight/data/tree/master/nba-draft-2015)