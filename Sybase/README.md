# DBQuery
Helper Query for all database like sqlserver, mysql, oracle, postgresql, sybase, dynamo db, mongodb

### Table of Contents

| No. | Topics |
| --- | --------- |
|   | **Date Time Query** |
|1  | [Convert date string to datetime format](#convert-date-string-to-datetime-format) |
|2  | [Add a day in current date](#Add-a-day-in-current-date) |


## Date Time Query

1. ### Convert date string to datetime format
``` r
SELECT CONVERT(DATETIME, '2022-05-06', 103)
```

2. ### Add a day in current date
``` r
SELECT DATEADD(dd, 1,  '2022-05-06')
```