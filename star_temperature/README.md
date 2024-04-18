# Поиск изображения по запросу

[md]()    [ipynb]()

## Описание проекта

Нам необходимо разработать нейронную сеть для обсерватории. Нейросеть должна помочь предсказывать абсолютную температуру на поверхности звезды. Обучить модель можно на данных базы обсерватории, где есть характеристики уже изученных 240 звёзд.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- nltk.stem.**WordNetLemmatizer**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.linear_model.**ElasticNet**
- sklearn.linear_model.**LinearRegression**
- **LGBMRegressor**
- **CLIP**
- **BERT**
- **ResNet18**


## Вывод

Мы загрузили и провели предобработку данных. Построили простую нейронную сеть и улучшили её при помощи Batch Normalization и Dropout. Лучший результат показала нейросеть c Batch Normalization, с 2-мя скрытыми слоями и функцией активации RELU.