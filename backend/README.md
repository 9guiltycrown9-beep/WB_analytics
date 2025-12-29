# WB Analytics Backend

NestJS backend для сервиса аналитики Wildberries.

## Быстрый старт

1. Скопируйте `.env.example` в `.env`:
```bash
cp .env.example .env
```

2. Запустите проект с помощью Docker Compose:
```bash
docker-compose up --build
```

Приложение будет доступно на `http://localhost:3000`

## Структура проекта

- `src/` - исходный код приложения
- `Dockerfile` - конфигурация Docker для сборки и запуска
- `docker-compose.yml` - конфигурация для запуска всех сервисов
- `.env.example` - пример файла с переменными окружения