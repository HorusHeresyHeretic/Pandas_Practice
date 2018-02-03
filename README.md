# nbviewer

*Viewer тетрадок встроенный в Git имеет нехорошую тенденцию отваливаться - если **sorry something went wrong. reload** пользуйтесь [nbviewer](https://nbviewer.jupyter.org/): спопируйте линк тетрадки, которую не смог открыть Git в поле (URL| GitHub username etc) и нажмите кнопокчу **Go**.*     

# Сборник полезных тетрадок с практикой по Pandas и ML.

Решил навести порядок в тетрадках написанных за 2017 - выявить и схоронить годноту, собрать шпаргалки и тут мой мир рухнул! несколько студентов ворвались в мой уютный мир ламповой и хаотичной еретичной телеграмм пони и потребовали **часть 2** за ради **вкатиться в ML** - я отговаривал, но один из них напомнил мне о старой как мир [истине](http://coub.com/view/g56t9) - так что няши, вот вам продолжение на практику в Pandas, полезную годноту и несколько примеров ML на точность. 

..и поскольку в телеграмме были крики **матан не нужен - давай pandas** про матан прочитаете по ссылкам ниже. 

# Часть 1. Pandas.

*Традиционно предлагаю [годный саундтрэк для процесса](https://soundcloud.com/guilherme19952/iron-maiden-fear-of-the-dark-piano-cover). первая часть содержит тетрадки с ранее использованным фукнционалом стандартной библиотеки Pandas в рамках учебного курса ODS и [pandas best practice](https://tomaugspurger.github.io/modern-1-intro.html) от [бога Pandas](https://github.com/TomAugspurger).*

*Да простит меня [Yorko](https://github.com/Yorko) за спойлер к домашкам ODS - обещаю ничего серьёзно дальше не показывать, в конце концов домашки второго запуска по 6ой урок включительно относительно свободно гуляют по просторам сети как до, так и после ввода рестрикта.*

*По результатам общения со студентами с уверенностью могу сказать, что люди не пошли в слак ODS по причине того - что не смогли вкатиться в Pandas, пологаю это надо исправлять так, что бы к следующему запуску курса умеющих прибавилось.*  

**полезные операции**

1. [Накодить первый датафрейм](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_DataFrame_practice.ipynb) и сделать наконец выводы о том - что это такое.
2. [Научиться добавлять новую колокнку](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_intro_basic_practice.ipynb) в датафрейм с данными из других колонок.

3. [Познакомиться с datetime64 в Pandas](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_Dataframe_Datetime_conversion_practice.ipynb) и запомнить  основные ошибки, что бы потом не повторять.
4. [Познакомиться с DS в Pandas ещё раз](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_Datetime_practice.ipynb) и запомнить разницу между bool, int, float, object и datetime.

5. [Научиться менять положение колонок](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_SortCols_Practice.ipynb) в датафрейме, на случай если будете писать собственные.
6. [Научить наконец группировать данные](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_groupby_practice.ipynb) в датафрейме или хотя бы запомнить, что это возможно.

7. [Осознать - что датафрейм это тоже ООП](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_index_telecom_practice.ipynb) и что объекты в нём также можно использовать как ООП.
8. [Посмотреть как делать свобные таблицы](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_adult_pivot_table_and_crosstab_standart_numpy_and_sort_practice.ipynb) и окончательно убедиться в том, что Pandas это тоже ООП.

9. [Разобраться как работает pd.melt и что](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_1/Pandas_melt_and_visaul_practice.ipynb) может пойти не так если за ним не следить и юзать как метлган.
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

*Няшы, поняши и броняши - а также приравненные к ним фанаты аниме, я бы не смог написать для вас этот гайд - если бы Yorko намеренно не оставил бы пару слепых пятен в каждом примере, который он разбирал и в которые мне пришлось упороться. Самая годнота - примеры **как строить тепловые карты** у вас есть - математикам должно хватить.*

*Всем остальным рекомендую потренироваться в построении тех графиков, смысл которых вы понимаете.* 

*Мне пришлось поломать голову для того, что бы вывалить вам пачку тетрадок - даже в той части, которая была решена Yorko, потрудитесь и вы: я намеренно оставил t-sne в части примеров кривым, как его раскаршивать я показал, но пока до вас не дойдёт идея сопоставления точек в многомерном пространстве - ничего не будет.*

*Да, вот ещё что - тетрадки разложены в порядке "заставь себя думать правильно", к логике учебного курса ODS имеют весьма отдалённое отношение как по содержанию, так и по хронологии. Код тоже не блещет - поскольку большая часть была написана мной, а не скопированна из чужих решений.* 

**дисклеймер**

*Если что: я не рекомендую заявлять в слаке ODS что правильно только так, как вы здесь видели, скорее всего "правильно" делать так - как пишет Yorko, а не так как я.* 

**смысл**

*Смысл происходящего в том, что я хотел ответить на самый распространнённый вопрос, который мне задали: "аааааа где начинаеться матан - без которого никак?"*.

*Так вот матан без которого никак - это простое осознание "отчего представление t-sne здесь одноцветное и правильно ли это"? Ответ на этот вопрос в любой форме позволяет вкатить в то - как работает остальное.*

# Часть 3. Machine Learning.

**щито поделать десу - не прокатит, если фильтров нет**

**Сейчас будет матан, пачка линков на полезные статьи "на почитать" в части 4.**

*Даю наглядный пример того, что именно на практике значит фраза "поготовка данных" и почему это так важно*

1. [Коофициент корреляции Пирсона без фильтра](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_3/ML_cardio_data_cleaning_filter_no_practice.ipynb) 
2. [Коофициент корреляции Пирсона с фильтром](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_3/ML_cardio_data_cleaning_filter_yes_practice.ipynb) 

*Внимательно смотрите на две картинки снизу, сопоставляете их в своей голове и задаётесь вопросом как отсутствие 1234 строк в среде 70000 величин так подвинуло коофициент корреляции условно одинаковых переменных, что даже космически далёкий от матана человек может заметить разницу.* 

*Запоминаете этот волнительны момент в своей жизни и ставите себе галочку о том, что данные нужно уметь **готовить** перед тем как скармливать их машине в рамках какого-либо алгоритма.* 

*Знание матана и глубина знаний в этом вопросе определяет - сколько фильтров и других фич вы сможете придумать для того, что бы подготовить данные.*

**Подготовка данных во многом определяет точность.**

*Т.е вместо того что бы кодить 3 строчки кода, которые построят лес - математики сидит и **думу** думает - "а что мне ещё сделать с данными на входе, что бы на выходе получить +0.1% к точности. Если математик сильный и умеет кодить - может даже длинную фукнцию написать на тему этого. Вот для этого и нужен и матан и Python.* 

3. [Святая простота]()

**Размер имеет значение - [pandas.get_dummies](http://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.get_dummies.html) наше всё**

*Я предупреждал, что волнительно важно иметь в голове представление о многономерном прострастве, если что - мы в нём работаем. Датафрейм, который содержит в себе признаки - это такой шарик ненависти и грусти, внутри которого крутиться варп воронка состоящая из значений столбцов, строк и индексов... и это пространство имеет размерность.*

*Когда мы чистим данные с помощью фильтра, например вычитая 1234 строки из 70000 - мы сокращем размерность признакова простраснтва. Однако, существет ряд вариантов, когда эту размерность наоборот нужно увеличть - добавить к размерности многомерному пространству х2-х3 возможных полей для векторов ради лорности происходящего.*

**Для этого есть специальный инструмент - dummies** 

3. [Святая простота расширения размерности](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_3/ML_df_cardio_traintest_quantitative_simple_tree.ipynb) загляни внутри и просто посмотри как это работает.

*Няши, я не знаю как мне одним словом, выражением или предложением объяснить теорию информатики и математики. Но, попробую - есть олдскульные дядьки, которые любят по максимуму свёртывать признаковое пространство фильтрам и уже потом считать - они дружат с формулами (с которыми редко когда дружил я) и могут всякое разное рассказать.*

*С другой стороны, есть мнение, что кратное увеличение полей доступных для построения векторов тоже тру. Я считаю что тру это и то и то и надо щупать ручками. Но, при этом рассуждения олдскульных дядек о влиянии мусора в данных никогда не укладывались в моей голове в рамках доступных мне знаний о соотношении сверх больших и сверх малых величин при построении модели допустимой погрешности.*

*Как эта разруха в моей голове должна объяснить вам значимость идеи расширения признакового пространства - я хз, спросите своего лектора в универе, но поверьте - это тоже работает*.

4. [Учимся строить полезный график точности](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_3/ML_df_telecom_factorize_and_standart_ml_practice_with_churn.ipynb) - тот, который в самом конце тетрадки, очень показательная вещь.

**Когда половина значений в колонках - это str**

5. [from sklearn.preprocessing import LabelEncoder](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_3/ML_traintest_label_encoder_in_action%20(1).ipynb)

*Вероятнее всего вы уже сталкивались с ситуацией, в которой несколько столбцов датафрейма содержат текст .astype(str) - например, названия улиц и вам хотелось бы использовать эти данные в своей модели т.к они являються значимыми. Специально для этих целей умные люди придумали labelencoder.

Этот божественный инструмент кодирует строки в np.array значения из которого можно использовать при построении любых моделей, поскольку после кодирования объект, к которому был применён labelencoder принимает вид int64.*

6. [Пользуйтесь, вот вам ещё пример с LabelEncoder](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_3/ML_video_game_sales_label_encoder_in_action.ipynb)

**Когда всё стало плохо - и совсем ничего не помогает**

7. [Что делать если...](https://github.com/HorusHeresyHeretic/Pandas_Practice/blob/master/Part_3/Ml_df_traintest_visual_take_a_hint_practice.ipynb)

*Тогда нужно вспомнить заветы олдскульных дядечек о необходимости сокращать выборку по максимуму, перечитать всё выше мной описанное, включить голову и задать себе вопрос о характере данных.* 

*Собственно говоря именно ради этого момента мы и учились строить графики и писать фильтры - что бы на основании анализа данных разработаь аналитическую методику, которая будет работать.*  

*В качестве заключения практической части этого гайда, я предлагаю вам потренироваться на последнем датасете и попытаться добиться лучшей точности за счёт подготовки данных, использования фильтров и любых других решений, которые вы посчиатете нужными. Что бы хорошо посчитать эту задачу (например, для того, что бы поехал pipeline)- нужно провести достаточно серьёзную работу по подготовке данных.* 

*В тетрадке есть визуальный анализ нескольких признаков, графики, пара тепловых карт и корреляционных матриц. После того как подготовите данные - попробуйте сравнить результаты подобного анализа.* 

*В подготовке данных вам поможет [важное](https://soundcloud.com/nightcorerealityreuploads/nightcore-take-a-hint) приложение.*

# Часть 4. Что почитать на ночь перед сном, утром и днём.

1. [Восстание машин](https://habrahabr.ru/post/337040/) - просто огонь!
2. [Текст и sklearn](https://habrahabr.ru/post/264339/) - в закладки на будущее.
3. [kNN](https://www.datacamp.com/community/tutorials/preprocessing-in-data-science-part-1-centering-scaling-and-knn) - для тех кто может в английский.


4. [Для тру танкистов](https://habrahabr.ru/post/319288/) - вдруг вы всё пропустили и вообще не читатель!
5. [Фильтрация строк](http://pythonr.blogspot.ru/2015/04/dataframe-pandas-strcontains.html) - дико сложная фигня как фильтровать строки в pandas.
6. [Шикарный мануал](https://alexanderdyakonov.wordpress.com/2016/08/03/python-категориальные-признаки/) - про то как работать с категориальными признаками.


7. [Решаем Титаник](https://habrahabr.ru/post/202090/) - простой пример как человек решает Титаник.
8. [Решаем Титаник](https://habrahabr.ru/post/274171/) - человек решает Титаник на 0.80383 точности.
9. [Готовим данные](https://habrahabr.ru/post/342366/) - понятная статья о том, зачем чистить данные.


10. [Свет истины](https://habrahabr.ru/post/340698/) - бог понятных комментариев о процессе анализа.


11. [SNS](https://habrahabr.ru/post/266289/) - хорошая статься про возможности seaborn.
12. [Kaggle](https://www.kaggle.com/kanncaa1/data-sciencetutorial-for-beginners) - годный data science tutorial for beginners.

*Линков получилось мало, потому что разобрать варп варонку закладок оказалось очень сложно, но и того что есть, вам должно хватить на долго. Возможно, позже добавлю ещё. Если вы дочитали это до конца, значит времени на аниме у вас осталось мало, поэтому держите [милоты](https://youtu.be/oZkPK_4qTc8) - там целый канал такого.* 

*ЗЫ официально заявлялю что все все все права на курсы ODS и сопутствующие материалы принадлежат [Yorko](https://github.com/Yorko) и его конфе. Гайд написал исключительно в ознакомительных целях и за ради подогнать ему на следующий запуск курса хоть одного толкового студента, из числа тех - кто меня заставил это делать.* 

# Второй бонус - новогодний сборник линков на гайды.

*Приходиться делать потому что в мире нет нормального браузера под 100500 закладок - а те что есть не торт.*

эпик тру годный [саундтрэк](http://coub.com/view/zjv7c) для погружения.

1. [Heat Map for Grid Search CV](https://qiita.com/bmj0114/items/8009f282c99b77780563)
2. [Evaluating Grid Search Results](https://blancas.io/sklearn-evaluation/user_guide/grid_search.html)
3. [Static Image Export in Python with Plotly](https://plot.ly/python/static-image-export/)
4. [Энтропия и деревья решений - матан и алгоритмы](https://habrahabr.ru/post/171759/)
5. [scipy.stats.entropy](https://docs.scipy.org/doc/scipy-0.19.0/reference/generated/scipy.stats.entropy.html)
6. [cross_validate and multiple metric evaluation](http://scikit-learn.org/stable/modules/cross_validation.html)
7. [Куча книжек про Python - которые можно скачать](https://yadi.sk/d/stfqXHPA3NLUrs)
8. [Актуальный список либ и фреймворков под Python](https://github.com/vinta/awesome-python)
9. [Ещё одна шпаргаkка по Markdown](https://github.com/sandino/Markdown-Cheatsheet)
10. [Подборка датасетов для тренировки](https://github.com/ismayc/pnwflights14)
11. [Руководство: Python и алгоритмическая торговля](http://habrparser.blogspot.ru/2017_06_18_archive.html)
12. [Pyparsing для новичков](https://habrahabr.ru/post/239081/)
13. [Основы парсинга с помощью Python+lxml](https://habrahabr.ru/post/220125/)
14. [Доступ к распарсенным деревьям Python](http://python-lab.ru/documentation/27/stdlib/parser.html)
15. [Как устроен парсер Python и про память](https://habrahabr.ru/post/314062/)
16. [Веб-парсинг на Ruby](https://habrahabr.ru/post/252379/)
17. [Парсинг формул в 50 строк на Python](https://habrahabr.ru/post/273253/)
18. [HTML парсер на Python](http://pythonicway.com/python-examples/python-terminal-examples/20-python-html-parser)
19. [Лексический анализ](http://ideafix.name/wp-content/uploads/2012/09/Python-14.pdf)
20. [Научная графика в Python](http://nbviewer.jupyter.org/github/whitehorn/Scientific_graphics_in_python/blob/master/P2%20Chapter%206%20Axes%20container.ipynb)
21. [Анализ Временных рядов](https://habrahabr.ru/post/210530/)
22. [Intro: Graphviz и Pydot](https://pythonhaven.wordpress.com/2009/12/09/generating_graphs_with_pydot/)
23. [Введение в GraphViz rus](http://linuxshare.ru/docs/misc/graphviz.html)
24. [Getting started with Graphviz and Python](http://matthiaseisen.com/articles/graphviz/)
25. [DataFrame и статистический анализ Pandas](https://www.8host.com/blog/ispolzovanie-paketa-pandas-v-python-3/)
26. [Хорошая презентация о Pandas от МГУшника](https://alexanderdyakonov.files.wordpress.com/2015/04/ama2015_pandas.pdf)
27. [Достойный набор лекций и учебных пособий](http://pythonr.blogspot.ru)
28. [Timeseries with pandas](http://nbviewer.jupyter.org/github/changhiskhan/talks/blob/master/pydata2012/pandas_timeseries.ipynb#Timeseries-with-pandas)
29. [pydot.Dot() Examples](https://www.programcreek.com/python/example/5579/pydot.Dot)
30. [Статья:учим Graphviz](http://livelikeapythonista.blogspot.ru/2014/03/graphviz.html)
31. [Учим Graphviz в коде](https://github.com/erocarrera/pydot/blob/master/pydot.py)
32. [DOT - FULL ENG Guide](http://www.graphviz.org/pdf/dotguide.pdf)
33. [Numpy frequent errors](https://metaphor.ethz.ch/fsdb/sam/PythonTutorial/frequent_errors.html)
34. [k-nearest-neighbor](https://pythonspot.com/en/k-nearest-neighbors/)
35. [Руководство по интроспекции на Python](https://www.ibm.com/developerworks/ru/library/l-pyint/index.html)
36. [Обучение на больших данных: Spark MLlib](https://habrahabr.ru/company/mlclass/blog/251471/)
37. [Tuning parameters of Random Forest model](https://www.analyticsvidhya.com/blog/2015/06/tuning-random-forest-model/)
38. [Forest of trees-based ensemble methods - код](https://github.com/scikit-learn/scikit-learn/blob/f3320a6f/sklearn/ensemble/forest.py#L745)
39. [Конспекты про python на русском языке Карл!](http://www.ilnurgi1.ru/docs/python/modules_user/matplotlib/)
40. [Регулярные выражения, пособие для новичков](https://habrahabr.ru/post/115825/) 
41. [Работа с текстовыми данными в scikit-learn](https://habrahabr.ru/post/266025/)
42. [Метод Главных Компонент PCA вщи со слайдами](https://bourabai.ru/cm/pca.htm)
43. [Специальные методы и атрибуты классов Python](https://www.ibm.com/developerworks/ru/library/l-python_part_7/index.html)
44. [NumPy, пособие для новичков](https://habrahabr.ru/post/121031/)
45. [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)
46. [Cвёрточная сеть классификаторов текстов](https://habrahabr.ru/post/315118/)

*Тот факт, что мне приходиться использовать гит в качестве косплея браузера для хранения всего того что было нагуглено - не вдохновляет: в среднем я генерю около 1000 закладок в квартал из которых значительная часть связана с предметной областью по причине того, что линки на аниме и анимешные куобы я храню в телеграм.*

*И по факту телега пока вне конкуренции: хром, аваст, неон и мозила так красиво данные не хранят.* 

*Возможно предстоит осваивать учебник по написанию ботов для телеграм и писать под себя.*
