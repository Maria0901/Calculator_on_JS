Чек-лист по тестовой задаче "Калькулятор":
1) Создать поле для ввода цифр, получающее значения только с кнопок.
2) Создать кнопки с цифрами, кнопки действий и кнопки очищения и вывода результата.
3) Написать функцию для отображения в окне инпута символов и цифр, введенных с помощью кнопок.
4) Добавить кнопку для очищения поля.
5) Написать функцию для посимвольного удаления и присвоить соответствующей кнопке.
6) Написать функцию для вычисления и вывода результата операций. 
7) Написать инструкцию пользователя.

Инструкция:

1) Максимальная длина символов за одну операцию - 16.
2) Количество операций ограничено длиной строки.
3) Ответ содержит 5 знаков после запятой.
4) Ответ всегда выводится с дробной частью, даже если она нулевая.
5) Количесво цифр после запятой при вводе ограничего максимальной длиной строки.
6) После получения резульата возможно продолжить рассчеты с получившимся числом.
7) В любой момент (при вводе, после получения результата) возможно очистить поле кнопкой "С", удалить символы и цифры по одному кнопкой "←" (исключение см. пункт 13).
8) Рассчет производится по нажатию кнопки "=".
9) Если введено два знака операции подряд, использоваться будет последний.
10) Если ввести только знаки операций и нажать "=" в окне инпута появится сообщение "Ошибка".
11) Если на конце введенного значения знак вычисления, а не цифра, при нажатии "=" не произойдет ни каких действий.
12) При делении на ноль в поле ввода появится сообщение "Ошибка".
13) Если в результате получилась "Ошибка", дальнейший ввод невозможен. Чтобы продолжить расчеты необходимо очистить поле кнопкой "С".
14) Если после "0" не ставится "." , "0" удалится после введения следующей цифры;
15) Чтобы произвести операцию с отрицательным числом необходимо взять его в скобки, если это число не первое при вводе.
16) Возможные операции: сложение/вычитание, умножение/деление, с отрицательными и дробными числами.
17) Если в одном числе ввести две точки подряд, первая удалится, если не подряд - число не будет считаться.
18) порядок выполнения действий в выражениях без скобок: действия выполняются по порядку слева направо, причем сначала выполняется умножение и деление, а затем – сложение и вычитание.
 







