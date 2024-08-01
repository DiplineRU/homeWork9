RU text
Вводная часть
Представьте, что вы работаете в компании и помогаете коллегам разбираться с рабочими вопросами. К вам обращаются сотрудники из бухгалтерии.
Каждый день месяца компания тратит некую сумму. Сумма затрат записывается в бухгалтерскую книгу каждый понедельник. Таким образом, в книге находятся 4–5 записей разных чисел.

Задача 1
Бухгалтеры попросили посчитать сумму всех выплат за месяц.
Создайте массив с пятью целочисленными элементами и задайте каждому элементу значение.
Напишите программу, которая решит эту задачу, и выведите в консоль результат в формате: «Сумма трат за месяц составила … рублей».

Задача 2
Также бухгалтерия попросила найти минимальную и максимальную траты за неделю.
Создайте массив с пятью целочисленными элементами и задайте каждому элементу значение.
Напишите программу, которая решит эту задачу, и выведите в консоль результат в формате: «Минимальная сумма трат за неделю составила … рублей. Максимальная сумма трат за неделю составила … рублей».

Задача 3
Теперь бухгалтерия хочет понять, какую в среднем сумму компания тратила еженедельно.
Создайте массив с пятью целочисленными элементами и задайте каждому элементу значение.
Напишите программу, которая посчитает среднее значение трат за месяц (то есть сумму всех трат за месяц поделить на количество недель), и выведите в консоль результат в формате: «Средняя сумма трат за месяц составила … рублей».
Важно помнить: подсчет среднего значения может иметь остаток, то есть быть не целым, а дробным числом.

Задача 4
В бухгалтерской книге появился баг. Что-то пошло не так: фамилии и имена сотрудников начали отображаться в обратную сторону. Т. е. вместо «Иванов Иван» мы имеем «навИ вонавИ». Данные с именами сотрудников хранятся в виде массива символов 
char[ ]
Напишите код, который развернет содержимое массива, а затем распечатает его содержимое. В качестве данных для массива используйте:
char[] reverseFullName = { 'n', 'a', 'v', 'I', ' ', 'v', 'o', 'n', 'a', 'v', 'I'};
В результате в консоль должно быть выведено: Ivanov Ivan.
Важно: не используйте дополнительные массивы для решения этой задачи. Необходимо корректно пройти по массиву циклом и поменять его содержимое , чтобы установить правильный порядок.

ENG text
The introductory part
Imagine that you work for a company and help colleagues deal with work issues. Employees from the accounting department are contacting you.
Every day of the month, the company spends a certain amount. The cost amount is recorded in the ledger every Monday. Thus, there are 4-5 entries of different numbers in the book.

Task 1
The accountants asked to calculate the amount of all payments for the month.
Create an array with five integer elements and set each element to a value.
Write a program that will solve this problem, and output the result to the console in the format: "The amount of expenses for the month was ... rubles."

Task 2
The accounting department also asked to find the minimum and maximum expenses for the week.
Create an array with five integer elements and set each element to a value.
Write a program that will solve this problem, and output the result to the console in the format: "The minimum amount spent per week was ... rubles. The maximum amount spent per week was ... rubles."

Task 3
Now the accounting department wants to understand the average amount the company spent weekly.
Create an array with five integer elements and set each element to a value.
Write a program that calculates the average amount of spending per month (that is, the sum of all spending per month divided by the number of weeks), and output the result to the console in the format: "The average amount of spending per month was ... rubles."
It is important to remember: the calculation of the average value may have a remainder, that is, it may not be an integer, but a fractional number.

Task 4
A bug has appeared in the ledger. Something went wrong: the surnames and names of employees began to be displayed in the opposite direction. I.e. instead of "Ivanov Ivan" we have "navI wonavI". Data with employee names is stored as an array of characters 
char[ ]
Write code that will expand the contents of the array and then print its contents. As data for the array, use:
char[] reverseFullName = { 'n', 'a', 'v', 'I', '', 'v', 'o', 'n', 'a', 'v', 'I'};
As a result, the following should be output to the console: Ivanov Ivan.
Important: do not use additional arrays to solve this problem. It is necessary to cycle through the array correctly and change its contents in order to establish the correct order.
