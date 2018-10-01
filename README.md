# WUCCStats

## Background
In July 2018 the **World Ultimate Club Championships** were held in Cincinnati Ohio USA. During the championships the commentary team used an online tool written by Tom Styles called www.commentarysource.com. There was a stats person entering the team starting on offense, and every turnover, point, and halftime afterwards. In certain games the location of each pass was also recorded. 

If you are a budding statistian looking for some game data to use in a project then this data is free to use. If you do any analysis on it then I'd love to hear from you. 

## Explaination of the data structure
Each game is an array of scoredPoint objects. The example below shows a point between Grut and Wildcard from the opening game of WUCC. The score is 2-2. There were 2 turnovers in the point, 1 each. Wildcard were on D, Grut were on O. This point is from a game where passes were not being recorded. 

```
{
    "team1Name": "Grut",
    "team2Name": "Wildcard",
    "turnovers": 2,
    "startedOnOffence": "Wildcard",
    "startedOnDefence": "Grut",
    "scored": "Wildcard",
    "gameStartOnOffence": "Grut",
    "team1Score": 2,
    "team2Score": 2,
    "passes": [],
    "lastPointInHalf": false,
    "scoredBy": 2874,
    "assistBy": null,
    "team1Class": "conceded",
    "team1OorD": "D",
    "team1Turnovers": 1,
    "team2Class": "hold",
    "team2OorD": "O",
    "team2Turnovers": 1,
    "team1Passes": 0,
    "team2Passes": 0
}
```

## Games with just points, turns, and halves.

## Games with points, turns, halves, and passes.

