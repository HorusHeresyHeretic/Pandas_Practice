# Сборник полезных тетрадок с практикой по Pandas и ML.

Решил навести порядок в тетрадках написанных за 2017 - выявить и схоронить годноту, собрать шпаргалки и тут мой мир рухнул! несколько студентов ворвались в мой уютный мир ламповой и хаотичной еретичной телеграмм пони и потребовали **часть 2** за ради **вкатиться в ML** - я отговаривал, но один из них напомнил мне о старой как мир [истине](http://coub.com/view/g56t9) - так что няши, вот вам продолжение на практику в Pandas, полезную годноту и несколько примеров ML на точность. 

..и поскольку в телеграмме были крики **матан не нужен - давай pandas** про матан прочитаете по ссылкам ниже. 

# Часть 1. Pandas.

*Традиционно предлагаю [годный саундтрэк для процесса](https://soundcloud.com/guilherme19952/iron-maiden-fear-of-the-dark-piano-cover). первая часть содержит тетрадки с ранее использованным фукнционалом стандартной библиотеки Pandas в рамках учебного курса ODS и [pandas best practice](https://tomaugspurger.github.io/modern-1-intro.html) от [бога Pandas](https://github.com/TomAugspurger).*

*Да простит меня [Yorko](https://github.com/Yorko) за спойлер к домашкам ODS - обещаю ничего серьёзно дальше не показывать, в конце концов домашки второго запуска по 6ой урок включительно относительно свободно гуляют по просторам сети как до, так и после ввода рестрикта.*

*По результатам общения со студентами с уверенностью могу сказать, что люди не пошли в слак ODS по причине того - что не смогли вкатиться в Pandas, пологаю это надо исправлять так, что бы к следующему запуску курса умеющих прибавилось.*  

**и полезные операции**

1. [Накодить первый датафрейм](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_DataFrame_practice.ipynb) и сделать наконец выводы о том - что это такое.
2. [Научиться добавлять новую колокнку](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_intro_basic_practice.ipynb) в датафрейм с данными из других колонок.

3. [Познакомиться с datetime64 в Pandas](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_Dataframe_Datetime_conversion_practice.ipynb) и запомнить  основные ошибки, что бы потом не повторять.
4. [Познакомиться с DS в Pandas ещё раз](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_Datetime_practice.ipynb) и запомнить разницу между bool, int, float, object и datetime.

5. [Научиться менять положение колонок](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_SortCols_Practice.ipynb) в датафрейме, на случай если будете писать собственные.
6. [Научить наконец группировать данные](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_groupby_practice.ipynb) в датафрейме или хотя бы запомнить, что это возможно.

7. [Осознать - что датафрейм это тоже ООП](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_index_telecom_practice.ipynb) и что объекты в нём также можно использовать как ООП.
8. [Посмотреть как делать свобные таблицы](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_adult_pivot_table_and_crosstab_standart_numpy_and_sort_practice.ipynb) и окончательно убедиться в том, что Pandas это тоже ООП.

9. [Разобраться как работает pd.melt и что](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_melt_and_visaul_practice.ipynb) может ройти не так если за ним не следить и юзать как метлган.
10. [Вспоминить о существовании True/False](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_testrain_indexing_true_false_practice.ipynb) и задуматься о том, как это работает в Pandas.
11. [Разобраться как работает .map() в Pandas](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_telecom_standart_practice.ipynb) и постараться не забыть половину того что сверху.
12. [Осознать, что типы данных - это очень важно](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_as_tool_for_logic_practice.ipynb) и что только ими можно как угодно крутить этим миром.

# Часть 2. Графики.

*Вкатиться в графики и процесс их построения гораздо сложнее, чем в базовые возможности кусочка стандартной бибилиотеки Paтdas, здесь всё надо трогать ручками, крутить, вертеть и запоминать в какой ситуации тетрадка строит красоту и годноту, а в какой - варп портал в сторону ока Хаоса.*

1. [Шапка Matplotlib](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_2/Pandas_matplotLib_Intro_1.ipynb) и размеры картинок в тетрадке.
2. [Интро matplotlib](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_2/Pandas_adult_visual_matplotlib_practice.ipynb) и первые картинки от matplotlib в тетрадке.

2. [x for x in data.columns if 'name' in x](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_2/Pandas_adult_visual_and_plotly_standart_practice.ipynb) в приложении к созданию графиков.
3. [pd.melt и seaborn in action titanic df](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_2/Pandas_titanic_visual_practice.ipynb) во время визаульного анализа Титаника.

4. [Визуальный анализ практических данных](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_2/Pandas_ru_python_beginners_uniques_and_visual_practice.ipynb) учимся смотреть статистику чатиков.
5. [Пробуем сделать красиво в первый раз](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_2/Pandas_ru_python_beginnes_chat_super_pearson_visual_and_t-sne_practice.ipynb) и понимаем, что красиво пока не получается.

6. [Смотрим как "красиво" делают другие](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_2/Pandas_cardio_longformat_visual_practice.ipynb) и запоминаем понятие longformat в приложении к визуальному анализу.
7. [Запоминаем как правильно выглядит t-SNE](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_2/Pandas_telecom_plotly_and_t-sne_practice.ipynb) в представлении людей, которые хотят извлечь из него оценку данных.

8. [Включаем голову, правим руки и делаем красиво](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_2/Pandas_cardio_full_visual_and_math_with_heatmaps_and_corr_maps_practice.ipynb) особое внимание уделяем созданию тепловых карт.
9. [Осваиваем полученные навыки и пробуем в t-SNE](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_2/Pandas_heatmap_adult_titanic_video_games_sales_telecom_and_some_t-sne_practice.ipynb) и понимает, что данные для t-sne нужно готовить.

10. [Наслаждаемся процессом и идём читать про t-SNE](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_2/Pandas_video_games_sales_visual_and_croossearch_practice.ipynb) -  до уровня "что такое многомерное пространство".

*Няшы, поняши и бронящи - а также приравненные к ним фанаты аниме, я бы не смог написать для вас этот гайд - если бы Yorko намеренно не оставил бы пару слепых пятен в каждом примере, который он разбирал и в которые мне пришлось упороться. Самая годнота - примеры **как строить тепловые карты** у вас есть - математикам должно хватить.*

*Всем остальным рекомендую потренироваться в построении тех графиков, смысл которых вы понимаете.* 

*Мне пришлось поломать голову для того, что бы вывалить вам пачку тетрадок - даже в той части, которая была решена Yorko, потрудитесь и вы: я намеренно оставил t-sne в части примеров кривым, как его раскаршивать я показал - но пока до вас не дойдёт идея сопоставления точек в многомерном пространстве, ваши представления t-sne будут одноцветными.*


