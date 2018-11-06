## Установка
Самый простой способ установки **apt-cyg**

1. Правой кнопкой мыши "https://raw.githubusercontent.com/transcode-open/apt-cyg/master/apt-cyg"
2. Выбрать "Сохранить ссылку как:"
3. Выбрать директорию c:\cygwin\bin (или другой путь установки)
4. Убрать .txt расширение, что бы сохранить файл как **apt-cyg**
5. Нажать "Сохранить"
6. Выполнить комманду `chmod +x /bin/apt-cyg` в *cygwin*

* Обновляем последний setup.ini
```sh
$ apt-cyg update
```

## Устанавливаем полезные пакеты:

```sh
$ apt-cyg install openssh git curl perl python3
$ apt-cyg update
```

## Памятка


+ `$ apt-cyg install` -- установить пакеты
+ `$ apt-cyg remove` -- удалить пакеты
+ `$ apt-cyg update` -- обновить setup.ini
+ `$ apt-cyg show` -- показать установленные пакеты
+ `$ apt-cyg find` -- найти пакет по подходящим патернам 
+ `$ apt-cyg describe` -- описать пакет по подходящим патернам 
+ `$ apt-cyg packageof` -- найти корневой пакет
