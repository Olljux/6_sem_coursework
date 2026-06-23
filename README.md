# 6_sem_coursework

# Веб-приложение для отслеживания курсов валют Центрального банка Российской Федерации.

Приложение разработано на Python с использованием Flask и архитектуры MVC. Для хранения данных используется база данных SQLite.

Репозиторий содержит:

app.py — контроллер Flask-приложения;
model.py — модель приложения и работа с базой данных;
templates/index.html — HTML-шаблон интерфейса;
requirements.txt — список зависимостей;
Dockerfile — файл сборки Docker-образа;
docker-compose.yml — конфигурация Docker Compose;
README.md — описание проекта.

## Доступ к приложению
Приложение доступно по адресу: https://currency-rate.ivanova-olga-vds.ru/

## Запуск приложения

1. Клонировать репозиторий:

```bash
git clone https://github.com/Olljux/6_sem_coursework
```

2. Перейти в папку проекта:
```bash
cd 6_sem_coursework
```

4. Собрать Docker-образ:
```bash
docker compose build
```

5. Запустить контейнер:
```bash
docker compose up -d
```
