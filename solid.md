SOLID, субъективное прочтение 
=============================

- SRE/DI - знаю, прочувствтвовал, мне кажутся вечными
- LSP/OSP/ISP - мне кажутся локальными приницпами, специфичными для OOП

Очень важные приницпы (SRE/DI)
------------------------------

### SRE

S - SRE - функция или класс должен делать что-то одно, признаки нарушения ("smells"): сложно подобрать название функции/классы, большое количество аргументов/настроек, много ветвлений с if. 

### DI

DI - очень помогает в случае написания тестов - если функция зависит от чего-то большого и глобального,
скорее всего эту связь можно упростить, передав в функцию ссылку или контструктор этого глобального объекта (базы данных, файла, соединения). 

Пример: https://stackoverflow.com/a/130862/1758363

Часто альтернатива тестирования объекта без DI - это mocking, всегда когда mocking есть - smell. 

Что-то тяготеющее к ООП (LSP/OSP/ISP)
-------------------------------------

### ISP

К вопросу о том, как писать хороший интерфейс, не один большой, а много маленьких. 
Часто нарушается и интерфейсы в итоге потом все равно агрегируются. Один из смежных приницпов - сначала определить интерфейс, потом писать начинку.

См. рис. 2-19 и 2-20 - тут  https://web.archive.org/web/20150906155800/http://www.objectmentor.com/resources/articles/Principles_and_Patterns.pdf  

### OSP 

- [JetBrains](https://blog.jetbrains.com/upsource/2015/08/31/what-to-look-for-in-a-code-review-solid-principles-2/)
что если есть приведжение типов (type casting) - то нарушен OSP
- [снова пример с `Shape()`](http://joelabrahamsson.com/a-simple-example-of-the-openclosed-principle/)

### LSP

Мне кажется, можно объяснить через "делайте что-то, что обеспечит переиспользование кода". Длинное, сложное, название приницпа, но весь вопрос в том, что классы должны хорошо наследоваться. Не пишите классов, которые будут наследоваться плохо. 

- [большое обсуждение в SO](https://stackoverflow.com/questions/56860/what-is-an-example-of-the-liskov-substitution-principle)
- [тут диаграммка с классом Shape()](https://github.com/alspirichev/SOLID#the-liskov-substitution-principle-lsp)


Еще ссылки
----------

- [Текст и немного кода](https://github.com/nahidulhasan/solid-principles)
- [репо на .NET, хорошие примеры](https://github.com/thangchung/clean-code-dotnet#solid)
- [Clojure](https://www.infoq.com/presentations/SOLID-Clojure/#downloadPdf/)

Три специализированных репо
---------------------------

Упоминаются выше, есть примеры кода на разных яызках программирования:

- <https://github.com/thangchung/clean-code-dotnet#solid>
- <https://github.com/alspirichev/SOLID>
- <https://github.com/nahidulhasan/solid-principles>
  
