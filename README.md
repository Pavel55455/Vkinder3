Дипломная работа 'VKinder'

Запуск программы

становка необходимых библиотек:
    pip install vk_api
    pip install psycopg2

Заполнение переменных в файле config.py --- 

Токен пользователя можно получить здесь

\Запуск файла bot.py
Взаимодействие с ботом начинается после нажатия кнопки 'Начать поиск' в диалоге с сообществом, чей токен (сomm_token) указан в файле config.py
Задание к дипломной работе
Необходимо разработать приложение для знакомств, эталоном которого является Tinder. Приложение предоставляет простой интерфейс для выбора понравившегося человека.

Используя данные из VK, нужно сделать сервис намного лучше, чем Tinder, а именно: чат-бота 'VKinder'. Бот должен искать людей, подходящих под условия, на основании информации о пользователе из VK:

возраст
пол
город
семейное положение (по дефолту происходит поиск по критериям 'в активном поиске' и 'не замужем(не женат)'
У тех людей, которые подошли по требованиям пользователю, получать топ-3 популярных фотографии профиля и отправлять их пользователю в чат вместе со ссылкой на найденного человека. Популярность определяется по количеству лайков.

Требование к сервису
Код программы удовлетворяет PEP8;
Получать токен от пользователя с нужными правами;
Программа декомпозирована на функции/классы/модули/пакеты;
Результат программы записывать в БД (PostreSQL);
Люди не должны повторяться при повторном поиске;
Не запрещается использовать внешние библиотеки для vk.
Баги
При вводе городов Украины, как локация поиска партнёра возникает ошибка из-за наличия в языке специфических символов, препятствующих корректной работе программы.
