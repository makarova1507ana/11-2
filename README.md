# самый классный модуль maths 
## как скачать
1. скачать файл maths.h
2. переместить файл в папку с проектом
3. подключить при помощи команды #include "maths.h"
## стандарты кодирования
[правила](https://google.github.io/styleguide/cppguide.html)

## Функция для сложения двух чисел
Принимает два значения *double*
Возвращает их сумму в *double*
>```c++
>double Add(double a, double b)
>{
>	return a + b;
>}
>```
Пример использования:
>```c++
>Add(-3.7, 4)
>// ввозвращает 0.3
>```
 
## Функция для вычитания одного числа из другого
Вычитает из первого переданного значения второе
>```с++
>double Sub(double a, double b)
>{
>	return a - b;
>}
>```
Пример использования:
>```с++
>Sub(10, 5.4);
>// возвращает 4.6
>```
### Дополнительные пример:
**математическое выражение:** (2+3) - (0.1 - (-3)) 
>```с++
>// (2+3) - (0.1 - (-3))
>Sub(Add(2,3),Sub(0.1, -3));
>// возвращет 1.9
>```
