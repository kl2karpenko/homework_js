# Домашнее задание по JS. Урок 4.

!Если что-то непонятно или не знаем как сделать пишем мне в скайп для помощи

## 1 задание

В объекте есть свойство className, которое содержит список «классов» – слов, разделенных пробелом:

```
var obj = {
  className: 'open menu'
}
```

Создайте функцию addClass(obj, cls), которая добавляет в список класс cls, но только если его там еще нет:

```
addClass(obj, 'new'); // obj.className='open menu new'
addClass(obj, 'open'); // без изменений (класс уже существует)
addClass(obj, 'me'); // obj.className='open menu new me'

alert( obj.className ); // "open menu new me"
```

P.S. Ваша функция не должна добавлять лишних пробелов.

## 2 задание

У объекта есть свойство className, которое хранит список «классов» – слов, разделенных пробелами:

```
var obj = {
  className: 'open menu'
};
```
Напишите функцию removeClass(obj, cls), которая удаляет класс cls, если он есть:

```
removeClass(obj, 'open'); // obj.className='menu'
removeClass(obj, 'blabla'); // без изменений (нет такого класса)
```

P.S. Дополнительное усложнение. Функция должна корректно обрабатывать дублирование класса в строке:

```
obj = {
  className: 'my menu menu'
};
removeClass(obj, 'menu');
alert( obj.className ); // 'my'
```

Лишних пробелов после функции образовываться не должно.

## 3 задание

Напишите код, который:

Запрашивает по очереди значения при помощи prompt и сохраняет их в массиве.
Заканчивает ввод, как только посетитель введёт пустую строку, не число или нажмёт «Отмена».
При этом ноль 0 не должен заканчивать ввод, это разрешённое число.
Выводит сумму всех значений массива когда ввод прекращен.

## 4 задание

Напишите код который принимат от пользователя значение x (можно например через prompt) и выводит значение следующей формулы

<img src="https://github.com/kl2karpenko/homework_js/blob/lesson4/task3_2.png"/>

## 5 задание

У вас есть массив arr, создайте функции arrSorted которая отсортирует массив arr по алфавиту (мы изучали функцию сортировки для массивов можно воспользоватся ею, в нее нужно передать как аргумент функцию вот ссылка на пример http://javascript.ru/Array/sort  )

```
var arr = ['HTML', 'JavaScript', 'CSS'];

// ... ваш код ...

console.log( arrSorted ); // CSS, HTML, JavaScript
console.log( arr ); // HTML, JavaScript, CSS (без изменений)

```

## 6 задание

Палиндром - это строка которая читается с обоих сторон одинаково. Например: Анна, оно, А роза упала на лапу Азора.

Необходимо написать функцию isPal(string) которая возвращает true или false в зависимости от того является ли строка палиндромом или нет.

```

console.log(isPal('Anna')); // true
console.log(isPal('А роза упала на лапу Азора')); //true
console.log(isPal('Вася')); //false
console.log(isPal('12321')); //true
console.log(isPal('123212')); //false

```

## 7 задание

Анаграммы — слова, состоящие из одинакового количества одинаковых букв, но в разном порядке. Например:

воз - зов, киборг - гробик, корсет - костер - сектор, 

Напишите функцию anClean(arr), которая возвращает массив слов, очищенный от анаграмм.

```
var arr = ['воз', 'киборг', 'корсет', 'ЗОВ', 'гробик', 'костер', 'сектор'];

console.log( anClean(arr) ); // 'воз,киборг,корсет' или 'ЗОВ,гробик,сектор'

```

## 8 задание

Создайте программу которая соеденит массив в строку и поменяет местами и поменяет порядок следования слов в массиве:

```

var arr = [ 'rrrA', 'toboR', 'ekiL', 'dooG', 'esoR' ];

```
## 9 задание

Codewars

<a href="http://www.codewars.com/r/qEzvHw">Регистрируемся на codewars</a>

Выполняем задачки:

<ol>
<li> <a href="http://www.codewars.com/kata/even-or-odd">even-or-odd</a></li>
<li> <a href="http://www.codewars.com/kata/jennys-secret-message">jennys-secret-message</a></li>
<li> <a href="http://www.codewars.com/kata/return-negative">return-negative</a></li>
<li> <a href="http://www.codewars.com/kata/opposites-attract">opposites-attract</a></li>
<li> <a href="http://www.codewars.com/kata/convert-boolean-values-to-strings-yes-or-no">convert-boolean-values-to-strings-yes-or-no</a></li>
</ol>
