### Job_market_analysis_Analysts_and_BI
⚒️ `Стек: фактоиды, таблицы, параметр, line chart, bar chart, map chart`

Датасет HH_dataset.csv с вакансиями аналитиков, которые нашлись по какому-то ключевому запросу на сайте hh. Одна и та же вакансия может быть найдена по нескольким запросам.

> Мне нужно реализовать дашборд и ответить на вопросы с помощью графиков:
> 1. Как изменяется кол-во вакансий по месяцам?
> 2. Какие навыки наиболее востребованы работодателями?
> 3. Как распределяется кол-во вакансий по зарплатам?
> 4. Какой разброс зарплат по разным профессиям?
> 5. Какие из вакансий имеют наибольший разброс по вилке зарплат?
> 6. Зарабатывают больше с навыком Power BI или Tableau?

Описание полей:

- archived — актуальная или в архиве
- area_name — название региона 
- direction — направление аналитики для ключевого слова
- employer_name — название работодателя 
- level — уровень позиции
- name — название вакансии
- published_at — дата публикации 
- query_string — поисковый запрос
- type — тип поискового запроса (навык/профессия)
- url — ссылка на вакансию
- vacancy_id — id вакансии
- lat — координаты вакансии, широта
- lng — координаты вакансии, долгота
- employer_id — id работодателя 
- salary, net — средняя зарплата в указной вилке после вычета налога
- salary_from — минимальное значение зарплаты в вилке
- salary_gross_flag — 0 — вилка указана net, 1 — вилка указана gross.
- salary_to — максимальное значение зарплаты в вилке

> Собрала дашборд в Tableau:
> - фактоиды - произвела расчет активных вакансий и средней зарплаты;
> - линейный график - динамика вакансий за весь период;
> - аналитические таблицы - спрос вакансий по городам и ключевому направлению;
> - график карта - активные вакансии и сред. зарплата по городам.
