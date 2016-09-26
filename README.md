#Введение
Программа антираписания представляет собой расписание свободных аудиторий БГУИР. Эта программа будет показывать наличие пустых аудиторий по корпусам\этажам корпусов, а так же наличие\отсутствие в аудитории розеток. Можно будет выбрать для отображения любой корпус, этаж, любую дату. Больше ничего приложение делать не будет...

#Требования пользователя
##Программные интерфейсы
* API Bsuir
* Android Studio

##Интерфейс пользователя
При входе в приложение будет показываться уведомление, что доступ в компьютерные аудитории будет осуществляться только при придъявлении студенческого билета БГУИР. Ну ещё там будет отказ от отвестственноти автора приложения(то есть меня), ну и тд... 

Если эти требования не принять, то приложение закроется.

На главном экране будут отображаться вкладки... Каждая вкладка будет соотвествавать номеру корпуса, ниже будут отображаться собственно свободные аудитории и время когда они будут свободны...

Так же на главном экране можно будет выбрать из выпадающего меню дату, чтобы отобарзить свободные аудитории...

Соотнести мои слова с реальностью можно с помощью мокапов, они лежат в папке mockups.

##Характеристики пользователей
Это приложение будет интересно студентам БГУИР, которые хотят спокойно позаниматься, покушать, поспать, помириться с девушкой и тд...

Уровень образования, достатка, ICQ по большей части не будет мешать пользоваться приложением.

Наибольшую пользу получат студенты БГУИР, для остальных людей польза от приложения сомнительна...			

##Предположения и зависимости
Отсутсвие подключения к интернету может повлиять на актуальность информации о свободных аудиториях и наличия в них розеток

#Системные требования	
##Функциональные требования
* функция обновления расписания\розеток
* функция ручного изменения расписания(на локальном устройстве)
* функция добавления\удаления розеток в аудитории(на сервере, для всех)

##Нефункциональные требования
* удобный пользовательский интерфейс

###Атирибуты качества
Необходимо организовать безопасный доступ к файлам в которых будет хранится информация о наличии розеток, синхронизацию между пользователями этих файлов. Сделать так, чтобы эти файлы не могли изменяться не пользователями приложения антирасписания... 
