# Анализ комментарией на токсичность

## Описание проекта

Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

## Навыки и инструменты
- pandas
- numpy
- nltk.corpus.nltk_stopwords
- nltk.corpus.WordNetLemmatizer
- sklearn.model_selection.KFold
- sklearn.model_selection.cross_val_score
- sklearn.model_selection.train_test_split
- sklearn.utils.shuffle
- sklearn.linear_model.LogisticRegression
- sklearn.tree.DecisionTreeClassifier
- sklearn.feature_extraction.text.TfidfVectorizer
- sklearn.metrics.f1_score
- LGBMClassifier

## Вывод

Мной была проведена обработка исходных данных, проанализированы две различные модели обучения: LogisticRegression и DecisionTreeClassifier. Лучшее значение F-1 меры показала модель LogisticRegression.
