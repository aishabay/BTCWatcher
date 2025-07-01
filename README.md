# BTCWatcher
## Author: Aisha | Python Developer
## Stack / Technologies used:
- Python
- Docker

## Project Description
This project is a full-stack application that tracks the real-time price of Bitcoin (BTC) in USD using Binance’s public API. The backend periodically fetches the BTC/USDT price every 5 seconds and stores the data in a MongoDB database. The frontend visualizes this price data in the form of a dynamic graph, allowing users to monitor Bitcoin’s price changes over time.

## Инструкция по данному проекту
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
