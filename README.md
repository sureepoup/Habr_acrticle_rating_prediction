# Description
В данном проекте ставилась задача по построению модели, которая будет предсказывать рейтинг статьи на ресурсе habr.com по имеющимся данным: дата, заголовок статьи, текст статьи. 

В ходе выполнения задачи был произведен разведочный анализ данных, препроцессинг и обучение моделей, а также оценка результатов обучения и детектирование аномалий.
Добавленные признаки: weekday, year, month, hour, text_lenght.
Используемые модели: Ridge Regression, Linear Regression, LightGBM.
Используемая метрика - MAE (средняя абсолютная ошибка).
Наилучшие результаты показали следующие бейзлайны
Lemmas + TF-IDF Vectorizer + categorical variables + LightGBM.
Clean text + TF-IDF Vectorizer + categorical variables + LightGBM.

Technologies: numpy, prophet, matplotlib, scipy, sklearn, lightgbm, nltk, pymorphy2, altair, re.
