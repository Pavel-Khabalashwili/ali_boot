# Телеграм-бот для поиска товаров на AliExpress

### Реализованные команды:
1) /start
2) /help
3) /low
4) /high
5) /custom
6) /history
7) /edit

low, high, custom выполняют поиск с сортировкой соответственно по минимальной цене, 
максимальной цене и по указанному диапазону цен.

Для каждой команды поиска запрашивается количество выводимых результатов.

Команда history выводит результаты последних 10 запросов.

При первом обращении к боту он спросит имя пользователя, регион и валюту для поиска и отображения результатов.

Для изменения данных профиля реализована команда edit

Для запуска бота необходимо создать файл .env, по образцу .env.template, в котором необходимо указать 
токен телеграм бота и ключ от API.

