[<- back to the index](readme.md)
# 10U KRACH Rankings
Rankings generated on Sun Feb 25 07:02:38 2024.

Rank|KRACH|Subdivision|Team|GP|W|L|T|OTW|OTL|SoS|Exp Wins|Win Diff
---:|---:|:---|:---|---:|---:|---:|---:|---:|---:|---:|---:|---:
1|1097|Playoffs|[PTL](https://gamesheetstats.com/seasons/3663/teams/140791/schedule)|20|17|2|1|1|1|431|18.3|-0.0
2|1037|Playoffs|[NJ Bandits](https://gamesheetstats.com/seasons/3663/teams/140807/schedule)|3|2|0|1|0|0|313|3.3|-0.0
3|287|Playoffs|[Royals](https://gamesheetstats.com/seasons/3663/teams/140796/schedule)|14|10|4|0|2|0|180|10.9|0.0
4|268|Playoffs|[Jr Flyers Cardillo](https://gamesheetstats.com/seasons/3663/teams/140794/schedule)|16|11|5|0|1|0|226|11.9|0.0
5|127||[CP Dynamo](https://gamesheetstats.com/seasons/3663/teams/140795/schedule)|11|7|4|0|0|1|226|7.9|0.0
6|93||[STJ](https://gamesheetstats.com/seasons/3663/teams/140792/schedule)|17|5|12|0|0|2|462|5.9|0.0
7|38||[New York Islanders](https://gamesheetstats.com/seasons/3663/teams/140793/schedule)|20|6|14|0|0|1|350|6.9|0.0
8|9||[LVPY](https://gamesheetstats.com/seasons/3663/teams/140790/schedule)|21|1|20|0|1|0|365|1.9|0.0

## Predictions
Uses KRACH ratings to predict winning percentage of each team (row) against each opponent (column).
||PTL|NJ Bandits|Royals|Jr Flyers Cardillo|CP Dynamo|STJ|New York Islanders|LVPY
| --: | --: | --: | --: | --: | --: | --: | --: | --: 
|PTL|--| 51%| 79%| 80%| 90%| 92%| 97%| 99%
|NJ Bandits| 49%|--| 78%| 79%| 89%| 92%| 96%| 99%
|Royals| 21%| 22%|--| 52%| 69%| 76%| 88%| 97%
|Jr Flyers Cardillo| 20%| 21%| 48%|--| 68%| 74%| 88%| 97%
|CP Dynamo| 10%| 11%| 31%| 32%|--| 58%| 77%| 93%
|STJ|  8%|  8%| 24%| 26%| 42%|--| 71%| 91%
|New York Islanders|  3%|  4%| 12%| 12%| 23%| 29%|--| 81%
|LVPY|  1%|  1%|  3%|  3%|  7%|  9%| 19%|--

## Generation Details

Generated with command line:
```
./aghf.py update
```

| Option | Value |
| :----- | ----: |
| Start Date | 2023-09-09 |
| End Date | 2024-02-10 |
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

