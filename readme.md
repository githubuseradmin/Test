# RPIIS LAB 1 | Find the biggest file and print info
## Task

Creat SH and BAT, that execute following:
Find the largest file in the folder (selected by the user) and print (txt file) the size of the file, numbers of words, latters and lines.

Input: folder
Output: txt file

> Создать файл sh и bat, который выполняет следующее: 
На вход пакетному файлу приходит абсолютный путь к папке (как параметр пакетного 
файла). Если такой папки нет, то писать “Данной папки нет” и завершить выполнение 
программы. Если такая папка есть, то в ней и ее подкаталогах найти самый большой файл, 
создать файл result.txt и вывести в него размер найденного файла, количество слов, букв и 
строк.

## Usage
### SH
> ./bigfile.sh

or

> bash bigfile.sh
### BAT
> bigfile.bat

## Result and output
As a result of script execution, you get a txt file.

## Example:

### The biggest file

> Hello world<br>
Hello world<br>
Hello world<br>

### result.txt

> Bytes: 36<br>
Words: 6<br>
Characters: 36<br>
Lines: 3<br>

### SH

![SH](https://github.com/githubuseradmin/test/blob/fb348a00c3bcd97ea83c5b03cc8b94eac9046155/sh.png)

### BAT

![cmd](https://github.com/githubuseradmin/test/blob/fb348a00c3bcd97ea83c5b03cc8b94eac9046155/bat.png)
