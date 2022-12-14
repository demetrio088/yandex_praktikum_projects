# Определение стоимости автомобилей

![](https://img.shields.io/badge/status-completed-green])

## Данные

В наличии были следующие данные об автомобилях:
- Дата скачивания анкеты из базы
- Тип автомобильного кузова
- Год регистрации автомобиля
- Тип коробки передач
- Мощность(л. с.)
- Модель автомобиля
- Пробег(км)
- Месяц регистрации автомобиля
- Тип топлива
- Марка автомобиля
- Была машина в ремонте или нет
- Дата создания анкеты
- Количество фотографий автомобиля
- Почтовый индекс владельца анкеты(пользователя)
- Дата последней активности пользователя
- Цена(евро)

## Задача

Разработать систему рекомендации стоимости автомобиля на основе его описания.

## Результаты проекта

Разработаны и протестированы рекомендательные модели. По итогам сравнения характеристик моделей по скорости работы и RMSE от наилучшей модели к наихудшей выяснили, что наименьшее и лучшее RMSE на тестовой выборке у модели LGBMRegressor с подобранными параметрами, при этом временные затраты на работу модели на уровне DecisionTreeRegressor и LinearRegression со значительно худшими параметрами RMSE(практически вдвое).

## Используемые библиотеки
*pandas*, *warnings*, *math*, *numpy*, *matplotlib*, *seaborn*, *lightgbm*, *sklearn*
