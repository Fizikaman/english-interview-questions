# Вопросы на собеседовании frontend-разработчика на английском

20 вопросов: 17 технических и 3 о вас и вашем опыте. У каждого — формулировка на английском и русский перевод.

Это редакционная подборка, а не список вопросов конкретного работодателя.

**Примеры ответов на английском и разбор каждого вопроса — на странице роли: [brolango.ru/voprosy-na-sobesedovanii/frontend](https://brolango.ru/voprosy-na-sobesedovanii/frontend?utm_source=github&utm_medium=repo&utm_campaign=interview-questions)**

## Технические вопросы

**1. What happens between typing a URL and seeing the page?**  
Что происходит между вводом адреса и появлением страницы?

<details>
<summary>Пример ответа и разбор</summary>

> The browser resolves the domain through DNS, opens a connection with TLS and sends an HTTP request. It parses the HTML into the DOM and the CSS into the CSSOM, then builds the render tree. After layout and paint, the page appears. I usually go deeper into the step that matters for the problem, such as a slow server response.

Держите ответ как цепочку: сеть → разбор → отрисовка. Связки first, then, after that помогают не потеряться. Не перечисляйте всё подряд: покажите этапы и предложите углубиться в тот, который важен интервьюеру.

Так разобран каждый вопрос на [странице роли](https://brolango.ru/voprosy-na-sobesedovanii/frontend?utm_source=github&utm_medium=repo&utm_campaign=interview-questions).

</details>

**2. When would you use defer instead of async on a script?**  
Когда вы выберете defer, а не async для скрипта?

**3. How does CSS specificity decide which rule wins?**  
Как специфичность CSS определяет, какое правило победит?

**4. What creates a new stacking context?**  
Что создаёт новый контекст наложения?

**5. When do you choose Grid over Flexbox?**  
Когда вы выбираете Grid вместо Flexbox?

**6. Why might you prefer rem to em for font sizes?**  
Почему для размера шрифта можно предпочесть rem, а не em?

**7. How would you explain a closure in JavaScript?**  
Как бы вы объяснили замыкание в JavaScript?

**8. What decides the value of this in a function?**  
Что определяет значение this в функции?

**9. How do let, const and var differ in scope?**  
Чем отличаются let, const и var по области видимости?

**10. Why does a promise callback run before setTimeout?**  
Почему колбэк промиса выполняется раньше setTimeout?

**11. What problem does event delegation solve?**  
Какую задачу решает делегирование событий?

**12. How does prototypal inheritance work in JavaScript?**  
Как работает прототипное наследование в JavaScript?

**13. Why does a browser block some cross-origin requests?**  
Почему браузер блокирует некоторые запросы к другому источнику?

**14. How would you investigate a page that scrolls slowly?**  
Как бы вы искали причину медленной прокрутки страницы?

**15. When would you pick WebSockets over Server-Sent Events?**  
Когда вы выберете WebSockets вместо Server-Sent Events?

**16. Why connect a label element to every form input?**  
Зачем связывать элемент label с каждым полем формы?

**17. How do you hide text visually but keep it for screen readers?**  
Как скрыть текст визуально, но оставить его для экранных читалок?

## Вопросы о вас и вашем опыте

**18. How do you keep up with changes in front-end tooling?**  
Как вы следите за изменениями во фронтенд-инструментах?

**19. Tell me about an interface you shipped and what you would change.**  
Расскажите об интерфейсе, который вы выпустили, и что бы вы изменили.

**20. How do you work with a designer when a mockup is unclear?**  
Как вы работаете с дизайнером, если макет неясен?

---

[Все ответы и разбор](https://brolango.ru/voprosy-na-sobesedovanii/frontend?utm_source=github&utm_medium=repo&utm_campaign=interview-questions) · [Другие роли](README.md)
