### Задание на Лабораторную работу 6. ###

Лабораторная работа №6 выполняется индивидуально или бригадами по 2 человека.

*1. Для сдачи лабораторной работы необходимо:*

  1.1. Программно реализовать алгоритм согласно варианту бригады (см. приложение А Задания) с любой рекомендуемой структурой данных (см. приложение В Задания).

  1.2. Измерить время работы алгоритма на различных наборах данных увеличивающегося размера (например, на массивах размером 100, 1000, 10000, 100000, 1000000 и т.д.). Данные можно генерировать с помощью генератора случайных чисел внутри самой программы. 

  1.3. Результаты измерения времени работы представить в отчете виде таблицы или графика. 
Отчет должен содержать состав бригады, номер варианта, краткое описание реализованного алгоритма, используемые структуры данных, разработанный исходный код.

  1.4. Выслать отчет преподавателю для предварительной проверки.

-----------------------------------------------------------------------------

Для получения оценки "Хорошо": 
* в пунтке 1.1 необходимо сделать две реализации алгоритма с использованием двух любых структур данных из приложения В Задания;
* в отчете 1.3 кроме графиков/таблиц необходимо добавить аналитическую оценку сложности реализованных вариантов алгоритмов (в нотации О(f(N))).

-----------------------------------------------------------------------------

Для получения оценки "Отлично": 
* в пунтке 1.1 необходимо сделать несколько реализаций алгоритма с использованием трех любых структур данных из приложения В Задания (по согласованию с преподавателем могут быть использованы и другие структуры данных);
* в отчете 1.3 кроме графиков/таблиц необходимо добавить аналитическую оценку сложности реализованных алгоритмов (в нотации О(f(N))) и сравнить ее с полученными экспериментальными значениями; обеспечить статистическую значимость экспериментов за счет проведения и измерения множества повторных экспериментов.

-----------------------------------------------------------------------------

*Приложение А.* Номер алгоритма для бригады расчитывается как <сумма букв в фамилиях участников бригады на русском языке> MOD 6 (остаток от деления суммы букв на 6):

0) Алгоритм сортировки пузырьком
1) Алгоритм сортировки вставкой
2) Алгоритм сортировки выбором
3) Алгоритм удаления четных чисел из массива
4) Алгоритм удаления нечетных чисел из массива
5) Алгоритм дублирования элементов в массиве (рядом с каждым элементом требуется разместить его копию)

*Приложение В.* Рекомендуемые для использования структуры данных:
* Массив (ArrayList)
* Связный список (LinkedList)
* Хэш таблица (HashMap)
* Бинарное дерево (TreeSet/PriorityQueue/Heap)
