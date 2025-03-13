requierments 
1. docker engine
2. docker
3. docker-compose

Для Ubuntu:

устновка: sudo apt-get install docker docker-compose

Скачать репозиторий.

файлы docker-compose и .env должны быть в одном месте

Файл .env настраивает Переменные среды внутри docker image (менять по необходимости)

После настройки среды, запустить командрй docker-compose up --build

После запуска перейти на апи localhost:7777/dstu
