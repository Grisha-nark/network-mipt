# Задание 1

Реализовать консистентный протокол, имитирующий TCP и работающий поверх UDP.

Для решения задачи необходимо изменить класс `MyTCPProtocol` в файле `protocol.py`.

Для проверки решения следует запустить ко `test.sh`. Все необходимые Python зависимости можно найти в файле `requirements.txt`

## Запуск при помощи docker
```
docker compose up --build
```

## Локальный запуск
Работает только на Linux, для подробностей см. [HOWTO.md](HOWTO.md)

## Оценивание

За задание можно получить до 3 баллов. Оценка складывается из тестов, пройденных решением:

* `test_small_*` - 0.5 балла
* `test_high_*` - 0.5 балла
* `test_large_message` - 1 балл
* `test_perfomance` - 1 балл, засчитывается только при прохождении всех остальных тестов.