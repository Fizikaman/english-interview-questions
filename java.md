# Вопросы на собеседовании Java-разработчика на английском

20 вопросов: 17 технических и 3 о вас и вашем опыте. У каждого — формулировка на английском и русский перевод.

Это редакционная подборка, а не список вопросов конкретного работодателя.

**Примеры ответов на английском и разбор каждого вопроса — на странице роли: [brolango.ru/voprosy-na-sobesedovanii/java](https://brolango.ru/voprosy-na-sobesedovanii/java?utm_source=github&utm_medium=repo&utm_campaign=interview-questions)**

## Технические вопросы

**1. How do the JDK, the JRE and the JVM relate?**  
Как связаны JDK, JRE и JVM?

<details>
<summary>Пример ответа и разбор</summary>

> The JVM executes bytecode and manages memory. The JRE is the runtime environment: the JVM plus the standard class libraries. The JDK adds development tools such as the javac compiler and the debugger. Since Java 11, Oracle no longer ships a separate JRE, so in practice teams install a JDK or build a custom runtime with jlink.

Объясните вложенность: JVM внутри JRE, JRE внутри JDK. Уточнение про Java 11 и jlink показывает знание современной практики. Не называйте JVM компилятором — компилирует javac.

Так разобран каждый вопрос на [странице роли](https://brolango.ru/voprosy-na-sobesedovanii/java?utm_source=github&utm_medium=repo&utm_campaign=interview-questions).

</details>

**2. What does final mean for a field, a method and a class?**  
Что означает final для поля, метода и класса?

**3. When would you choose an abstract class over an interface?**  
Когда вы выберете абстрактный класс вместо интерфейса?

**4. In what order are constructors and initializers run?**  
В каком порядке выполняются конструкторы и блоки инициализации?

**5. How does overloading differ from overriding?**  
Чем перегрузка отличается от переопределения?

**6. Why must equals and hashCode be overridden together?**  
Почему equals и hashCode нужно переопределять вместе?

**7. How does a HashMap find a value by key?**  
Как HashMap находит значение по ключу?

**8. When would you use ArrayList instead of LinkedList?**  
Когда вы выберете ArrayList вместо LinkedList?

**9. What happens if you remove items from a list while iterating over it?**  
Что произойдёт, если удалять элементы списка во время обхода?

**10. Why is String immutable, and when do you use StringBuilder?**  
Почему String неизменяем и когда нужен StringBuilder?

**11. What does the volatile keyword guarantee?**  
Что гарантирует ключевое слово volatile?

**12. How does synchronized prevent a race condition?**  
Как synchronized предотвращает состояние гонки?

**13. Why use an ExecutorService instead of creating threads directly?**  
Зачем ExecutorService, если можно создавать потоки напрямую?

**14. What problem do virtual threads solve?**  
Какую задачу решают виртуальные потоки?

**15. How does the garbage collector decide what to free?**  
Как сборщик мусора решает, что освободить?

**16. How do checked and unchecked exceptions differ?**  
Чем отличаются проверяемые и непроверяемые исключения?

**17. How does try-with-resources close resources?**  
Как try-with-resources закрывает ресурсы?

## Вопросы о вас и вашем опыте

**18. Tell me about a performance problem you solved in a Java service.**  
Расскажите о проблеме производительности, которую вы решили в Java-сервисе.

**19. How do you decide when to upgrade the Java version?**  
Как вы решаете, когда обновлять версию Java?

**20. Describe a concurrency bug you had to track down.**  
Опишите ошибку многопоточности, которую вам пришлось искать.

---

[Все ответы и разбор](https://brolango.ru/voprosy-na-sobesedovanii/java?utm_source=github&utm_medium=repo&utm_campaign=interview-questions) · [Другие роли](README.md)
