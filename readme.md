# Автоматизация тестирования консольных приложений Linux на Python
## Homework1

### Задание 1.

Условие:
Написать функцию на Python, которой передаются в качестве параметров команда и текст. Функция должна возвращать True, если команда успешно выполнена и текст найден в её выводе и False в противном случае. Передаваться должна только одна строка, разбиение вывода использовать не нужно.

### Задание 2. (повышенной сложности)

Доработать функцию из предыдущего задания таким образом, чтобы у неё появился дополнительный режим работы, в котором вывод разбивается на слова с удалением всех знаков пунктуации (их можно взять из списка string.punctuation модуля string). В этом режиме должно проверяться наличие слова в выводе.

## Homework2

### Задание 1.

Условие:
Дополнить проект тестами, проверяющими команды вывода списка файлов (l) и разархивирования с путями (x).

### Задание 2. (повышенной сложности)

• Установить пакет для расчёта crc32
sudo apt install libarchive-zip-perl
• Доработать проект, добавив тест команды расчёта хеша (h). Проверить, что хеш совпадает с рассчитанным командой crc32.

### Homework3

## Задание 1.

Условие:
Дополнить проект фикстурой, которая после каждого шага теста дописывает в заранее созданный файл stat.txt строку вида:
время, кол-во файлов из конфига, размер файла из конфига, статистика загрузки процессора из файла /proc/loadavg (можно писать просто всё содержимое этого файла).

## Задание 2. (дополнительное задание)

Дополнить все тесты ключом команды 7z -t (тип архива). Вынести этот параметр в конфиг.


### Homework4

## Задание 1.

Условие:
Переделать все шаги позитивных тестов на выполнение по SSH. Проверить работу.

## Задание 2. (дополнительное задание)

Условие:
Переделать все шаги негативных тестов на выполнение по SSH. Проверить работу.