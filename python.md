# Вопросы на собеседовании Python-разработчика на английском

23 вопроса: 20 технических и 3 о вас и вашем опыте. У каждого — формулировка на английском и русский перевод.

Это редакционная подборка, а не список вопросов конкретного работодателя.

**Примеры ответов на английском и разбор каждого вопроса — на странице роли: [brolango.ru/voprosy-na-sobesedovanii/python](https://brolango.ru/voprosy-na-sobesedovanii/python?utm_source=github&utm_medium=repo&utm_campaign=interview-questions)**

## Технические вопросы

**1. When would you choose a tuple over a list?**  
Когда вы выберете кортеж вместо списка?

<details>
<summary>Пример ответа и разбор</summary>

> I use a list when the sequence needs to change, and a tuple when its positions describe a fixed record. For example, coordinates can be a tuple. Tuple immutability prevents replacing its elements, but a list stored inside a tuple can still change. I choose by meaning before making performance claims.

Начните с критерия выбора, затем приведите пример и уточните границу неизменяемости. Полезная связка — I use … when …. Не обещайте, что кортеж всегда быстрее: это не объясняет, подходит ли он задаче.

Так разобран каждый вопрос на [странице роли](https://brolango.ru/voprosy-na-sobesedovanii/python?utm_source=github&utm_medium=repo&utm_campaign=interview-questions).

</details>

**2. What does \_\_init\_\_ actually initialize?**  
Что именно инициализирует \_\_init\_\_?

**3. When does a comprehension improve readability?**  
Когда comprehension делает код понятнее?

**4. How does the GIL affect thread selection?**  
Как GIL влияет на выбор потоков?

**5. How do you handle an absent dictionary key?**  
Как обработать отсутствующий ключ словаря?

**6. What remains shared after a shallow copy?**  
Что остаётся общим после поверхностного копирования?

**7. How would you explain a function decorator?**  
Как вы объясните декоратор функции?

**8. How does with manage resource cleanup?**  
Как with управляет освобождением ресурсов?

**9. When does a try statement's else block run?**  
Когда выполняется else у конструкции try?

**10. Which objects can serve as dictionary keys?**  
Какие объекты могут быть ключами словаря?

**11. When is identity different from equality?**  
Когда идентичность отличается от равенства?

**12. Why can a default list retain earlier values?**  
Почему список по умолчанию сохраняет прежние значения?

**13. How do \*args and \*\*kwargs collect arguments?**  
Как \*args и \*\*kwargs собирают аргументы?

**14. Where does a nested function look up names?**  
Где вложенная функция ищет имена?

**15. Why use a generator for streamed data?**  
Зачем использовать генератор для потока данных?

**16. Does async def make blocking work concurrent?**  
Делает ли async def блокирующую работу конкурентной?

**17. What guarantees do type annotations provide?**  
Какие гарантии дают аннотации типов?

**18. What does a virtual environment isolate?**  
Что изолирует виртуальное окружение?

**19. How do instance, class and static methods differ?**  
Чем отличаются обычный, классовый и статический методы?

**20. How would you find a minimum from CSV records?**  
Как найти минимум среди записей CSV?

## Вопросы о вас и вашем опыте

**21. Tell me about a Python service you made faster.**  
Расскажите о Python-сервисе, который вы ускорили.

**22. How do you keep a Python codebase maintainable in a team?**  
Как вы держите Python-код в команде в порядке?

**23. Why did you choose Python, and when would you pick another language?**  
Почему вы выбрали Python и когда предпочли бы другой язык?

---

[Все ответы и разбор](https://brolango.ru/voprosy-na-sobesedovanii/python?utm_source=github&utm_medium=repo&utm_campaign=interview-questions) · [Другие роли](README.md)
