Написать программу, которая из имеющегося массива строк формирует массив из строк,
длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры,
либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами
Описание алгоритма решения:
Объявляем 2 массива одинаковой размерности. Используем метод, в котором цикл равен длине массива, внутри цикла находится проверка условия ( <=3 ),
если условие выполняется, то элемент первого массива заносится в переменную count элемента второго массива.
Переменная count чтобы поочередно заполнять данные из первого массива во второй. После выполнения цикла переменная count увеличивается на 1
и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца цикла.
