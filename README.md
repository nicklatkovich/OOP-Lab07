﻿Created by **NickLatkovich**

>* Модифицировать проект, созданный в предыдущем практикуме №6.
* Написать функцию-шаблон в соответствии с вариантом.
* Проверить работу функции  с int, double , пользовательским классом (для манипуляций выбрать одно из полей класса).

## Вариант 1

> Класс - Одномерный массив.
Дополнительно перегружены следующие операции:
- * - Умножение массивов;
- [] - Доступ по индексу;
- int() - Размер массива;
- == - Проверка на равенство;
- <= - Сравнение.
- << - Вывод массива

### Методы:
  * void Set(int number, int index); /*Записывает элемент с номером index значение number*/
  * void SetRand(int min, int max); /*Записывает в качестве элементов случайные числа в диапозоне [min, max]. Перегружена для int и double*/
  * int Get(int index); /*Возвращает значение элемента с номером index*/
  * int GetSize(); /*Возвращает размер массива*/
  * void Resize(int size); /*Изменяет размер массива, сохраняя предыдущие значения (новые заполняет нулями)*/
  * void print(); /*Выводит массив через cout*/

### Пользовательский класс - Вектор

#### Методы:
* void Set(int number, int index); /*Записывает в координату с номером index значение number*/
* void SetRand(int min, int max); /*Записывает в качестве координат случайные числа в диапозоне [min, max]*/
* int Get(int index); /*Возвращает значение координаты с номером index*/
* int GetSize(); /*Возвращает размерность вектора*/
* void Resize(int size); /*Изменяет размерность вектора, сохраняя предыдущие значения (новые заполняет нулями)*/
* void print(); /*Выводит вектор через cout*/
