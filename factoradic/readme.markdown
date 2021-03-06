*Факториальная система счисления* длины n &mdash;
это последовательность из n десятичных чисел, в которой число стоящее на позиции i лежит в 
диапазоне [0…i]. 

Автор: Виктор Мигрин.


Ссылки:
[Википедия](https://ru.wikipedia.org/wiki/Система_счисления#Факториальная_система_счисления),
[Wikipedia](https://en.wikipedia.org/wiki/Factorial_number_system),
[OEIS](http://oeis.org/A007623),
[OEISWIKI](https://oeis.org/wiki/Factorial_numeral_system),
[Amount_of_objects_is_factorial](http://oeis.org/A000142).

Предподсчёт: O(n), где n = 19 &mdash; максимальное число,
для которого количество строк в ФСС длины n помещается в `int64_t`.

Функция `total`: O(1).

Функция `generate_all`: O(n * (n+1)!).

Функция `is_valid`: O(n).

Функция `number_by_object`: O(n).

Функция `object_by_number`: O(n).

Функция `prev`: O(n).

Функция `next`: O(n).