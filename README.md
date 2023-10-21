sprint
Документация проекта
Функции проекта
Регистрация пользователей

Авторизация пользователей

Создание, просмотр, обновление и удаление пользователей

Создание, просмотр, обновление и удаление координат

Создание, просмотр, обновление и удаление уровней

Создание, просмотр, обновление и удаление изображений

Создание, просмотр, обновление и удаление перевалов

Примеры использования API
Получение списка пользователей
-GET /api/users/

Создание нового пользователя
-POST /api/users/ { "email": "test@example.com", "phone": "+1234567890", "first_name": "John", "last_name": "Doe", "surname": "Smith" }

Обновление пользователя
-PUT /api/users/1/ { "email": "updated@example.com", "phone": "+1234567890", "first_name": "John", "last_name": "Doe", "surname": "Smith" }

Удаление пользователя
-DELETE /api/users/1/
