# API Overview

## GET /api/movies
Повертає список фільмів.

## GET /api/movies/{id}
Деталі одного фільму.

## POST /api/review
Створення нового відгуку.

Приклад:
```json
{ "movieId": 1, "user": "vova", "review": "Класний фільм" }
