# Raifhack-DS
Ссылка на соревнование https://apply.raifhack.ru/competition

Место топ20 на 19 часов 25 сентября на паблике

Скор 1,425 на паблике

Данные train уже обрезаны по признаку price_type = 1, исходник не загрузился

1) Взял только данные с price_type = 1
2) Почистил руками признак floor
3) Накинул one hot encoding на категориальные фичи
4) Потюнил параметры lightgbm при помощи библиотеки optuna
5) И на 5х10 фолдах обучил модель
6) Немного подрезал предикт сверху

Может какие-то отдельные части будут полезны.

config:
numpy '1.20.1'
pandas '1.2.4'
lightgbm '3.2.1'
sklearn '0.24.1'
re '2.2.1'
