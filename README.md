# A System for Comparison of Regional and Central Mass Media
<p>В данном репозитории находятся файлы, содержащие программы на языке Python, в которых реализуется проект по теме "Мониторинг и сравнение тематик центральных и региональных СМИ".</p>
<p>Автор: Юлия Горшкова, студентка 2 курса группы БКЛ-193 образовательной программы "Фундаментальная и компьютерная лингвистика"</p>
<p>Научный руководитель: Эдуард Станиславович Клышинский, доцент, Школа Лингвистики НИУ ВШЭ.</p>
<br>
<h2> Файлы </h2>
<p>- W_comments_preprocessing.ipynb -- файл, в котором находится часть программы, получающая на вход два корпуса данных (которые можно найти по ссылке https://drive.google.com/drive/folders/15O7a2MoL3-oZXHm8NTm4xhl4fsEjvQC5?usp=sharing), и производящая их обработку: вычленение из сырых данных необходимой информации, лемматизация текстовых документов, удаление стоп-слов. Файл содержит множество комментариев о работе программы.</p>
<p>- Preprocessing.ipynb -- все то же самое, но без комментариев.</p>
<p>- W_comments_LDA_and_TFIDF_clustering.ipynb -- файл, содержащий основную программу для автоматичского выделения тем с примененнием 1) алгоритма LDA и 2) кластеризации TF-IDF векторов, сохранения результатов в виде таблиц тем и относящихся к ним термов, построения визуализаций. Для работы алгоритма необходимы два корпуса текстов, полученные в результате работы первой программы, которые можно найти по ссылке: https://drive.google.com/drive/folders/12QXhchwIar8YrOkcF4Ao1RIsOa0jBGIn?usp=sharing. Содержит подробные комментарии. </p>
<p>- LDA_and_TFIDF_clustering (1).ipynb -- все то же самое, но без комментариев.
<p>- Приложение_Горшкова.docx -- файл, содержащий приложение к курсовой работе (таблицы с результатами экспериментов).
<h2> Источники данных: </h2>
<h4> Региональные источники: </h4>
<p>Газета Якшур-Бодьинского района удмурсткой области "Рассвет": http://рассвет-якшур-бодья.рф</p>
<p>Советская Адыгея: https://sovetskaya-adygeya.ru</p>
<p>Газета Юга: http://www.gazetayuga.ru</p>
<p>Молодой коммунар Тула: https://mk.tula.ru</p>
<p>Волгоградская правда: https://vpravda.ru</p>
<p>Вперед: http://vperedsp.ru</p>
<p>Вечерний Челябинск: https://vecherka.su</p>
<p>Авангард: http://gazeta-avangard.ru</p>
<p>Красное прикамье: https://красноеприкамье.рф</p>
<p>Сельская правда: http://www.selpravda.ru</p>
<p>Вечерний Ставрополь: https://vechorka.ru</p>
<p>Кабардино-Балкарская правда: https://www.kbpravda.ru</p>
<p>Риск: https://risk-inform.ru</p>
<p>Вестни района: https://moyaokruga.ru/vestnikrajona/</p>
<p>Благодарненские вести: https://blag-vesti.ru</p>
<p>Чебоксарские новости: http://chebnovosti.ru</p>
<p>Починковский район: https://moyaokruga.ru/pochinki/</p>
<p>Гжатский вестник: http://gagarin-gazeta.ru</p>
<p>Курские городские известия: https://gikursk.ru</p>
<p>Вечерний волгоград: https://vv-34.ru</p>
<p>Светлый путь: https://tyumedia.ru/16/</p>
<p>Сафоновская правда: http://safonovka.ru</p>
<p>Можгинские вести: https://можгинские-вести.рф</p>
<h4> Центрльные источники: </h4>
<p>N+1: https://nplus1.ru</p>
<p>Газета.ру: https://www.gazeta.ru</p>
<p>РБК: https://www.rbc.ru</p>
