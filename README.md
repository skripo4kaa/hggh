
ConsultBot (доступний в Telegram за посиланням @Consult22Bot) є ботом, розробленим для того, щоб надавати розклад занять мовою Python для студентів через платформу Telegram. За допомогою цього бота, студенти можуть легко звертатися до нього у будь-який момент за допомогою свого смартфона і знаходити розклад занять на конкретний день.
Під час розробки цього бота я використовував PyCharm як інтегроване середовище розробки. Ви можете завантажити PyCharm за посиланням https://www.jetbrains.com/ru-ru/pycharm/.
Для створення бота спочатку вам потрібно звернутися до чату @BotFather в Telegram. Створення бота через цей чат є досить простим - ви просто слідуєте інструкціям. Після цього @BotFather надішле вам повідомлення з токеном вашого бота. Цей токен потрібно буде вставити у відповідний рядок в коді бота:
bot = telebot.TeleBot("ЗАМІНІТИ ЦЕЙ ТЕКСТ НА ТОКЕН НЕ ПРИБИРАЮЧИ КАВИЧКИ")

Зміна коду для власних потреб є дуже простою. Ви можете використовувати коментарі в коді, що знаходяться праворуч від 18-го і 28-го рядків, для зміни розкладу.
Для розгортання бота на сервері я використовував безкоштовну хмарну платформу Heroku. Процес перенесення бота досить простий і може бути виконаний за 9 хвилин за допомогою гайда, який можна знайти за цим посиланням: http://surl.li/knvnq.
