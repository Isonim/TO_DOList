**Подготовка проекта**:

1. клонируйте репозиторий
2. Перейдите в копированную папку
3. Делайте composer install
4. Копируйте .env.example файл и создавайте .env, после этого создавайте sqlite базу данных, назовите его как вы хотите.
5. Делаем migration для столбцов
  php artisan migrate
6. Генерируем ключ
  php artisan key:generate
7. Делаем npm install
  npm install
  
**Запускаем сервер**:
1. Запускайте эту команду:
php artisan serve

2. Для фронтенд части запускаем эту команду:
npm run hot

**После всего переходите на http://localhost:8000 и ваш приложение готов к использованию.**
