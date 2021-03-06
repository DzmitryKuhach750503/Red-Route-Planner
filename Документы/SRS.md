# SRS

###
Содержание

1. [Введение](#1)
2. [Требования пользователя](#2) <br>
  2.1. [Программные интерфейсы](#2.1) <br>
  2.2. [Интерфейс пользователя](#2.2) <br>
  2.3. [Характеристики пользователей](#2.3) <br>
  2.4. [Предположения и зависимости](#2.4) <br>
3. [Системные требования](#3.) <br>
  3.1 [Функциональные требования](#3.1) <br>
  3.2 [Нефункциональные требования](#3.2) <br>
        3.2.1 [Атрибуты качества](#3.2.1) <br>        3.2.2 [Внешние интерфейсы](#3.2.2) <br>        3.2.3 [Ограничения](#3.2.3) <br>
4. [Аналоги](#4) <br>

### 1. Введение <a name="1"></a>  
Данный документ посвящен программному продукту:  “Red Route Planner”.  
“Red Route Planner” - это мобильное приложение, позволяющее пользователю построить наиболее быстрый маршрут через места, необходимые для посещения.  
Люди ежедневно сталкиваются с разнообразными профессиональными и бытовыми задачами, что требует их присутствия в разных местах города или района. Чтобы быстрее перемещаться раньше заранее узнавали и планировали маршруты. Но в настоящее время, в век цифровизации,  набирают популярность приложения, содержащие электронные карты. Такие приложения способны быстро помочь человеку составить необходимый в конкретном случае маршрут и отобразить его с необходимыми для данными.  
“Red Route Planner” - это приложение, которое рассчитано для любого человека. Система настроек приложения позволит выбрать способ перемещения пользователя, а также указать какие места для посещения необходимо добавить в маршрут. Удобство приложения заключается в том, что карта с маршрутом всегда находится с пользователем - на его мобильном устройстве.  



### 2. Требования пользователя <a name="2"></a>
#### 2.1. Программные интерфейсы <a name="2.1"></a>
Операционной средой для разработки является операционная система Android. Средой разработки для данной операционной системы и эмулятором был выбран Android SDK. 
Для реализации приложения будет использоваться  JDK  -  комплект разработчика  для разработки на языке Java, включающий в себя компилятор Java, стандартные библиотеки классов Java, утилиты и исполнительную систему Java.
Выбор IDE c поддержкой разработки для Android упал на Android Studio.
.
#### 2.2. Интерфейс пользователя <a name="2.2"></a>

На главной форме приложения требуется предоставить пользователю возможность создать маршрут, увеличить или уменьшить карту, определить текущую геолокацию, рисунок 2.1.

![рисунок 2.1](https://github.com/DzmitryKuhach750503/Red-Route-Planner/blob/master/Мокапы/Main_panel.png)
 
Данная форма предполагает функции добавления новых точек маршрута, их удаление, построение маршрута от текущего расположения пользователя через выбранные точки, рисунок 2.2.

![рисунок 2.2](https://github.com/DzmitryKuhach750503/Red-Route-Planner/blob/master/Мокапы/Route_Settings.png)
  
Пример построенного маршрута приведён на рисунке 2.3.

![рисунок 2.3](https://github.com/DzmitryKuhach750503/Red-Route-Planner/blob/master/Мокапы/Main_panel_route.png)
   
В приложении должны быть предусмотрены настройки, которые вызываются из главного меню (рисунок 2.4).

![рисунок 2.4](https://github.com/DzmitryKuhach750503/Red-Route-Planner/blob/master/Мокапы/Setting.png)
 



#### 2.3. Характеристики пользователей <a name="2.3"></a>

ПО “Red Route Planner”  разрабатывается под любого пользователя.  Приложение должно быть пригодно как для людей, которые хотят построить короткий маршрут, так и для людей, желающих посетить большое количество мест.  




#### 2.4. Предположения и зависимости  
<a name="2.4"></a>  Мобильное приложение рассчитано для смартфонов под операционную систему Android, что ставит ограничения для использования приложения пользователям, имеющим другие ОС или у которых отсутствует смартфон. Приложение  “Red Route Planner” должно требовать постоянного подключения к интернету.

### 3. Системные требования <a name="3"></a>  


#### 3.1. Функциональные требования <a name="3.1"></a>  
1.	Работа с картой - возможность пользователя увеличивать или уменьшать размер карты;
2.	Построение маршрута -  создание маршрута через определённые точки, которые выбирает пользователь, выбор способа передвижения пользователя;
3.	Определение геолокации -  возможность пользователя определить текущее местоположение на карте;
4.  Очистка карты - возможность пользователя очищать карту от маршрута;
5.	Настройки -  пользователю необходимо предоставить возможность настраивать приложение под себя (установка цвета маршрута, цвета маркера местоположения пользователя, цвета маркеров точек маршрута, настройка уведомлений);

#### 3.2. Нефункциональные требования <a name="3.2"></a>   



#### 3.2.1. Атрибуты качества <a name="3.2.1"></a>  
Одним из главных атрибутов качества разрабатываемого мобильного приложения должна стать надежность ПО. Под надежностью необходимо понимать свойство программы точно выполнять заложенные задачи и в любой ситуации обеспечить сохранность данных, с которыми работает пользователь. 
Безотказность программы  должна характеризоваться работоспособностью во время обработки информации и корректной работой при непредвиденных действиях пользователя.
Производительности системы необходимо обеспечивать комфортную работу пользователя. Для этого время отклика программы должно быть минимальным.  




#### 3.2.2. Внешние интерфейсы <a name="3.1"></a>  
Интерфейсу приложения необходимо обеспечить  простоту выполнения действий в ПО, должна соблюдаться легкость ориентирования человека в приложении, интерфейс обязан не раздражать, результаты действий и запросы программы необходимо предоставлять пользователю в понятной форме.
   



#### 3.2.3. Ограничения <a name="3.1"></a>  
Для запуска приложения треубется версия Android 7.0 и выше. Установка приложения осуществляется через apk файл. Для работы с приложением требуется интернет.
#### 4. Аналоги <a name="4"></a>
К аналогам разрабатываемого приложения «Red Route Planner» можно отнести  следующие программы:  
1.	«Google Maps» –  приложение, которое предоставляет работу с картой, маршрутами и информацией о местаз, отображаемых на катре. К достоинствам можно механизм редактирования карт, голосовой поиск, спутниковые снимки  
2.	«Route4Me Route Planner» –  приложение, предназначеное для прокладки оптимального маршрута. Отличается предоставлением оптимального маршрута и быстротой его изменения при внесении изменений.

####  
Рассмотрев аналоги, можно сказать, что разрабатываемое приложение должно стать хорошей платформой для дальнейшего масштабирования, переноса на другие платформы. К достоинствам на данном этапе можно отнести удобство работы пользователя с ПО, надежность приложения.  
