# Исследование данных о продажах игр (ЯП)

### Цели проекта

- Провести анализ данных из открытых источников о продажах игр, оценках пользователей и экспертов, жанров и платформ
- Выявить закономерности, определяющие коммерческую успешность игры:
    1. Зависимость продаж от региона.
    2. Зависимость продаж от платформы.
    3. Зависимость продаж от жанра.
    4. Зависимость продаж от установленного рейтинга ESRB.

### Задачи проекта

1. Изучение общей информации о данных  
2. Подготовка данных и генерация новых признаков  
3. Исследовательский анализ данных  
    3.1 Выбор актуальных игровых платформ и периода релиза игр  
    3.2 Исследование продаж по актуальным платформам  
    3.3 Анализ влияния отзывов пользователей и критиков на продажи  
    3.4 Анализ влияния жанра игры на продажи  
4. Опрределение портрета пользователя каждого региона  
5. Проверка статистических гипотез  
    5.1 Средние пользовательские рейтинги платформ Xbox One и PC  
    5.2 Средние пользовательские рейтинги жанров Action и Sports.  

### Итоги

В рамках исследования была проведена работа с данными по продажам игр до 2016 года:
* была осуществлена предобработка данных - все данные были проверены на соответствие по типам данных, на отсутствие дубликатов, проведена работа по восстановлению пропусков данных, также в таблицу были внесены дополнительные столбцы, требуемые для проведения исслдования
* был проведен исследовательский анализ - выявлен актуальный период анализа (2013 - 2016 г), выявлены ведущие платформы и популярные жанры, а также соответствие продаж игр оценкам пользователей и критиков
* был составлен обобщенный портрет пользователя для каждого региона с его сецифическими предпочтениями при покупке игр
* были проверены гипотезы по пользоваетльским рейтингам двух платформ и двух жанров, которые показали, что рейтинги по платформам и жанрам статистически отличаются друг от друга

В качестве рекомендаций по планированию рекламной кампании на 2017 год можно выделить следующее:
* ключевыми платформами для европейского и американского рынка оказываются платформы Microsoft и Sony (при этом платформы новго поколения все больше и больше вытесняют предыдущее); для японского рынка основными платформами оказываются платформы Sony и Nintendo (при этом платформы разных поколений продолжают сосуществовать друг с другом)
* ключевыми жанрами по продажам конкретной игры оказываются для Европы и Америки жанры __shooter__ и __sports__, а для Японии - __role-playing__ и __fighting__
* на европейском рынке пользоваатели склонны покупать игры с более "взрослым" рейтингом ESBR, чем на американском, при этом в Японии оказывается не актуальным американский возрастной рейтинг ESBR, т.к. значительная часть игр выпускается для японского рынка и получает только свой внутренний рейтинг
* ориентироваться на оценки пользовтелей не рекомендуется, посколько корреляция оценок пользователей с продажами выражена слабо, а елси выражена, то обратная
* ориентироваться на оценки критики необходимо осторожно, поскольку прямая корреляция есть, однако выражена недостаточно сильно

### Используемый стек инструментов

- Python
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook