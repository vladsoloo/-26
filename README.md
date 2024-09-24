# -26
Соломахин В

1) Компьюютерная арифмеетика, техническая дисциплина, предметом исследования которой являются представление чисел в ЭВМ, алгоритмы вычисления элементарных функций, арифметических операций и другие, а также реализующая их аппаратура.

2) В компьютерах вещественные числа хранятся в регистрах и ячейках памяти с ограниченным количеством разрядов. Поэтому точность представления вещественных чисел является конечной, а диапозон ограничен.

3) При сложении может возникнуть ситуация, когда старшие разряды результата операции не помещаются в отведенной для него области памяти. Такая ситуация называется переполнением разрядной сетки формата числа.

4) Дробная часть числа ограничена, поэтому любое число, имеющее более трёх цифр после запятой, не может быть представлено точно: младшие цифры придётся отбрасывать.

5)  Антипереполнение — это ситуация, когда результат операции становится настолько близким к нулю, что порядок числа выходит за пределы разрядной сетки. По мнению некоторых источников, переполнение более опасно для вычислений, так как оно приводит к значительным ошибкам и некорректным результатам. Антипереполнение, хотя и вызывает неточности, обычно не столь критично для большинства задач. 

6) Антипереполнение может сделать дальнейшие вычисления невозможными, если полученный результат нужно разделить на него. 

7) Знаковый разряд несёт один бит информации, поскольку он имеет два допустимых значения: 0 и 1 

8) Примеры величин, которые по своему смыслу могут иметь только целые значения: Год рождения, Номер квартиры. 

9) Деление 

10) Временем исполнения команды, и размером операндов. 

11) Разделение в компьютере целых и вещественных (дробей) чисел даёт следующие преимущества: Экономичное использование компьютерной памяти. Целые числа занимают меньше места в памяти, чем вещественные. Например, целые числа в интервале от 0 до 255 в языке Паскаль можно хранить в переменных типа byte, которые занимают всего один байт.  Ускорение операций. Операции с целыми числами, как правило, выполняются значительно быстрее, чем с вещественными. В ядре современных процессоров реализованы только целочисленные арифметические действия, а для вещественной арифметики используется специализированный встроенный блок. Удобство в определённых задачах. Только для целых чисел определены операции деления нацело и нахождения остатка. В некоторых задачах они удобнее, чем простое деление с получением дробного (к тому же не совсем точного) результата. Например, без них не обойтись при вычислении наибольшего общего делителя двух чисел.  

12) Дискретные величины — это те, множество значений которых состоит из отдельных чисел, не сливающихся в интервалы или отрезки. Например, в большинстве случаев это будет некоторое конечное подмножество целых чисел.  
Непрерывные величины — это те, у которых множество возможных значений представляет собой непрерывный отрезок или несколько отрезков на числовой прямой. Иногда этим множеством будет вся числовая прямая. 1 
В математике переменная может быть дискретной в одних диапазонах числовой строки и непрерывной в других.  
Обоснование: в некоторых контекстах для любого значения в диапазоне, который разрешено принимать переменной, существует положительное минимальное расстояние до ближайшего другого другого допустимого значения.

13) Во-первых, непрерывность бывает разной: в точке, справа и слева от этой точки f(c+0), f(c),f(c-0) на промежутке (открытом или закрытом), на бесконечности или в ООФ  
Во-вторых,  справедливо другое: если функция непрерывна и ограничена, то такая функция необходимо стремится к пределу. 

14) Да, можно увеличить разрядность обрабатываемых чисел по сравнению с аппаратной разрядностью компьютера.

!ЗАДАЧИ!

1) 255, 999  

2) 2^16 – 1 = 65 535, 2^32 – 1 = 4 294 967 295  

3) 2^-16 =   0,0000152587890625;  1,234567  1,234568  

4) ‐32767  

5) Например, факториал числа 9, т.е. 1⋅2⋅3⋅…⋅9 = 362880 > 2^16
