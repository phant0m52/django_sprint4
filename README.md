

2. Переход в директорию django_sprint4

```
cd django_sprint4
```

3. Создание виртуального окружения

```
python -m venv venv
```

4. Активация виртуального окружения

```
source venv/Scripts/activate
```

5. Обновите pip

```
python -m pip install --upgrade pip
```

6. Установка зависимостей

```
pip install -r requirements.txt
```

7. Применение миграций

```
python manage.py migrate
```

8. Загрузить фикстуры в БД

```
python manage.py loaddata db.json
```

9. Создать суперпользователя

```
python manage.py createsuperuser
```

10. Запуск проекта, введите команду

```
python manage.py runserver
```


