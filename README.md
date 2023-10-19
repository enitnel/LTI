# LTI-project
database management systems course project


## Разрабатываемое командой приложение 

### Краткое общее описание предметной области

Разработка БД для видеоигры от первого лица с линейным сюжетом на Unity3D

Целью данной работы является создание БД игровых компонентов для игры Leave the Island.
Задачи: 
Необходимо обеспечить
* Подключение всех БД к игре;
* Просмотр записей в БД. 

### Требования к работе

* Необходимо создать приложение с различными БД;
* Одна из БД должна быть NoSQL;
* В приложении должна быть возможность выбора базы данных

### Выполняемые программой функции (функциональные требования):

* Хранение данных
* Выборка данных
* Обновление данных

### Описание хранимых данных в каждой из используемых БД

* Персонаж
* Сюжет
* Звук
* Записки
* Концовки


## Выбранные для использования в приложении СУБД

* MongoDB
* MySQL
* SQLite

## Подробная ER-диаграмма с описанием полей таблиц:

![Dms coursework ER diagram](/Dms_cw_ER_diag.png)
  
## Модели баз данных

* MySQL   

![MySQL scheme](/MySQL_scheme.png)
 
* MongoDB

![MongoDB scheme](/MongoDB_scheme.png)   

* SQLite

![SQLite scheme](/SQLIte_scheme.png)


## Перечень основных операций с базами данных (для пользователя)



### Примеры составных запросов
  
* Получение информации о параметрах игры.

### Выборка данных

* Получение пользователем о характеристиках персонажа.
* Получение пользователем подробной информации о развитии игры.


## Архитектура приложения на верхнем уровне (простейшая диаграмма классов) с описанием основных модулей приложения

* MySQL
  
![MySQL Architecure](/MySQL_Architecure.jpg)
 
* MongoDB
 
![MongoDB_Architecture](/MongoDB_Architecure.jpg)
  
  
## Пример работы приложения

![Game sample](/Game_sample.jpg)


## Описание предлагаемых для использования инструментов, сторонних библиотек и программных средств, языка программирования

* Unity 3D
* XAMPP
* Visual Studio
* Sublime Text

