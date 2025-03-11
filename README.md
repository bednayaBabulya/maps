<<<<<<< HEAD
# Проект: Интерактивное планирование маршрутов

## Описание
Этот проект представляет собой веб-приложение на Yii2, предназначенное для создания, планирования и публикации маршрутов с интеграцией API Яндекс.Карт. Пользователи могут взаимодействовать с контентом, просматривать информацию о достопримечательностях, а компании могут публиковать маршруты с пометкой.

## Функционал
### Регистрация и авторизация
- **Частные лица**: регистрация и авторизация по имени, email и паролю.
- **Компании**: расширенная регистрация с указанием названия, юридического адреса, ИНН, сайта и контактного лица.
- **Верификация компаний**: администратор проверяет компанию перед присвоением статуса «Верифицирована».

### Интерактивная карта и маршруты
- **Используется API Яндекс.Карт** для отображения карты.
- **Создание маршрутов** с выбором стартовой и конечной точек.
- **Добавление заметок, фото и описаний** к маршрутам.

### Интеграция внешних API
- **Погодные условия и трафик**: отображение актуальной информации.
- **Данные о достопримечательностях** через внешние сервисы.

### Публикации и контент
- **Создание и сохранение маршрутов** с возможностью делиться ими.
- **Публикации от турфирм** с отметкой «Компания».
- **Фильтрация контента**: можно выбирать маршруты от частных лиц или турфирм.

### Мобильная адаптация
- Адаптивный дизайн для комфортного использования на ПК и мобильных устройствах.

## Установка и запуск
### Требования
- PHP 8.0+
- MySQL 5.7+
- Composer
- Yii2 (Basic или Advanced)

### Установка
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/username/repository.git
   cd repository
   ```
2. Установите зависимости:
   ```bash
   composer install
   ```
3. Настройте файл конфигурации `.env` или `config/db.php` (если используется advanced template).
4. Выполните миграции базы данных:
   ```bash
   php yii migrate
   ```
5. Запустите локальный сервер:
   ```bash
   php yii serve
   ```

## Лицензия
Этот проект распространяется под лицензией MIT.

## Контакты
Автор: Никита Сергеевич Беляев