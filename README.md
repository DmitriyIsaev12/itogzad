# itogzad
## Задача : 
### Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа.
### Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма.
### При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами
### Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. 
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. 
При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

## Способ решения:
##Создаем два массива: первый и второй одинаковой длины. 
Потом создаем метод, в котором есть цикл соразмерный длине массива, с проверкой на условие( <=3 ) 
Если условие верно -  элемент первого массива заносится в count элемент второго массива.
Переменная count создается чтобы поочередно передавать данные из первого массива во второй и избежать пробелы. 
После присвоения переменная count увеличивается на 1 и возвращается к циклу for в котором i увеличивается на 1.
И так пробегаем до конца длины массива.
