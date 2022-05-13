<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="ML_0"></a>ML</h1>
<p class="has-line-data" data-line-start="1" data-line-end="3">Данные были взяты из открытого источника - <a href="http://kaggle.com">kaggle.com</a><br>
BigMart Sales Data название датасета</p>
<p class="has-line-data" data-line-start="4" data-line-end="5">Краткое описание действий по шагам:</p>
<ol>
<li class="has-line-data" data-line-start="5" data-line-end="6">Импортируем нужные для работы библиотеки</li>
<li class="has-line-data" data-line-start="6" data-line-end="14">Сбор и анализ данных<br>
2.1) Загружаем данные из csv файла в pandas<br>
2.2) Выводим первые строки из созданного датафрейма<br>
2.3) Выводим количество данных и их характеристик<br>
2.4) Выводим общую информацию о содержащихся данных в датасете(признаки)<br>
2.5) Проверяем отсутсвующие значения, чтобы не упереться в неправильное обучение в дальнейшем<br>
2.6) Работаем со столбцом Item_Weight, Outlet_Size - заполняем недостающие значения<br>
2.7) Еще раз проверяем на пустые значения, убеждаемся, что их больше нет</li>
<li class="has-line-data" data-line-start="14" data-line-end="16">Анализируем данные<br>
3.1) Смотрим распределение на графике по выбранным осям и характеристикам</li>
<li class="has-line-data" data-line-start="16" data-line-end="20">Готовим данные для следующего шага<br>
4.1) Готовим этикетки<br>
4.2) Разделяем функцию и цели<br>
4.3) Разделяем данные на test и train части</li>
<li class="has-line-data" data-line-start="20" data-line-end="22">Производим машинное обучение с помощью XGBoost<br>
5.1) Производим оценку с помощью сравнения test и train результата</li>
</ol>
