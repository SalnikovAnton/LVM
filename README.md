# LVM
На имеющемся образе centos/7 - v. 1804.2
1) Уменьшить том под / до 8G
2) Выделить том под /home
3) Выделить том под /var - сделать в mirror
4) /home - сделать том для снапшотов
5) Прописать монтирование в fstab. Попробовать с разными опциями и разными
файловыми системами ( на выбор)
Работа со снапшотами:
- сгенерить файлы в /home/
- снāть снапшот
- удалить часть файлов
- восстановиться со снапшота
