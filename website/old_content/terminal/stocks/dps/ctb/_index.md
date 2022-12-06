```
usage: ctb [-n NUM] [--export {csv,json,xlsx}] [-h]
```

Request a list of stocks that have the highest cost to borrow [Source: Interactive Broker]

```
optional arguments:
  -n NUMBER, --number NUMBER
                        Number of records to retrieve. (default: 20)
  --raw                 Print raw data. (default: False)
  -h, --help            show this help message (default: False)
  --export EXPORT       Export raw data into csv, json, xlsx (default: )
  --source {ibkr,stocksera}
                        Data source to select from (default: ibkr)
```

Example:
```
2022 Apr 07, 09:47 (�) /stocks/dps/ $ ctb
      Highest Cost to Borrow
┌─────────┬───────────┬───────────┐
│ Symbol  │ Fees      │ Available │
├─────────┼───────────┼───────────┤
│ PIK     │ 457.4402% │ 7000      │
├─────────┼───────────┼───────────┤
│ EVTL    │ 413.7294% │ 10000     │
├─────────┼───────────┼───────────┤
│ CELZ    │ 330.9411% │ 100000    │
├─────────┼───────────┼───────────┤
│ DRCT    │ 304.9628% │ 300000    │
├─────────┼───────────┼───────────┤
│ MYNZ    │ 291.8163% │ 3000      │
├─────────┼───────────┼───────────┤
│ DCFC    │ 279.0673% │ 10000     │
├─────────┼───────────┼───────────┤
│ FGFPP   │ 278.422%  │ 8000      │
├─────────┼───────────┼───────────┤
│ ZTEK    │ 250.0307% │ 75000     │
├─────────┼───────────┼───────────┤
│ FRGE    │ 245.1883% │ 700       │
├─────────┼───────────┼───────────┤
│ SATL    │ 240.7341% │ 500       │
├─────────┼───────────┼───────────┤
│ ARMR    │ 240.5414% │ 5000      │
├─────────┼───────────┼───────────┤
│ PILL    │ 223.538%  │ 55000     │
├─────────┼───────────┼───────────┤
│ ARQQ    │ 217.3978% │ 3000      │
├─────────┼───────────┼───────────┤
│ NRSN    │ 216.9888% │ 6000      │
├─────────┼───────────┼───────────┤
│ ZIONL   │ 215.2871% │ 35000     │
├─────────┼───────────┼───────────┤
│ BLBX    │ 213.441%  │ 15000     │
├─────────┼───────────┼───────────┤
│ WINSF   │ 212.907%  │ 10000     │
├─────────┼───────────┼───────────┤
│ SKYH    │ 206.7746% │ 25000     │
├─────────┼───────────┼───────────┤
│ SOHON   │ 205.1096% │ 40000     │
├─────────┼───────────┼───────────┤
│ MH PRA  │ 202.1235% │ 100000    │
└─────────┴───────────┴───────────┘
```