# hw3.1ogo2
## Чат-бот для напоминания о питье воды

Этот чат-бот на основе Telegram API предназначен для напоминания пользователям о необходимости пить воду в течение дня. 

### Функциональность:

• Стартовое сообщение: Когда пользователь запускает бота командой /start, он приветствует его и запускает напоминания о воде.
• Напоминания: Бот отправляет сообщения о питье воды в 10:00, 14:00 и 18:00.
• Интересные факты о воде: Пользователь может получить случайный факт о воде, используя команду /fact. 

### Установка и запуск:

1. Создайте бота в Telegram:
  * Перейдите в @BotFather в Telegram.
  * Введите команду /newbot.
  * Выберите имя бота и имя пользователя.
  * Сохраните токен доступа, который вам предоставит @BotFather.
2. Замените токен в коде:
  * В файле bot.py найдите строку bot = telebot.TeleBot('Здесь должен быть ваш токен')
  * на ваш токен доступа.
3. Запустите бота:
  * Откройте терминал и перейдите в папку, где находится файл bot.py.
  * Запустите команду python bot.py.

### Использование:

1. Найдите бота в Telegram по его имени пользователя, которое вы указали при создании.
2. Отправьте команду /start, чтобы начать работу бота.
3. Бот будет отправлять вам напоминания о воде в указанное время.
4. Используйте команду /fact, чтобы получить случайный интересный факт о воде.

### Дополнительные возможности:

• Добавить возможность настройки времени напоминаний.
• Ввести возможность выбора предпочитаемого чашки воды в напоминаниях.
• Интегрировать с другими приложениями, например, с фитнес-трекерами.
• Реализовать возможность отключения/включения напоминаний.