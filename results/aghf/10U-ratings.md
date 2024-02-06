[<- back to the index](readme.md)
# 10U KRACH Rankings
Rankings generated on Tue Feb  6 07:03:11 2024.

Rank|KRACH|Subdivision|Team|GP|W|L|T|OTW|OTL|SoS|Exp Wins|Win Diff
---:|---:|:---|:---|---:|---:|---:|---:|---:|---:|---:|---:|---:
1|1100|Playoffs|[PTL](https://gamesheetstats.com/seasons/3663/teams/140791/schedule)|19|16|2|1|1|1|454|17.3|-0.0
2|1029|Playoffs|[NJ Bandits](https://gamesheetstats.com/seasons/3663/teams/140807/schedule)|3|2|0|1|0|0|313|3.3|-0.0
3|313|Playoffs|[Jr Flyers Cardillo](https://gamesheetstats.com/seasons/3663/teams/140794/schedule)|15|11|4|0|1|0|213|11.9|0.0
4|239|Playoffs|[Royals](https://gamesheetstats.com/seasons/3663/teams/140796/schedule)|13|9|4|0|2|0|183|9.9|0.0
5|123||[CP Dynamo](https://gamesheetstats.com/seasons/3663/teams/140795/schedule)|11|7|4|0|0|1|221|7.9|0.0
6|92||[STJ](https://gamesheetstats.com/seasons/3663/teams/140792/schedule)|17|5|12|0|0|2|464|5.9|0.0
7|37||[New York Islanders](https://gamesheetstats.com/seasons/3663/teams/140793/schedule)|20|6|14|0|0|1|350|6.9|0.0
8|9||[LVPY](https://gamesheetstats.com/seasons/3663/teams/140790/schedule)|20|1|19|0|1|0|332|1.9|0.0

## Predictions
Uses KRACH ratings to predict winning percentage of each team (row) against each opponent (column).
||PTL|NJ Bandits|Jr Flyers Cardillo|Royals|CP Dynamo|STJ|New York Islanders|LVPY
| --: | --: | --: | --: | --: | --: | --: | --: | --: 
|PTL|--| 52%| 78%| 82%| 90%| 92%| 97%| 99%
|NJ Bandits| 48%|--| 77%| 81%| 89%| 92%| 96%| 99%
|Jr Flyers Cardillo| 22%| 23%|--| 57%| 72%| 77%| 89%| 97%
|Royals| 18%| 19%| 43%|--| 66%| 72%| 86%| 96%
|CP Dynamo| 10%| 11%| 28%| 34%|--| 57%| 77%| 93%
|STJ|  8%|  8%| 23%| 28%| 43%|--| 71%| 91%
|New York Islanders|  3%|  4%| 11%| 14%| 23%| 29%|--| 81%
|LVPY|  1%|  1%|  3%|  4%|  7%|  9%| 19%|--

## Generation Details

Generated with command line:
```
./aghf.py update
```

| Option | Value |
| :----- | ----: |
| Start Date | 2023-09-09 |
| End Date | 2024-02-04 |
| Max Iterations | 200 |
| Max Ratings Diff | 1e-05 |
| Shootout Win Value | 1.00 |
| Shootout Loss Value | 0.00 |
| Tie Value | 0.50 |
| Alpha Value | 0.85 |
| Bonus Points | 0.00 |
| Fake Ties | 0 |
| Alpha Games | 1 |
| Ignore teams | __KRACH_FAKE_TEAM__ |
| Min Games Played | 4 |

