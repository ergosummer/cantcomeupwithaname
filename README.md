# Ыыыыть!)

### Проект по курсу "Анализ данных на Python". 

### Изначальный датасет для анализа:
https://registry.opendata.aws/us-hiring-rates-pandemic/ \
В процессе что-то пошло не так (см. FAIL). 
Датасет придется сменить. 

### Москва и Санкт-Петербург - две столицы, конкурирующие между собой.
### В том числе - и в вопросе погодных условий. 
Вытащим исторические данные о погоде за доступный период с сайта pogoda1.ru: метеостанции Внуково для Москвы и Пулково для СПб.
В наличии и категориальные, и количественные признаки, а также достаточное количество наблюдений (>2к для каждого города).

Очевидная задача для машинного обучения - логистическая регрессия: предсказывать по погоде, где Москва, а где Питер.

Над проверкой гипотез думаю, вероятно, будет связано со сравнением времен года. 

Числовая нумерация файлов (кроме README) в гитхабе соответствует этапам в документации проекта (github.com/hse-econ-data-science/andan_2023/blob/main/project_rules.md).

### ГОТОВЫЕ ЭТАПЫ:
FAIL - без нумерации, задокументировал проблемы с изначально заявленным датасетом.

README - про выбор темы и общие идеи.

2-PARSER - сбор данных и парсинг. Этап готов.

3-HANDLING-DATA - работа с пропусками. Этап готов.\
~~Написал цикл для заполнения НаНов, но, как выяснилось при визуализации, с ним проблема - иногда ставит очень странные значения; непонятно, почему. Буду признателен фидбеку. В принципе, можно не мудрить и заполнять НаНы средними по всей выборке (тем более, их немного), но я решил заморочиться.~~ Проблема решена.

4-5-NEW_PROPERTIES_AND_VISUALS - создание новых признаков и визуализация. Этап готов. \
~~не закончил с визуализацией. С очень странной ошибкой отказывается работать seaborn, тут тоже буду признателен фидбеку, как это починить.~~ Проблема решена.

*6-HYPOTHESIS - в последнюю очередь.*

7-ML_CLASSIFICATION - этап готов.
