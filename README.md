# BTCWatcher:
## Author: Aisha | Python Developer
## Stack / Technologies used:
- Python
- Docker

### Инструкция по данному проекту
1. Введите в терминале 
```
git clone git@github.com:aishabay/BTCWatcher.git
```

2. Перейдите в директорию данного проекта
```
cd BTCWatcher
```

3. Убедитесь что Docker запущен.
```
docker version
```

4. Создайте и запустите контейнеры
```
docker compose up -d 
```

5. Перейдите по адресу `http://127.0.0.1:5050/` в браузере

6. Остановите и удалите контейнеры
```
docker compose down -v
```