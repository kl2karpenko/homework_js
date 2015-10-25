# Домашнее задание по JS. Урок 8.

!Если что-то непонятно или не знаем как сделать пишем мне в скайп для помощи

## 1 задание

Создайте кнопку button в вашем документе и выведете в консоль при нажатии на кнопку ссылку this и проверте являеться ли this 
той кнопкой на которую вы нажали!

## 2 задание

Создайте input[type=text] элемент. При фокусе на элемент после него будет добваляться новый div, при вводе
в него текста тот же текст будет писаться в div внизу, после blur с input div будет удаляться

## 3 задание

Добавьте в ваш документ элемент select, при изменении знавения которого вы будете записывать выбранные значение клиенто
в массив, после того как клиент изменить хзначение select вы выведете это значение на экран и так для каждого значения, то есть 
у вас под селектом будет список всех значений которые клиент когда либо выбирал

## 4 задание

Когда вы вводите что нибудь через клавиатуру у документа возникает событие onkeyup, onkeydown, onkeypress и объект event имеет такое свойство как keyCode

То есть:

```

document.addEventListener('keydown', function (event) {
    console.log(event.keyCode); // выдаст код той клавиши котоую вы будете нажимать
});

```

Сделайте модальное окно которое будет появляться при нажатии на кнопку которую вы создадите в документе, и сделайте так что бы при нажатии на ESC это окно закрывалось

## 5 задание

Создайте страницу на которой будет навигация, которая будет переводить пользователя по якорю на разные разведлы сайта, но при переходе на якорь я хочу чтобы скролл был плавным, то есть вам по факту нужно изменить поведении event при нажатии на данный якорь

## 6 задание

Создайте форму с полями имени, фамилии, имейла и обратной связи которая будет валидироваться, если пользователь неправильно ввел информацию (валидация должна быть сделана как на HTML5 так и с помощью JS, и валидация должна срабатывать при blur с поля инпута формы и при клике на кнопку submit если это нужно)

## 7 задание 

Выполните задание с CODEWARS

<ol>
<li><a href="http://www.codewars.com/kata/more-than-one-way-to-call-a-function-or-skin-a-cat">more-than-one-way-to-call-a-function-or-skin-a-cat</a></li>
<li><a href="http://www.codewars.com/kata/case-swapping">case-swapping</a></li>
<li><a href="http://www.codewars.com/kata/descending-order">descending-order</a></li>
<li><a href="http://www.codewars.com/kata/complete-the-pattern-number-10-parallelogram">complete-the-pattern-number-10-parallelogram</a></li>
<li><a href="http://www.codewars.com/kata/find-duplicates">find-duplicates</a></li>
<li><a href="http://www.codewars.com/kata/gradually-adding-parameters">gradually-adding-parameters</a></li>
<li><a href="http://www.codewars.com/kata/reverseit-1">reverseit-1</a></li>
<li><a href="http://www.codewars.com/kata/basic-js-calculating-averages">basic-js-calculating-averages</a></li>
</ol>
