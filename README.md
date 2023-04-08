Описание программы для визуализации графиков функций
Эта программа написана на языке программирования Python и предназначена для создания графиков функций на основе уравнений, введенных пользователем.

Требования
Для работы программы необходимо наличие следующих компонентов:

Python 3.x
библиотека Matplotlib
библиотека NumPy
библиотека SymPy
Использование
Запустите программу.
Введите уравнение функции с клавиатуры в соответствии со следующими правилами:
используйте только переменную x;
используйте только стандартные математические операции (+, -, *, /);
используйте возведение в степень через двойной знак **.
Нажмите Enter, чтобы построить график.
Описание работы программы
После ввода уравнения функции, оно преобразуется в символьное выражение с помощью библиотеки SymPy. Затем создается функция, которая может быть вычислена для любого значения x. Для построения графика создается массив значений x от -10 до 10 с использованием библиотеки NumPy, и для каждого значения x вычисляется значение функции. Затем график строится с помощью библиотеки Matplotlib.

Пример использования
Введите уравнение: x**2 + 2*x - 3

График уравнения x**2 + 2*x - 3

![image](https://user-images.githubusercontent.com/130166971/230729979-a6df3563-c42e-441d-9044-1166ec95495c.png)

Авторы программы: Shadowrange
