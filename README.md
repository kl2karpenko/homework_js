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

