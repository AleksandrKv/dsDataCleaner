# dsDataCleaner - Очистка данных (о квартирах в Москве и Московской области)

# Описание проекта
Проект выполнен в январе-феврале 2023 года в рамках обучение по программе "Data Science" в онлайн-школе "Skill Factory". Проект может быть использован в качестве шаблона по первичному исследованию набора данных, анализу и отчистке данных (подготовка данных к исследованию с использованием нейронных сетей).

Основной файл [main.ipynb](https://github.com/AleksandrKv/dsDataCleaner/blob/master/main.ipynb) содержит все необходимые комментарии и пояснения, в т.ч. постановку задач. 

Файл с исходными данными "data/dst-3.0_16_1_hh_database.csv" к заданию имеет размер более 400 Мб, поэтому на GitHub он не опубликован, его можно скачать по [ссылке](https://disk.yandex.ru/d/EmfsHjqA4tp_ZA).


# Полезные ссылки при реализации проекта
* [Git: Удаление файлов из всех коммитов](https://pro-prof.com/forums/topic/git-удаление-файлов-из-всех-коммитов)  
// java -jar bfg.jar --delete-files test.py

* [Как добавить колонку к pd.DataFrame; Представление/копия данных в DataFrameж; A value is trying to be set on a copy of a slice from a DataFrame](https://suilin.ru/post/pandas_column/)   

* Команда для вычисления хеш-суммы: certutil -hashfile "data\dst-3.0_16_1_hh_database.csv"