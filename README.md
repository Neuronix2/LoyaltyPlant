# Loyalty Plant

Тестовое задание

##  JMeter

В папке **perfomance** находится тест-план, выполняющий следующие действия:

- Создание 100 пользователей
- Зачисление на счет некоторой суммы (100 + номер потока)
- Последовательный перевод 50.0 следующему получателю
- Проверка, что баланс каждого аккаунта в порядке (проверяется баланс и сравнивается с тем, что должно быть)
- Удаление пользователей

Все тесты выполняются в 100 потоков. Потоки имеют разное время запуска, что позволяет проверить блокировки

## Запуск
В Unix среде: `sh start.sh`

Веб интерфейс запускается на порту 9000, если не укзано иное