# Домашнее задание по JS. Урок 3.

!Если что-то непонятно или не знаем как сделать пишем мне в скайп для помощи

## 1 задание

Создайте объект Date для даты: 20 февраля 2012 года, 3 часа 12 минут.

Временная зона — местная. Выведите его на экран.

## 2 задание

Напишите код для генерации случайного значения в диапазоне от 0 до max, не включая max.

## 3 задание

Напишите цикл, который предлагает prompt ввести число, большее 100. Если посетитель ввел другое число — попросить ввести еще раз, и так далее.

Цикл должен спрашивать число пока либо посетитель не введет число, большее 100, либо не нажмет кнопку Cancel (ESC).

Предполагается, что посетитель вводит только числа, предусматривать обработку нечисловых строк в этой задаче необязательно.

## 4 задание

Какие из этих if верны, т.е. выполнятся?

Какие конкретно значения будут результатами выражений в условиях if(...)?

```
if (-1 || 0) alert( 'первое' );
if (-1 && 0) alert( 'второе' );
if (null || -1 && 1) alert( 'третье' );
```

## 5 задание

Переписать if'ы в switch
важность: 4решение
Перепишите код с использованием одной конструкции switch:

```
var a = +prompt('a?', '');

if (a == 0) {
  alert( 0 );
}
if (a == 1) {
  alert( 1 );
}

if (a == 2 || a == 3) {
  alert( '2,3' );
}
```

## 6 задание

Есть объект salaries с зарплатами. Напишите код, который выведет сумму всех его зарплат.

```
var salaries = {
  "Вася": 100,
  "Петя": 300,
  "Даша": 250
};
```

//... ваш код должен вывести 650


## 7 задание

Натуральное число, большее 1, называется простым, если оно ни на что не делится, кроме себя и 1.

Другими словами, n>1 – простое, если при делении на любое число от 2 до n-1 есть остаток.

Создайте код, который выводит все простые числа из интервала от 2 до 10. Результат должен быть: 2,3,5,7.

P.S. Код также должен легко модифицироваться для любых других интервалов.

## 8 задание

Из массива arr выведите строку которая будет равна "Мама мыла раму" используя встроенные методы массива (если есть лишние елементы в массиве их нужно удалить!):

```

var arr = ["у", "м", "а", "р", " ", "а", "л", "ы", "м", 5, " ", "а", "м", "а", "М", 1];


```
