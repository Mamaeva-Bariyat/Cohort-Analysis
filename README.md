# Cohort Analysis
Когортный анализ ценен для бизнеса, поскольку он позволяет им понимать поведение пользователей более детально и действенно.
Первый шаг — определить когорты на основе определенной характеристики или события. Например, на платформе электронной коммерции когорты могут быть определены на основе месяца первой покупки пользователя.<p>
Описание датасета:
- Date: The specific dates of user interactions.
- New Users: The count of new users for each date.
- Returning Users: The count of users returning on each date.
- Duration Day 1: The average duration (possibly in minutes or seconds) of user interaction on their first day.
- Duration Day 7: The average duration of user interaction on their seventh day.<p>
Задачи:
- Определить тенденции в привлечении новых пользователей и удержании возвращающихся пользователей на еженедельной основе.
- Понять, как вовлеченность пользователей, на что указывает средняя продолжительность взаимодействия, развивается с первого по седьмой день использования.
- Выявить любые существенные еженедельные закономерности или аномалии в поведении и вовлеченности пользователей и исследовать потенциальные причины этих тенденций.
- Изучить взаимосвязь между удержанием пользователей (возвращающиеся пользователи) и вовлеченностью (показатели продолжительности), чтобы оценить эффективность стратегий вовлечения пользователей.
- Предоставить действенные идеи, которые могут направлять маркетинговые усилия, стратегии контента и улучшения пользовательского опыта.
 # Визуализация новых и вернувшихся пользователей с течением времени
![Trend of New and Returning Users Over Time.png](https://github.com/Mamaeva-Bariyat/Cohort-Analysis/blob/main/images/Trend%20of%20New%20and%20Returning%20Users%20Over%20Time.png)
![Trend of Duration(Day 1 and Day 7) Over Time.png](https://github.com/Mamaeva-Bariyat/Cohort-Analysis/blob/main/images/Trend%20of%20Duration%20(Day%201%20and%20Day%207)%20Over%20Time.png)
# Kорреляция между переменными:
![Correlation Matrix of Variables](https://github.com/Mamaeva-Bariyat/Cohort-Analysis/blob/main/images/Correlation%20Matrix%20of%20Variables.png)
Здесь самая сильная корреляция наблюдается между количеством новых и вернувшихся пользователей, что указывает на потенциальную тенденцию перехода новых пользователей в категорию вернувшихся.
# когортный анализ:
Для задачи когортного анализа мы сгруппируем данные по неделям года, чтобы создать когорты. Затем для каждой когорты (недели) мы рассчитаем среднее количество новых и вернувшихся пользователей, а также среднее значение "Длительности дня 1" и "Длительности дня 7". Начнем с группировки данных по неделям и расчета необходимых средних значений:
![Weekly Average jf New vs. Returning Users.png](https://github.com/Mamaeva-Bariyat/Cohort-Analysis/blob/main/images/[Weekly%20Average%20jf%20New%20vs.%20Returning%20Users.png)

![Weekly Average of Duration (Day 1 vs. Day 7).png](https://github.com/Mamaeva-Bariyat/Cohort-Analysis/blob/main/images/Weekly%20Average%20of%20Duration%20(Day%201%20vs.%20Day%207).png)








