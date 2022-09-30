# Simple Linear Regression

- Sử dụng scikit-learning để triển khai mô hình hồi quy tuyến tính đơn giản
- Tạo mô hình, đào tạo, kiểm tra và sử dụng mô hình

## Data 

[FuelConsumption.csv](FuelConsumption.csv)

Tập dữ liệu mức tiêu thụ nhiên liệu FuelConsumption.csv, trong đó có xếp hạng mức tiêu thụ nhiên liệu dành riêng cho từng kiểu xe và lượng khí thải CO2 ước tính cho các loại xe ở Canada.

- MODELYEAR e.g. 2014
- MAKE e.g. Acura
- MODEL e.g. ILX
- VEHICLE CLASS e.g. SUV
- ENGINE SIZE e.g. 4.7
- CYLINDERS e.g 6
- TRANSMISSION e.g. A6
- FUELTYPE e.g. Z
- FUEL CONSUMPTION in CITY(L/100 km) e.g. 9.9
- FUEL CONSUMPTION in HWY (L/100 km) e.g. 8.9
- FUEL CONSUMPTION COMB (L/100 km) e.g. 9.2
- FUELCONSUMPTION_COMB_MPG (L/100 km) e.g. 18
- CO2 EMISSIONS (g/km) e.g. 182 --> low --> 0 

## Importing Needed packages

```python
import matplotlib.pyplot as plt
import pandas as pd
import pylab as pl
import numpy as np
%matplotlib inline
```

### 
