Список (List)
=============

Список у Python це:

* послідовність елементів, розділених між собою комою та укладених у квадратні дужки
* змінюваний упорядкований тип даних

Приклади списків:

.. code:: python

    vlans = [10, 20, 30, 77]
    commands = ["interface Gi0/1", "ip address 10.1.1.1 255.255.255.0"]
    list3 = [1, 20, 4.0, 'word']

Створення списку за допомогою літералу:

.. code:: python

    In [1]: vlans = [10, 20, 30, 50]

.. note::

    Літерал – це вираз, який створює об'єкт.


Создание списка с помощью функции list:

.. code:: python

    In [2]: list1 = list('router')

    In [3]: print(list1)
    ['r', 'o', 'u', 't', 'e', 'r']

Індекси, зрізи
---------------

Так як список - це впорядкований тип даних, то, як і в рядках, у списках можна
звертатися до елемента за номером, робити зрізи:

.. code:: python

    In [4]: list3 = [1, 20, 4.0, 'word']

    In [5]: list3[1]
    Out[5]: 20

    In [6]: list3[1::]
    Out[6]: [20, 4.0, 'word']

    In [7]: list3[-1]
    Out[7]: 'word'

    In [8]: list3[::-1]
    Out[8]: ['word', 4.0, 20, 1]


Оскільки список є змінним типом даних, елементи списку можна змінювати:

.. code:: python

    In [13]: list3
    Out[13]: [1, 20, 4.0, 'word']

    In [14]: list3[0] = 'test'

    In [15]: list3
    Out[15]: ['test', 20, 4.0, 'word']

Можна також створювати список списків. І, як і у звичайному списку, можна
звертатися до елементів у вкладених списках:

.. code:: python

    interfaces = [['FastEthernet0/0', '15.0.15.1', 'YES', 'manual', 'up', 'up'],
                  ['FastEthernet0/1', '10.0.1.1', 'YES', 'manual', 'up', 'up'],
                  ['FastEthernet0/2', '10.0.2.1', 'YES', 'manual', 'up', 'down']]

    In [17]: interfaces[0][0]
    Out[17]: 'FastEthernet0/0'

    In [18]: interfaces[2][0]
    Out[18]: 'FastEthernet0/2'

    In [19]: interfaces[2][1]
    Out[19]: '10.0.2.1'

len, sorted
------------

Функція len повертає кількість елементів у списку:

.. code:: python

    In [1]: items = [1, 2, 3]

    In [2]: len(items)
    Out[2]: 3

Функція sorted сортує елементи списку за зростанням і повертає новий список із
відсортованими елементами:

.. code:: python

    In [1]: names = ['John', 'Michael', 'Antony']

    In [2]: sorted(names)
    Out[2]: ['Antony', 'John', 'Michael']



.. toctree::
   :maxdepth: 1
   :hidden:

   list_methods
