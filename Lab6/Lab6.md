# Отчет по лабораторной работе №6

## Анализ файловой системы Linux. Команды для работы с файлами и

## каталогами

```
Кузнецов Юрий Владимирович
```
## Содержание

Цель работы ......................................................................................................................................................................... 1

Задание ................................................................................................................................................................................... 1

Выполнение лабораторной работы ...................................................................................................................... 1

Вывод ....................................................................................................................................................................................... 4

## Цель работы

Ознакомление с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобретение практических навыков по применению команд для работы с
файлами и каталогами, по управлению процессами (и работами), по проверке
использования диска и обслуживанию файловой системы.

## Задание

- Выполнить все примеры из первой части
- Копирование заданных файлов в каталоги
- Создание директорий и каталогов
- Перемещение файлов
- Переименование файлов
- Изменение прав доступа к файлам
- Просмотр содержимого файлов
- Работа со справкой man

## Выполнение лабораторной работы

Выполнил примеры из первой части.


Скопировал файл /usr/include/sys/io.h в домашний каталог и назвал его equipment.

Создал директорию ski.plases. Переместил в этот каталог файл equipment.

Переименовал файл в equiplist.

Создал в домашнем каталоге файл abc1, скопировал его в ski.plases, назвал его
‘equiplist2’.

В каталоге ski.plases создал каталог equipment.

Переместил файлы equiplist и equiplist2 в каталог equipment.

Создал каталог newdir и переименовал его в каталоге ski.plases в ‘plans’.

Определил опции команды chmod. Создал нужные файлы.

Присвоил файлу australia права: drwxr—r—

Файлу play: drwx—x—x

Файлу my_os: -r-xr—r—

Файлу feathers: -rw-rw-r—


Просмотрел содержимое файла /etc/passwd (/etc/password не было)

_команды_

Скопировал файл feathers в файл file.old.

Переместил файл file.old в каталог play.

Скопировал каталог play в каталог fun.


Переместил каталог fun в каталог play и назвал его ‘games’.

Лишил владельца файла feathers права на чтение. Попытался просмотреть этот файл,
ничего не вышло. Скопировать тоже не получилось. Вернул владельцу право на чтение.

Лишил владельца каталога play права на выполнение. Все же перейти в каталог я смог.
Права вернул.

Прочитал man по командам mount, fsck, mkfs, kill.

## Вывод

Я удачно ознакомился с файловой системой Linux, её структурой, именами и
содержанием каталогов.

Приобрел практические навыки по применению команд для работы с файлами и
каталогами, по управлению процессами (и работами), по проверке использования
диска и обслуживанию файловой системы.


