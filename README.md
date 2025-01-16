# RabbitMQ: Установка и Начало Работы

## Установка RabbitMQ через Docker

Запустите контейнер RabbitMQ с последней версией `4.0.x` и панелью управления:

```bash
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:4.0-management
