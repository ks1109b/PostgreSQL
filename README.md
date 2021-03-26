# PostgreSQL

### Задача:
Необходимо подготовить приложение к тестированию на СУБД PostgreSQL.

### Приложение: [db-api.jar](https://github.com/netology-code/aqa-homeworks/raw/aqa4/docker/db-api.jar)

### Процесс:
- запускаем docker-compose командой: ```docker-compose -f docker-compose.yml up -d```
- дожидаемся запуска postgresql
- запускаем приложение командой: ```java -jar db-api.jar```
- проверяем результат путем запроса: ```GET http://localhost:9999/api/cards```

### Результат:
![Screenshot_20](https://user-images.githubusercontent.com/73786860/112627407-a01a5c80-8e42-11eb-804c-faeee0b86b70.jpg)
