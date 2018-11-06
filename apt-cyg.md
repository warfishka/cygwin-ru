Самый простой способ установки **apt-cyg**

* Правой кнопкой мыши "https://raw.githubusercontent.com/transcode-open/apt-cyg/master/apt-cyg"
* Выбрать "Сохранить ссылку как:"
* Выбарть директорию c:\cygwin\bin (или другой путь установки)
* Убрать .txt расширение, что бы сохранить файл как **apt-cyg**
* Нажать "Сохранить"
* Запустить комманду `chmod` в *cygwin*

```sh
$ apt-cyg install -- установить пакеты
$ apt-cyg remove -- удалить пакеты
$ apt-cyg update -- обновить setup.ini
$ apt-cyg show -- показать установленные пакеты
$ apt-cyg find -- найти пакет по подходящим патернам 
$ apt-cyg describe -- описать пакет по подходящим патернам 
$ apt-cyg packageof -- найти корневой пакет
```
