Создайте на вашем github репозиторий по следующему шаблону HW#-name. Все результаты нужно запушить в ваш репозиторий и прикрепить ссылку на hillel портале.
Создайте index.html в котором подключите js script.
Создайте README.md с описанием задания.

Реализовать функции sum через замыкание
function sum(x) {// ваш код}

const sum1 = sum(1);
sum1(2); // результат выполнения 3
или 
	вызов sum(1)(2); // результат выполнения 3

Описать комментарием в чем ошибка, почему и исправить код.
for (var i = 0; i < 10; i++) {
    setTimeout(function() {
        console.log(i);
    }, 0);
}
В итоге нужно вывести от 1 до 10.