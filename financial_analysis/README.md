# Описание - Анализ убытков приложения ProcrastinatePRO+

## Данные

В наличии были следующие данные  пользователях, привлечённых с 1 мая по 27 октября 2019 года:
- Структура visits_info_short.csv:
    - User Id — уникальный идентификатор пользователя,
    - Region — страна пользователя,
    - Device — тип устройства пользователя,
    - Channel — идентификатор источника перехода,
    - Session Start — дата и время начала сессии,
    - Session End — дата и время окончания сессии.
- Структура orders_info_short.csv:
    - User Id — уникальный идентификатор пользователя,
    - Event Dt — дата и время покупки,
    - Revenue — сумма заказа.
- Структура costs_info_short.csv:
    - dt — дата проведения рекламной кампании,
    - Channel — идентификатор рекламного источника,
    - costs — расходы на эту кампанию.


## Задача

Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Задача — разобраться в причинах и помочь компании выйти в плюс

## Используемые библиотеки
*Pandas*, *Matplotlib*, *Numpy*, *Seaborn*