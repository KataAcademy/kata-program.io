# Задача: программа для логистической компании

#### Описание:
Логистическая компания перевозит товары при помощи грузовых машин.  
У каждого товара есть стоимость и вес.
У каждой машины есть максимальная грузоподъемность.  
Компании выгодно перевозить максимально дорогие товары, потому что за их доставку платят больше.  
Напишите программу, результатом работы которой станет инструкция для грузчиков, подсказывающая какой товар нужно грузить в машину.
Ввод и вывод данных должен осуществляться через консоль.

#### Последовательность выполнения программы в консоли:
1. Пользователь вводит грузоподъёмность машины - целое число в килограммах. 
2. Пользователь указывает предметы для перевозки в формате `название_предмета/вес/цена` отделенных пробелом друг от друга. Описание каждого следующего предмета должно быть отделено пробелом.
3. Программа выводит в консоль названия всех предметов, которые надо загрузить в машину и их суммарную стоимость. 

#### Пример работы программы:
###### Input:
`50`  
`стол/30/7000 шкаф/40/9000 пылесос/10/6000 кровать/40/10000`  
###### Output:
 `пылесос кровать 16000 `
 
#### Принципы оценки работы:
Обратите внимание на принципы ООП, постарайтесь разбить программу на логические классы. Продемонстрируйте своё умение в работе с разными синтаксическими конструкциями, не забудьте про исключительные ситуации, при которых выполнение программы невозможно из-за некорректных входных данных. 
 
#### Как отправить решение?
1. Если вы не знакомы с git и Github вам нужно ознакомиться с этой [статьей](http://maxsite.org/page/how-to-put-your-project-on-github-com), в ней описаны основы работы с git. 
2. Если вы уже ознакомились с основами работы с git или были  знакомы ранее - вам нужно создать собственныый репозиторий и добавить туда проект с решениием.
3. Ссылку на репозиторий отправьте нам на почту *info@kata.academy* с темой **Тестовое задание на курс**.  
