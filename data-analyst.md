# Вопросы на собеседовании аналитика данных на английском

20 вопросов: 17 технических и 3 о вас и вашем опыте. У каждого — формулировка на английском и русский перевод.

Это редакционная подборка, а не список вопросов конкретного работодателя.

**Примеры ответов на английском и разбор каждого вопроса — на странице роли: [brolango.ru/voprosy-na-sobesedovanii/data-analyst](https://brolango.ru/voprosy-na-sobesedovanii/data-analyst?utm_source=github&utm_medium=repo&utm_campaign=interview-questions)**

## Технические вопросы

**1. How do WHERE and HAVING differ?**  
Чем WHERE отличается от HAVING?

<details>
<summary>Пример ответа и разбор</summary>

> WHERE filters rows before grouping, so it cannot use aggregate functions. HAVING filters groups after GROUP BY, so it can check conditions such as COUNT(\*) \> 10. I put row conditions in WHERE whenever possible, because the database then aggregates fewer rows. A query can use both.

Ключ — порядок выполнения: фильтр строк → группировка → фильтр групп. Совет о производительности показывает опыт. Короткий пример условия делает ответ конкретным.

Так разобран каждый вопрос на [странице роли](https://brolango.ru/voprosy-na-sobesedovanii/data-analyst?utm_source=github&utm_medium=repo&utm_campaign=interview-questions).

</details>

**2. How can a LEFT JOIN end up behaving like an inner join?**  
Как LEFT JOIN может начать вести себя как внутреннее соединение?

**3. What does COUNT(\*) count that COUNT(column) does not?**  
Что считает COUNT(\*), чего не считает COUNT(column)?

**4. How do ROW\_NUMBER, RANK and DENSE\_RANK differ?**  
Чем отличаются ROW\_NUMBER, RANK и DENSE\_RANK?

**5. How would you find duplicate records in a table?**  
Как вы найдёте дубликаты записей в таблице?

**6. How would you calculate a running total in SQL?**  
Как посчитать нарастающий итог в SQL?

**7. How would you build a cohort retention table?**  
Как построить таблицу удержания по когортам?

**8. When is the median more useful than the mean?**  
Когда медиана полезнее среднего?

**9. How would you explain a confidence interval to a manager?**  
Как объяснить менеджеру доверительный интервал?

**10. What does a p-value tell you, and what does it not?**  
Что говорит p-значение, а чего оно не говорит?

**11. How do Type I and Type II errors differ?**  
Чем ошибка первого рода отличается от ошибки второго рода?

**12. Why decide the sample size before an A/B test starts?**  
Зачем рассчитывать размер выборки до начала A/B-теста?

**13. What is a sample ratio mismatch?**  
Что такое несоответствие соотношения выборок (SRM)?

**14. Why is it risky to stop an A/B test as soon as it looks significant?**  
Почему рискованно останавливать A/B-тест, как только результат выглядит значимым?

**15. How can Simpson's paradox mislead a report?**  
Как парадокс Симпсона может исказить отчёт?

**16. How do you choose a chart for a comparison?**  
Как выбрать график для сравнения?

**17. A key metric dropped yesterday. Where do you start?**  
Ключевая метрика вчера упала. С чего вы начнёте?

## Вопросы о вас и вашем опыте

**18. Tell me about an analysis that changed a decision.**  
Расскажите об анализе, который изменил решение.

**19. Tell me about a data error you found.**  
Расскажите об ошибке в данных, которую вы нашли.

**20. How do you handle a vague request from a stakeholder?**  
Как вы работаете с размытым запросом заказчика?

---

[Все ответы и разбор](https://brolango.ru/voprosy-na-sobesedovanii/data-analyst?utm_source=github&utm_medium=repo&utm_campaign=interview-questions) · [Другие роли](README.md)
