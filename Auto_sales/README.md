# Определение стоимости автомобилей

## Описание проекта

Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля.

## Навыки и инструменты

- python
- pandas
- numpy
- seaborn
- matplotlib
- sklearn.compose.ColumnTransformer
- sklearn.pipeline
- sklearn.model_selection.GridSearchCV
- sklearn.model_selection.KFold
- sklearn.preprocessing.OrdinalEncoder
- sklearn.preprocessing.StandardScaler
- sklearn.preprocessing.OneHotEncoder
- sklearn.ensemble.RandomForestRegressor
- sklearn.linear_model.LinearRegression
- sklearn.metrics.mean_squared_error

## Вывод

Задачей являлось разработать модель обучения, которая будет помогать определить рыночную стоимость автомобиля.
При работе над проектом был проведен анализ представленных данных, исключены данные, обработаны пропуски и аномалии.
Обучены четыре разные модели обучения для выявления лучшей по следующим показателям:
- качество предсказания;
- время обучения модели;
- время предсказания модели.
Лучшей моделью по данным показателям является CatBoostRegressor, показатель качества предсказания составил 1532.2, что ниже нашего порогового значения.
