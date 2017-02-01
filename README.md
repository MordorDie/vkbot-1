# vkbot
Базовая конструкция бота для социальной сети Вконтакте

###Как активировать бота?
В файле `core_bot.py` указать в переменной `app_id` - id от приложения вконтакте и `user_login`, `user_password` - данные от аккаунта для бота, то есть логин и пароль от странички Вконтакте, для бота.

###Что есть в боте?

+ Реализованно переобразование цифр в эмоджи
+ Реализованны комманды: !статы, !обомне, !аптайм, !время, !лайк, !оботе
+ Реализован механизм автоопределения отправки сообщений (лс/беседа)
+ Реализованно авто-добавление и удаление друзей (при удалении бота).
+ Проверка на кик из группы
+ Оптимизировал количество запросов, на сколько смог, за все время тестирования, ниразу не видел капчи.
+ Реализованно чтение сообщений (помечает, как прочитанные)
+ Время цикла проверки сообщений, каждые 5 секунд
+ Перед ответом, бот отправляет статус (пишет....)
+ В статусе бота отображается время и дата, с помощью эмоджи.
+ Реализованна проверка лайкнул бот аватарку или нет