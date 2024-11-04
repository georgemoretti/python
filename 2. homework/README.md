Задание 1

Создайте функцию, которая будет открывать файл, считывать его содержимое и выводить на экран только те строки, которые содержат числовые значения. Если файл не найден, должно возникнуть исключение FileNotFoundError, если внутри файла попалось значение отличное от числа, должно возникнуть исключение TypeError. Файл должен иметь текстовый формат.

Для считывания данных из файла можно воспользоваться следующим программным кодом:

with open('data.txt', 'r', encoding='utf-8') as file:
    data = file.readlines()
print(data)  # обратите внимание на \n