# ШИФТ конкурс "Займы"
Тестовое задание от проекта ШИФТ ЦФТ  
Ноутбук проекта находится в файле [loans_voronin.ipynb](https://github.com/ArtemV0ronin/shift_loans/blob/main/loans_voronin.ipynb)  
Альтернативная [ссылка](https://colab.research.google.com/drive/1IUF3yNLfn3JurYmQ5IBqt9y_lq0HYJci#offline=true&sandboxMode=true) на Google Collab.


## Задача проекта
Командой ШИФТ ЦФТ предоставлен набор данных о клиентах с информацией о их кредитной истории в банке. Необходимо для каждого клиента предсказать бинарный таргет, который равен 1, если займ не возвращен и 0, если заемщик вернул займ.
Оценка модели будет делаться по метрике Gini:

**Gini = 2 * ROC AUC - 1**


## Используемый стек
![Static Badge](https://img.shields.io/badge/sklearn-red)
![Static Badge](https://img.shields.io/badge/LogisticRegression-red)
![Static Badge](https://img.shields.io/badge/RandomForestClassifier-red)
![Static Badge](https://img.shields.io/badge/CatBoostClassifier-red)
![Static Badge](https://img.shields.io/badge/LGBMClassifier-red)
![Static Badge](https://img.shields.io/badge/XGBClassifier-red)
![Static Badge](https://img.shields.io/badge/matplotlib-red)
![Static Badge](https://img.shields.io/badge/seaborn-red)
![Static Badge](https://img.shields.io/badge/pandas-red)
![Static Badge](https://img.shields.io/badge/numpy-red)
![Static Badge](https://img.shields.io/badge/tqdm-red)
![Static Badge](https://img.shields.io/badge/time-red)

## Итоги проекта

В результате работы было разработано несколько моделей классификации, определяющих вероятность возврата кредита. 
Лучшая метрика Gini на тесте у модели Catboost = **0.4577**.
В ходе работы было сделано:
+ EDA
+ Обработка пропусков
+ Предобработка и рекурсивное удаление фичей
+ Анализ корреляций
+ Обработка аномалий
+ Обучение моделей, подбор гиперпараметров
+ Тестирование
