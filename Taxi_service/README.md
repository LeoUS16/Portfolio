# Прогнозирование заказов такси

## Описание проекта

Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Строится модель для такого предсказания.

## Навыки и инструменты
- python
- pandas
- numpy
- seaborn
- matplotlib
- sklearn
- sklearn.model_selection.GridSearchCV
- sklearn.model_selection.TimeSeriesSplit
- sklearn.ensemble.RandomForestRegressor
- sklearn.linear_model.LinearRegression
- sklearn.metrics.mean_squared_error
- LGBMRegressor
- CatBoostRegressor

## Вывод

Целью исследования было создание модели для предсказания количества заказов такси на следующий час. В моем распоряжении были историчекие данные за полгода о заказах такси в аэропортах.
В процессе работы было рассмотрено четыре модели обучения: линейная регрессия, случайный лес, LightGBM и CatBoost. Среди этих моделей по метрике RMSE лучшей оказалась CatBoostRegressor.
