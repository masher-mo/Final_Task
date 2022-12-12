## Задача : 
### Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами
## Описание алгоритма решения:
Необходимо объявить два массива: первый и вторый такой же длины, после этого метод, в котором цикл такой же соразмерный длине массива, внутри цикла идет проверка условия ( <=3 ), если так, элемент первого массива заносится в count элемент второго массива. Переменная count чтобы попеременно переносить из первого массива во второй и без пробелов. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.

