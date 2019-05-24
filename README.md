#NBABot Data
This repository holds historical and current team data from the NBA. It is used in NBABot's development as a resource to provide better data. Included currently is:
- Team Data (Logos, Arenas, Colors, Locations) from every NBA Champion and current NBA Team.
- League History, including Champions and MVPs.

*There is more on the way, though.*

# NBA Regular Endpoints -- Can't find all these though.
**Scoreboard**
`http://data.nba.com/data/5s/json/cms/noseason/scoreboard/__date__/games.json`
**Box Score**
`http://data.nba.com/data/5s/json/cms/noseason/game/__date__/__gameId__/boxscore.json`
**Play by Play**
`http://data.nba.com/data/5s/json/cms/noseason/game/__date__/__gameId__/pbp_all.json`
**All Teams Schedule**
`http://data.nba.com/data/10s/prod/v1/__season__/schedule.json`
**Teams Schedule**
`http://data.nba.com/data/10s/prod/v1/__season__/teams/__teamId__/schedule.json`
**Game Preview**
`http://data.nba.com/data/10s/prod/v1/__date__/__gameId___preview_article.json`
**Game Recap**
`http://data.nba.com/data/10s/prod/v1/__date__/__gameId___recap_article.json`
**Playoffs Bracket**
`http://data.nba.com/data/10s/prod/v1/__season__/playoffsBracket.json`
**Team Leaders**
`http://data.nba.com/data/10s/prod/v1/__season__/teams/__teamId__/leaders.json`
**Team Stats (Rankings by Team)**
`http://data.nba.com/data/10s/prod/v1/__season__/team_stats_rankings.json`
**Coaches List**
`http://data.nba.com/data/10s/prod/v1/__season__/coaches.json`

### Parameters Overview
- `__season__` in form of year, i.e. `2018`
- `__teamId__` in form of a string of numbers, I'll work on finding these.
- `__date__` in form of `mmddyyyy`
- `__gameId__` I'm not quite sure about, though.

