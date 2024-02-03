Описание:

Создай консольное приложение "Калькулятор". Приложение должно читать из консоли введенные пользователем строки, числа, арифметические операции проводимые между ними и выводить в консоль результат их выполнения.
Реализуй класс Main с методом public static String calc(String input). Метод должен принимать строку с арифметическим выражением между двумя числами и возвращать строку с результатом их выполнения. Ты можешь добавлять свои импорты, классы и методы. Добавленные классы не должны иметь модификаторы доступа (public или другие).

Требования:﻿

1. Калькулятор умеет выполнять операции сложения, вычитания, умножения и деления с двумя числами: a + b, a - b, a * b, a / b. Данные передаются в одну строку (смотри пример)! Решения, в которых каждое число и арифмитеческая операция передаются с новой строки считаются неверными.

2. Калькулятор умеет работать как с арабскими (1,2,3,4,5...), так и с римскими (I,II,III,IV,V...) числами.

3. Калькулятор должен принимать на вход числа от 1 до 10 включительно, не более. На выходе числа не ограничиваются по величине и могут быть любыми.

4. Калькулятор умеет работать только с целыми числами.

5. Калькулятор умеет работать только с арабскими или римскими цифрами одновременно, при вводе пользователем строки вроде 3 + II калькулятор должен выбросить исключение и прекратить свою работу.

6. При вводе римских чисел, ответ должен быть выведен римскими цифрами, соответственно, при вводе арабских - ответ ожидается арабскими.
7. При вводе пользователем неподходящих чисел приложение выбрасывает исключение и завершает свою работу.
8. При вводе пользователем строки, не соответствующей одной из вышеописанных арифметических операций, приложение выбрасывает исключение и завершает свою работу.
9. Результатом операции деления является целое число, остаток отбрасывается.
10. Результатом работы калькулятора с арабскими числами могут быть отрицательные числа и ноль. Результатом работы калькулятора с римскими числами могут быть только положительные числа, если результат работы меньше единицы, выбрасывается исключение.

Пример работы программы:

Input:
1 + 2

Output:
3

Input:
VI / III

Output:
II

Input:
I - II

Output:
throws Exception //т.к. в римской системе нет отрицательных чисел

Input:
I + 1

Output:
throws Exception //т.к. используются одновременно разные системы счисления

Input:
1

Output:
throws Exception //т.к. строка не является математической операцией

Input:
1 + 2 + 3

Output:
throws Exception //т.к. формат математической операции не удовлетворяет заданию
