# Неделя 4

[Линк на борду миро со всеми диаграммами](https://miro.com/app/board/uXjVMES1DKY=/?share_link_id=549504476777)

Для рефакторинга взял схему из урока  
![fixup-system.jpg](fixup-system.jpg)

Из нулевой домашки тоже есть схема сервисов, но там придется рефакторить сильно меньше. 
![services.png](services.png)

В текущей системе необходимо исправить 3 момента:

Вынести матчинг:
![matching.jpg](matching.jpg)

Разнести аккаунтинг
![accounting.jpg](accounting.jpg)

Разнести энтити сервис
![entity.jpg](entity.jpg)

Будем отталкиваться от стратегии когда нет ресурсов, а опыт есть:

Шаг 1:
Разнесем entity-сервис
![entity-fixup.jpg](entity-fixup.jpg)

Шаг 2:
Вынесем матчинг в отдельный сервис:
![entity-fixup.jpg](entity-fixup.jpg)

Шаг 3:
Разнесем аккаунтинг на 2:
![accounting-fixup.jpg](accounting-fixup.jpg)