# **FinalTask**

## _**Задача:**_

 
 _**Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.**_

## _**Описание решения:**_
* Объявляем исходный массив строк. Объявляем пустой массив с длинной равной исходному массиву.

* Объявляем метод формирования выходного массива по условиям задачи. На вход метод принимает ранее заданные массивы. В теле метода задаем переменную счетчик, типа число, равную 0. Задаем цикл, при котором выполняется последовательный перебор массива до достижения последнего элемента массива. В рамках цикла вводим условие в соответствии с условиями задачи (длина строки <=3). В случаях выполнения условия элемент первого массива заносится во второй массив.

* Объявляем метод печати массива. На вход метод принимает второй массив, содержащий элементы, отвечающие условиям задачи. В теле метода выполняется цикл последовательного перебора массива до достижения последнего элемента массива с выводом на экран каждого элемента входного массива.
