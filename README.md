ЗАПУСК

1. Выполните команду "npm i" после клонирование, чтобы установить все зависимости

2. Выберите тип запуска:

|-> Development
cmd-> docker compose -f docker-compose.yml -f docker-compose-dev.yml up -d --build

|-> Production
cmd-> docker compose -f docker-compose.yml -f docker-compose-prod.yml up -d --build
