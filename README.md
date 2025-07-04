# Планировщик задач

Веб-приложение для планирования и управления задачами с простым и интуитивным интерфейсом.

## Описание проекта

Планировщик задач представляет собой веб-сервер на Go с фронтендом на HTML/CSS/JavaScript. Приложение позволяет создавать, редактировать, удалять и отмечать задачи как выполненные. Поддерживается повторение задач с различными интервалами (дни, недели, годы).

### Основные возможности:
- Создание и управление задачами
- Поддержка повторяющихся задач
- Автоматический расчет следующей даты для повторяющихся задач
- Простая аутентификация по паролю
- RESTful API для интеграции

## Выполненные задания со звездочкой

- ✅ Реализована аутентификация с JWT токенами
- ✅ Поддержка переменных окружения для настройки
- ✅ Middleware для защиты API endpoints
- ✅ Создание Docker образа для деплоя


### Аутентификация
- `POST /api/signin` - вход в систему

### Задачи
- `GET /api/tasks` - получение списка всех задач
- `GET /api/task?id=<id>` - получение задачи по ID
- `POST /api/task` - создание новой задачи
- `PUT /api/task` - обновление задачи
- `DELETE /api/task?id=<id>` - удаление задачи
- `POST /api/task/done?id=<id>` - отметка задачи как выполненной



