# ОПИСАНИЕ ЗАДАЧИ "ПИНГ-ПОНГ"
Необходимо реализовать при помощи программного кода,
написанного на Java или Kotlin игру в пинг-понг:

<b>Дано:</b><br>
Интерфейс игрока - Player.java
Абстрактный класс судьи - AbstractGameReferee.java
Класс для обозначения точки на сетке стола - TablePoint.java
Абстрактный класс стола для пинг-понга - AbstractPingPongTable.java
Вспомогательный класс для создания разметки стола - PingPongTableLayoutBuilder.java

<b>Задача</b>:<br>
Необходимо при помощи существующих классов реализовать игру двух игроков под присмотром судьи.

<i>Сначала необходимо реализовать объект стола.</i><br>
Стол состоит из трех наборов точек:
1. точек площадки ирока 1 
2. точек площадки игрока 2
3. точек за пределами стола.

<i>Затем реализовать игроков:</i><br>
Каждый удар (hit) игрока должен возвращать рандомную точку из общего набора точек стола (как площадок игроков, так и точек за пределами стола).

<i>Реализовать GameReferee</i>:<br>
При каждом ударе игрока судья проверяет, попал ли игрок по столу соперника или нет. И пишет в console лог об успешности удара.
В случае, если игрок не попадает по столу, очко присуждается его сопернику.
Очко разыгрывается до тех пор, пока один из игроков не попадет по столу соперника.
Очки суммируются и тот, кто наберет первым 11 очков - является победителем.

Критерии приемки задания:
Использованы классы, представленные в графе Дано.
Код написан на языке Java либо Kotlin.
Код работает. Судья фиксирует каждый розыгрыш и точку удара игроком, а так же успешность его попадания по столу соперника.
При каждом запуске программы розыгрыш должен быть уникальным.

Задача не сложная. Желаем успеха!