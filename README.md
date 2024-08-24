# Online Store

Это проект интернет-магазина, разработанный с использованием Django и PostgreSQL. Он включает в себя функционал для управления отделами и товарами.

## Содержание

- [Функционал](#функционал)
- [Технологии](#технологии)
- [Установка](#установка)
- [Использование](#использование)

## Функционал

- Управление отделами (категориями).
- Добавление, редактирование и удаление товаров в отделах.
- Просмотр списка отделов и связанных с ними товаров.
- Экспортированная копия базы данных для удобства передачи.

## Технологии

- Python
- Django
- PostgreSQL
- HTML/CSS
- Bootstrap (для оформления)

## Установка

1. **Клонируйте репозиторий:**

    ```bash```
    git clone https://github.com/ваш_пользователь/online_store.git
    
    ```bash```
    cd online_store

2. **Создайте и активируйте виртуальное окружение:**

    ```bash```
    python -m venv venv
    
    ```bash```
    .\venv\Scripts\Activate  — Для Windows
    
    ```bash```
    source venv/bin/activate  — Для Linux/Mac
  
4. Установите зависимости:
    
    ```bash```
    pip install -r requirements.txt
   
5. Настройте базу данных:
Убедитесь, что у вас установлен PostgreSQL и создана база данных. Обновите настройки базы данных в файле online_store/settings.py.

6. Примените миграции:

    ```bash```
    python manage.py migrate

7. Запустите сервер:

    ```bash```    
    python manage.py runserver

Теперь вы можете открыть приложение в браузере по адресу http://127.0.0.1:8000.
   
## Использование

Для управления отделами и товарами используйте интерфейс, доступный по адресу http://127.0.0.1:8000/departments/.
Вы можете добавлять, редактировать и удалять отделы и товары через соответствующие кнопки.
