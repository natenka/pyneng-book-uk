Вступ
========

З одного боку, книга досить базова, щоб її міг здолати будь-який бажаючий,
а з іншого боку, у книзі розглядаються всі основні теми, які дозволять зростати
самостійно. Книга не ставить за мету глибокого розгляду Python. Завдання 
книги – пояснити зрозумілою мовою основи Python та дати розуміння необхідних
інструментів для його практичного використання. Все, що розглядається в книзі,
орієнтоване на мережеве обладнання та роботу з ним. Це дозволяє відразу
використовувати у роботі мережевого інженера те, що було вивчено.
Всі приклади показуються на прикладі обладнання Cisco, але, звичайно ж,
вони застосовні для будь-якого іншого обладнання.

Для кого ця книга
~~~~~~~~~~~~~~~~~~

Для мережевих інженерів з досвідом програмування та без. Всі приклади та завдання
побудовані навколо роботи з мережевим обладнанням. Ця книга буде корисна мережевим
інженерам, які хочуть автоматизувати завдання, з якими стикаються кожен день і хотіли
зайнятися програмуванням, але не знали, з якого боку підійти.


Навіщо вчитися програмувати?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Знання програмування для мережевого інженера можна порівняти зі знанням англійської мови.
Якщо ви знаєте англійську хоча б на рівні, який дозволяє читати технічну документацію, ви відразу розширюєте свої можливості:

* доступно у кілька разів більше літератури, форумів та блогів;
* практично для будь-якого питання або проблеми досить швидко перебуває рішення, якщо ви ввели запит до Google.

Знання програмування у цьому дуже схоже. Якщо ви знаєте, наприклад Python хоча
б на базовому рівні, ви вже відкриваєте масу нових можливостей для себе. Аналогія
з англійською підходить ще й тому, що можна працювати мережевим інженером і бути добрим
фахівцем без знання англійської. Англійська просто дає додаткові можливості, але вона не є обов'язковою вимогою.


Необхідні версії ОС та Python
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Усі приклади та виведення терміналу у книзі відображаються на Debian Linux.
Мінімально необхідна версія Python – 3.7, але для більшості прикладів підійде і Python 3.6.


Приклади
~~~~~~~

Усі приклади, що використовуються у книзі, розташовуються у `репозиторії <https://github.com/natenka/pyneng-examples-exercises>`__.
Приклади, які показані в розділах книги, є навчальними. Це означає, що вони не
обов'язково показують найкращий варіант розв'язання задачі, тому що вони
засновані лише на тій інформації, що розглядалась у попередніх розділах книги.
Крім того, досить часто приклади, що давалися у розділах, розвиваються у
завданнях. Тобто, в завданнях вам потрібно буде зробити більш
універсальну, і, загалом, правильнішу версію коду. Якщо є можливість, краще
набирати код, який використовується в книзі, самостійно, або, як мінімум,
скопіювати приклади та спробувати щось у них змінити – так інформація краще
запам'ятовуватиметься. Якщо такої можливості немає, наприклад коли ви читаєте
книгу в дорозі, краще повторити приклади самостійно пізніше. У будь-якому
випадку обов'язково потрібно виконувати завдання вручну.


Завдання
~~~~~~~

Всі завдання та допоміжні файли можна отримати в тому ж репозиторії, де є
`приклади коду <https://github.com/natenka/pyneng-examples-exercises>`__,
Якщо завдання розділу мають завдання з літерами (наприклад,
5.2a), то потрібно виконати спочатку завдання без літер, а потім з літерами.
Завдання з літерами, як правило, трохи складніші за завдання без літер і
розвивають ідею у відповідному завданні без літери. Якщо виходить, краще
виконувати завдання по порядку.

`Для всіх завдань є "відповіді", а точніше варіанти рішень <https://github.com/natenka/pyneng-answers>`__.
Для кожного завдання
може бути багато правильних варіантів розв'язання. Звичайно, у відповіді краще
підглядати поменше, але вони можуть допомогти вийти зі складної ситуації.

Якщо, наприклад, ви вирішили завдання умовно у 20 рядків, а у відповіді воно
вирішено у 7 рядків, це не означає, що ви зробили неправильно. Будь-який
робочий варіант рішення – правильний. Варіанти розв'язання можна читати після
вирішення завдань. Це буде і практика читання коду, і ви зможете подивитися на
інші підходи до вирішення задачі.

Запитання
~~~~~~~

Для частини тем книги створено добірки питань:

* `Типи даних. Частина 1 <https://goo.gl/forms/xKHX5xNM8Pv5sQDf2>`__
* `Типи даних. Частина 2 <https://goo.gl/forms/igxR3ub3tQg3ycX53>`__
* `Контроль ходу програми. Частина 1 <https://goo.gl/forms/2TmGcrhG11h2SdLn1>`__
* `Контроль ходу програми. Частина 2 <https://goo.gl/forms/KZGaDquGlUmOz2kG3>`__
* `Функції та модулі. Частина 1 <https://goo.gl/forms/M1DpbdD0brVbdp1G3>`__
* `Функції та модулі. Частина 2 <https://goo.gl/forms/rNvdX9bHw8wLajJp2>`__
* `Регулярні вирази. Частина 1 <https://goo.gl/forms/5UpkJbm1dORqs4bP2>`__
* `Регулярні вирази. Частина 2 <https://goo.gl/forms/ltuOAO62yLlZkEmm1>`__
* `Бази даних <https://goo.gl/forms/wtGgmWg0vow1Cyqo1>`__

Ці питання можна використовувати як перевірки знань, так і в ролі завдань. Дуже
корисно відповідати на запитання після прочитання відповідної теми. Вони
дозволять вам згадати матеріал теми, а також побачити практично різні аспекти
роботи з Python. Постарайтеся спочатку відповісти самостійно, а потім
піддивитися відповіді в IPython з питань, у яких ви сумніваєтеся.

Презентації
~~~~~~~~~~~

Для всіх тем книги є презентації у `репозиторії <https://github.com/pyneng/all-pyneng-slides/tree/main/pyneng>`__. По ним
За ними зручно швидко переглядати інформацію та повторювати.


Формати завантаження книги
~~~~~~~~~~~~~~~~~~~~

Книгу можна завантажити у двох форматах: PDF, Epub. Вони автоматично
оновлюються, тому завжди містять однакову інформацію.


Задати питання
~~~~~~~~~~

Для обговорення книги, завдань та пов'язаних питань використовується
`Github Discussions <https://github.com/natenka/pyneng-book-uk/discussions>`__.
Всі питання, пропозиції та зауваження щодо книги також пишіть там.

