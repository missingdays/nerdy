##Домашнее задание

Сегодня на уроке информатики Петя узнал про системы счисления с различными основаниями. В системе счисления с основанием k используются цифры с весом от 0 до k − 1, для обозначения первых 10 цифр используются обычные цифры, а далее задействуются также буквы латинского алфавита и другие знаки.

Теперь Петя пытается решить следующее домашнее задание. Даны числа x, y и z, записанные с использованием десятичных цифр. Требуется найти все такие основания систем счисления k, что все цифры, использованные в числах, существуют в этой системе счисления, и при этом если считать, что x, y и z — числа, записанные в системе счисления с основанием k, то произведение x и y равно z.

Петя начал решать эту задачу и обнаружил, что при некоторых условиях подходит бесконечно много различных k. Он решил для начала понять, имеет ли место этот случай. Помогите ему это выяснить.

##Формат входных данных
Первая строка содержит число t — количество тестов во входных данных (1 ≤ t ≤ 1000).

Далее следует описание t тестов, каждый тест описывается тремя строками, которые содержат числа x, y и z, соответственно. Каждое из этих чисел положительно, состоит только из десятичных цифр и не содержит ведущих нулей. Длина каждого из чисел x и y не превышает 100, длина числа z не превышает 200.

##Формат выходных данных

На каждый тест в отдельной строке выведите ответ на него — «Infinity», если существует бесконечное число таких k, что если считать, что числа во вводе записаны в системе счисления с основанием k, то произведение x и y равно z, либо «Finite», если таких k конечное число.

###Входные данные

4

1

1

1

2

2

10

11

11

121

1

1

10

##Выходные данные
Infinity

Finite

Infinity

Finite