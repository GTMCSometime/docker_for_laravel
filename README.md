<p align="center">Docker для Laravel</p>


## Контейнеры


- nginx (8006:80 порт)
- PHP
- MySQL (3318:3306 порт)
- PHPMyAdmin (8007:80 порт)
- Composer
- artisan

## Использование

1. Добавляем в корень проекта.
2. В терминале пишем: "docker compose up -d".
3. После сборки контейнеров, в терминале, для миграции в БД, пишем: "docker compose run artisan migrate".