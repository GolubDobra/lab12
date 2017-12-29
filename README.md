# lab12
[![Build Status](https://travis-ci.org/GolubDobra/lab12.svg?branch=master)](https://travis-ci.org/GolubDobra/lab12)

## Задание:
Написать программу на *C++* обеспечивающую асинхронный запрос по заданному *URL* к *HTTPS* серверу на получение кода доступа. Для создания асинхронного запроса необходимо использовать следующие примитивы многопоточного программирования: `std::thread` для управления потоком и `std::promise` для асинхронной обработки кода ответа.
Передача аргумента происходит через командную строку.

## Terminal:
```ShellSession
$ ./main https://main.ru
Redirect to: https://main.ru/
Код ответа: 200
```
