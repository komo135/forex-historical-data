# forex historical csv data
Each symbol contains m15, m30, h1, h4, d1 data and the data length is 10 years.

# Example
```python
import pandas as pd

url = "https://raw.githubusercontent.com/komo135/forex-historical-data/main/EURUSD/EURUSDh1.csv"
df = pd.read_csv(url)

print(df.head())
```
```
                  Date      open      high       low     close  tick_volume
0  2012-11-16 00:00:00  127801.0  127835.0  127777.0  127810.0          869
1  2012-11-16 01:00:00  127809.0  127837.0  127686.0  127736.0         1408
2  2012-11-16 02:00:00  127738.0  127769.0  127706.0  127734.0         1285
3  2012-11-16 03:00:00  127738.0  127762.0  127673.0  127695.0         1210
4  2012-11-16 04:00:00  127694.0  127771.0  127641.0  127724.0         1487
```
