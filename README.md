# 6_sem_coursework

# Currency Rate Web Application

```text
app.py                 - контроллер Flask

model.py               - модель приложения

templates/index.html   - HTML-шаблон

requirements.txt       - зависимости Python

Dockerfile             - инструкция сборки Docker-образа

docker-compose.yml     - конфигурация Docker Compose

---

## Доступ к приложению

После запуска приложение доступно по адресу:

```text
https://currency-rate.ivanova-olga-vds.ru
```

или

```text
http://currency-rate.ivanova-olga-vds.ru:5003
```

в зависимости от используемой конфигурации Nginx и HTTPS.




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
