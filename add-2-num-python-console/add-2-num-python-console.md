---
date: 2021-08-23
categories: [it, programming]
tags: [Python, Сложение двух чисел, Установка]
---

# Сложение двух чисел в Python через консоль и блокнот

Для работы с Python после его установки можно не устанавливать никаких других программ (PyCharm, VSCode, Wing и др.), а воспользоваться обычным блокнотом.

## Установка программы

Вначале надо установить Python себе на компьютер. Смотрите статью [Установка Python](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-python/install-python.md).

## Создание проекта

Вместо навороченных сред программирования откроем обычный блокнот:

![Блокнот](img/notepad.png)

## Написание кода

Напишем программу сложения двух чисел:

```python
a = int(input("Введите первое число "))
b = int(input("Введите второе число "))
c = a + b
print("Сумма =", c)
```

![Код программы](img/code.png)

Сохраним файл куда-нибудь. Я для примера сохранил под именем `add2num.py` в папке `C:\projects`:

![Сохранение файла](img/save_01.png)

![Выбор места хранения и названия файла](img/save_02.png)

То есть полный путь к файлу у меня такой `C:\projects\add2num.py`.

## Запуск программы

Нам нужна командная строка, терминал или что-нибудь в этом роде. Покажу, как открыть обычную командную строку через поиск в Windows:

![Открытие командной строки через поиск](img/cmd_01.png)

![Открытая командная строка](img/cmd_02.png)

Теперь просто пропишем такую команду и нажмем `Enter`:

```console
python C:\projects\add2num.py
```

![Запуск Python скрипта](img/run.png)

Если у вас путь к сохраненному файлу с кодом другой, то поменяйте в примере вызова этот путь. Если вдруг не сработает, то попробуйте такой вариант:

```console
python3 C:\projects\add2num.py
```

После запустится программа, где мы можете ввести два числа и посмотреть на результат их суммирования:

![Запущенное приложение](img/result_01.png)

![Результат выполнения программы](img/result_02.png)
