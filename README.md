Описание задачи.
Создать телефонный справочник с возможностью импорта и экспорта данных в нескольких форматах.


main (основной модуль) 
logger (модуль логирования) 
bot.py (модуль телеграм-бота) 
.gitignore (не требует комментариев) 
crud (создание, чтение, обновление, удаление) 
user_interface (модуль взаимодействия с пользователем) - 
data_generation (модуль генерации БД) 
Как запустить проект (рекомендуем использовать VCS)

Для запуска с помощью консоли:
скачать проект в локальный репозиторий;
в консоли ввести команду "python3 main.py";
в случае необходимости создания рандомной базы контактов раскоменнтировать строку #7 (метод dg.start()) модуля main.py;
следовать инструкциям в консоле.
Для запуска телеграм-бота:
скачать проект в локальный репозиторий;
обновить Python до версии 3.10.5;
настроить окружение, введя в консоле поочередно команды:
python3 -m venv .libraries;
pip install pyTelegramBotAPI;
при необходимости обновить библиотеку до последней версии (следуя инструкциям в консоле)
перезапустить консоль;
в корневой папке проекта (Phonebook_team_development) создать файл с названием "token.csv", в котором в первой строке добавить индивидуальный токен телеграм-бота, после чего сохранить изменения файла;
инструкция по созданию индивидуального токена телеграм-бота здесь: https://core.telegram.org/bots
в консоле ввести команду "python3 bot.py" или "python bot.py" (при необходимости установить версию Python 3.10.5)


