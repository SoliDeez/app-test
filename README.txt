- Для запуска необходимо находясь в каталоке с файлом docker-compose.yml ввести в терминале команду:
docker compose up -d

- В браузере перейти по адресу:
127.0.0.1

- Заполнить форму с необходимыми параметрами:
Язык - Русский
login: test
password: test
Разрешить использование слабого пароля.
e-mail: test@example.com

- Для активации ObjectCache:
Перейти в раздел плагины
Активировать плагин Redis Object Cache
Нажать Enable Object Cache

- Для остановки приложения и удаления контенеров:
docker compose down
