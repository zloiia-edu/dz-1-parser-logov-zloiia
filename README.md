# edu_logparser1
Тестовое задание для ООП Парсер Логов

В этом задании создан скелет программы по архитектуре, которую мы разработали на паре.

# Техническое задание на программу

Существует несколько типов приборов, которые генерируют списки ошибок в виде целых чисел, которые записываются по одной в строке. К примеру
```
12
12
14
21
22
40
1223
```

Типов приборов несколько. Каждый генерирует свой наборы кодов. В каждом коде зашифрована своя ошибка, уникальная для каждого типа устройства. 

Данные могут поступать из файла или из терминала. В файле коды представлены как в описании. 
Необходимо разработать программу, которая бы позволила преобразоывать коды ошибок устройства в строки, понятные пользователю. Пользователь может вводить данные из файла или вручную в терминале. Также необходимо дать пользователю возможность сохранить результаты работы в файл или вывести их в терминал


# Домашнее задание:
* Придумать способ как правильно закончить обработку данных. То есть как остановить поток
* По возможности обработать ситуации ошибок чтения. К примеру, если нам пытаются ввести не целое число.
* `*УСЛОЖНЕННОЕ*` Переделать класс обработчик таким образом, чтобы не приходилось под каждое устройство создавать отдельный класс с зашитыми в него кодами ошибок, а дать возможность конфигурировать таблицу кодов ошибок. То есть чтобы класс-обработчик мог брать таблицу кодов ошибок из файла
* :+1: `*СУПЕР УСЛОЖНЕННОЕ*` Придумать как можно дать пользователю программы возможность самому выбирать тип входного и выходного потока данных. То есть чтобы пользователь мог сам выбирать, хочет он вводить данные в терминал и выводить в файл, или пусть данные берутся из файла и выводятся в терминал или все будет в терминале.