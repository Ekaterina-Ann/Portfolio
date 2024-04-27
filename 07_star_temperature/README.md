# Прогнозирование температуры звезды

[ipynb](https://github.com/Ekaterina-Ann/Portfolio/blob/master/star_temperature/star_temperature.ipynb)

## Описание проекта

Необходимо разработать нейронную сеть для обсерватории. Нейросеть должна помочь предсказывать абсолютную температуру на поверхности звезды. Обучить модель можно на данных базы обсерватории, где есть характеристики уже изученных 240 звёзд.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **torch**
- sklearn.linear_model.**LinearRegression**
- **matplotlib**
- **seaborn**

import torch


## Вывод

Я загрузила и провела предобработку данных. Построила простую нейронную сеть и улучшила её при помощи Batch Normalization и Dropout. Лучший результат показала нейросеть c Batch Normalization, с 2-мя скрытыми слоями и функцией активации RELU.
