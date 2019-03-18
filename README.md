# Ventana

Senior project for classifying activity levels based on wearable monitors

### Documentation

https://ventana.readthedocs.io/en/latest/

### Setup

```
pip install ventana
```

### Example

```
import pandas as pd
from ventana.sojourn import sojourn_1x

df = pd.read_csv("path")
df["sojourn_est"] = sojourn_1x(df["vertical_counts"])
```
