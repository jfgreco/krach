[<- back to the index](readme.md)
# 10U KRACH Rankings
Rankings generated on Wed Jan 31 07:03:34 2024.

Rank|KRACH|Subdivision|Team|GP|W|L|T|OTW|OTL|SoS|Exp Wins|Win Diff
---:|---:|:---|:---|---:|---:|---:|---:|---:|---:|---:|---:|---:
1|1055|Playoffs|[PTL](https://gamesheetstats.com/seasons/3663/teams/140791/schedule)|18|15|2|1|1|1|463|16.3|-0.0
2|1043|Playoffs|[NJ Bandits](https://gamesheetstats.com/seasons/3663/teams/140807/schedule)|3|2|0|1|0|0|306|3.3|-0.0
3|399|Playoffs|[Jr Flyers Cardillo](https://gamesheetstats.com/seasons/3663/teams/140794/schedule)|14|11|3|0|1|0|165|11.9|0.0
4|280|Playoffs|[Royals](https://gamesheetstats.com/seasons/3663/teams/140796/schedule)|13|9|4|0|2|0|203|9.9|0.0
5|139||[CP Dynamo](https://gamesheetstats.com/seasons/3663/teams/140795/schedule)|11|7|4|0|0|1|226|7.9|0.0
6|106||[STJ](https://gamesheetstats.com/seasons/3663/teams/140792/schedule)|17|5|12|0|0|2|485|5.9|0.0
7|43||[New York Islanders](https://gamesheetstats.com/seasons/3663/teams/140793/schedule)|20|6|14|0|0|1|356|6.9|0.0
8|10||[LVPY](https://gamesheetstats.com/seasons/3663/teams/140790/schedule)|20|1|19|0|1|0|352|1.9|0.0

## Predictions
Uses KRACH ratings to predict winning percentage of each team (row) against each opponent (column).
||PTL|NJ Bandits|Jr Flyers Cardillo|Royals|CP Dynamo|STJ|New York Islanders|LVPY
| --: | --: | --: | --: | --: | --: | --: | --: | --: 
|PTL|--| 50%| 73%| 79%| 88%| 91%| 96%| 99%
|NJ Bandits| 50%|--| 72%| 79%| 88%| 91%| 96%| 99%
|Jr Flyers Cardillo| 27%| 28%|--| 59%| 74%| 79%| 90%| 97%
|Royals| 21%| 21%| 41%|--| 67%| 73%| 87%| 96%
|CP Dynamo| 12%| 12%| 26%| 33%|--| 57%| 77%| 93%
|STJ|  9%|  9%| 21%| 27%| 43%|--| 71%| 91%
|New York Islanders|  4%|  4%| 10%| 13%| 23%| 29%|--| 80%
|LVPY|  1%|  1%|  3%|  4%|  7%|  9%| 20%|--

## Generation Details

Generated with command line:
```
./aghf.py update
```

| Option | Value |
| :----- | ----: |
| Start Date | 2023-09-09 |
| End Date | 2024-01-27 |
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

