Контейнеризированная версия сайта с оборудованием
Для запуска сайта необходимо установить на линукс сервер:
1) docker (документация есть на оффициальном сайте)
2) docker-compose (через apt-get install)
3) в директории с docker-compose.yaml написать комманду $: docker-compose up -d
Все конфигурации по запускаемым контейнерам хранятся в docker-compose.yaml, настройка nginx - nginx/nginx.conf
