1) Создать группы: developers; qa; interns; managers
Команда такая (не разбирали на занятии)
```
sudo groupadd workers
```
где workers - имя группы
2) Создать пользователей ivanoviv, petrovas, mitinev, fedorovaev, chernyatinskiyss, mavrinsk
3) Распределить пользователей в группы:
ivanoviv, petrovas в developers
fedorovaev -  qa
chernyatinskiyss, mavrinsk - interns
4) Создать пользователя manager, задав ему при создании uid=3000, добавить в группу managers
5) Задать пароли для всех пользователей
6) Создать директорию labs в /opt. В нем создать каталоги library и tests.
7) Создать файлы book_1, book_2, book_3, book_4, book_5 в library
8) Создать текстовый файл for_test в tests
9) Сделать файл for_test исполняемым для группы interns
10) Настроить права доступа к каталогу library так, чтобы члены группы developers могли изменять и создавать там файлы, а пользователи группы interns имели доступ на чтение
11) Сменить права файлу for_test - сделать владельцем fedorovaev, а группой владельцев developers, проверить какие операции над файлом доступны для пользователей fedorovaev, petrovas и mavrinsk
