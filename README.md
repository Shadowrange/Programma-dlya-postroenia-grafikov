# Описание программы для визуализации графиков функций<br/>
Программа написана на языке программирования Python и предназначена для создания графиков функций на основе уравнений, введенных пользователем.<br/>
  
## Требования<br/>
Для работы программы необходимо наличие следующих компонентов:<br/>

* Python 3.x<br/>
* библиотека Matplotlib<br/>
* библиотека NumPy
* библиотека SymPy
  
## Использование<br/>
Запустите программу.<br/>
Введите крайнее левое значение функции по оси x
Введите крайнее правое значение функции по оси x
Введите уравнение функции с клавиатуры в соответствии со следующими правилами:<br/>
- используйте только переменную x;
- используйте только стандартные математические операции (+, -, *, /);
- используйте возведение в степень через двойной знак **.
- Нажмите Enter, чтобы построить график.<br/>
  
## Описание работы программы<br/>
После ввода уравнения функции, оно преобразуется в символьное выражение с помощью библиотеки SymPy. Затем создается функция, которая может быть вычислена для любого значения x. Для построения графика создается массив значений x, принадлежащий [a1; b1] с использованием библиотеки NumPy, и для каждого значения x вычисляется значение функции. Затем график строится с помощью библиотеки Matplotlib.

## Пример использования<br/>
> Введите уравнение: x**2 + 2*x - 3

> График уравнения x**2 + 2*x - 3<br/>
<br/>
![image](https://user-images.githubusercontent.com/130166971/230729979-a6df3563-c42e-441d-9044-1166ec95495c.png)  
  
Авторы программы: Shadowrange<br/>
