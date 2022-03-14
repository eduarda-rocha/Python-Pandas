# Trabalhando com Dados

```
import pandas as pd
# pd.set_option('display.max_rows', 1000)

dataset = pd.read_csv('db.csv', sep = ';')
dataset

dataset.dtypes

dataset[['Quilometragem', 'Valor']].describe()

dataset.info()
```