# Домашнее задание по JS. Урок 2.

## 1 задание

Определите результат и тип переменных в следующих случаях:

var r = '9' + 0;
var r = 9 + '0';
var r = 4 + 9;
var r = null + 7;
var r = '6' + null;

## 2 задание

Исправьте строку так чтобы в результате исчисления получилось 18

console.log(‘9’ + 9);

## 3 задание

В чем разница между сравнениями и какой будет результат:
‘4’ == 4 || ‘4’ === 4

## 4 задание

Будет ли верным  выражение:
2/3 + 1 + 1/3 == 2 и почему да или нет

## 5 задание

Что будет выведено в резлультате след. операций

var obj = {},
r = 0;

obj.prop = 9;
r = obj.prop;
delete obj.prop;

console.log(obj.prop, r);

## 6 задание

Используя конструкцию if..else, напишите код, который будет спрашивать: 'Какой сейчас месяц?'.

Если посетитель вводит 'сентябрь', то выводить 'Вы правы!', если что-то другое — выводить 'Та ну ты что? сентябрь!'.

## 7 задание

Используя конструкцию if..else, напишите код, который будет спрашивать: 'Введите любое целое число?'

Затем выведите alert:

1, если значение больше нуля, -1, если значение меньше нуля, 0, если значение равно нулю.

## 8 задание

Перепишите if с использованием оператора '?':

var x = 4, y = 6;

if (x + y >= 9) {
  result = 'Да!';
} else {
  result = 'Нет!';
}
