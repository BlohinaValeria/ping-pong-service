# Ping-Pong Microservice

Микросервис на Python/Flask с Docker Compose.

## Запуск
docker-compose up -d

## Проверка

curl http://localhost:5001/ping

curl http://localhost:5002/ping

curl http://localhost:5003/ping

## Остановка
docker-compose down

## Демо

http://178.255.126.171:5001/ping

http://178.255.126.171:5002/ping

http://178.255.126.171:5003/ping

## Пример ответа
{"service":"ping-service-5001","response":"pong-from-port-5001","port":5000,"timestamp":"2026-06-03"}

## Технологии
Python + Flask + Docker + Docker Compose
EOF
![1](https://github.com/BlohinaValeria/ping-pong-service/blob/main/pingpong.png)

