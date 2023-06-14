## Проект по курсу "Анализ данных на Python".  

### Москва и Санкт-Петербург - две столицы, конкурирующие между собой.
В том числе - и в вопросе погодных условий. \
Вытащим исторические данные о погоде за доступный период с сайта [pogoda1.ru](https://pogoda1.ru): [метеостанции Внуково для Москвы](https://pogoda1.ru/moscow-vnukovo-airport/) и [Пулково для СПб](https://pogoda1.ru/sankt-peterburg-pulkovo-airport/).
В наличии и категориальные, и количественные признаки, а также достаточное количество наблюдений (>2к для каждого города).

Решаемая задача для машинного обучения - бинарная классификация: предсказывать по погоде, где Москва, а где Питер.

Проверка гипотез: сравнение температурного режима времен года (z-test, критерий согласия Пирсона, F-test). 

Числовая нумерация файлов (кроме README) в гитхабе соответствует этапам в [документации проекта](https://github.com/hse-econ-data-science/andan_2023/blob/main/project_rules.md).

### ГОТОВЫЕ ЭТАПЫ:
**[FAIL](https://github.com/ergosummer/cantcomeupwithaname/blob/main/FAIL.ipynb)** - без нумерации, задокументировал проблемы с [изначально заявленным датасетом](https://registry.opendata.aws/us-hiring-rates-pandemic/).

**README** - про выбор темы и общие идеи.

**[2-PARSER](https://github.com/ergosummer/cantcomeupwithaname/tree/main/2-PARSER)** - сбор данных и парсинг. Этап готов.

**[3-HANDLING-DATA](https://github.com/ergosummer/cantcomeupwithaname/tree/main/3-HANDLING-DATA)** - работа с пропусками. Этап готов.

**[4-5-NEW_PROPERTIES_AND_VISUALS](https://github.com/ergosummer/cantcomeupwithaname/tree/main/4_5-NEW_PROPERTIES_AND_VISUALS)** - создание новых признаков и визуализация. Этап готов. 

**[6-HYPOTHESIS](https://github.com/ergosummer/cantcomeupwithaname/tree/main/6_HYPOTHESIS)** - проверка гипотез. Этап готов. 

**[7-ML_CLASSIFICATION](https://github.com/ergosummer/cantcomeupwithaname/tree/main/7-ML_CLASSIFICATION)** - этап готов.

Файлы, содержащие результат парсинга и обработки датасета, лежат [здесь](https://github.com/ergosummer/cantcomeupwithaname/tree/main/data_after_scrapping). 
