# OC_1
Лабораторная работа №1
## Что нужно уметь
1. монтировать/размонтировать файловую систему
2. выводить информацию о подмонтированных дисках (чтобы было видно тип файловой системы)
3. создавать файловые системы (форматирование)
4. создавать разделы
5. проверять файловые системы
## В своей виртуальной машине сделать
1. создать виртуальный диск (скриншот доступных дисков в отчет)
2. на этом диске создать 8 разделов (размером N Мбайт, N-последние три цифры в номере зачетки) используя MBR запись (не GPT) (скриншот доступных разделов на диске в отчет)
3. на одном из разделов создать файловую систему NTFS (размер блока (байт) (256) 1024, 2048, 4096 (65536) самый близкий размер к последней цифре в номере зачетки) (скриншоты команды форматирования и информации о файловой системе в отчет)
4. на одном из разделов создать файловую систему FAT32  (скриншоты команды форматирования и информации о файловой системе в отчет)
5. на одном из разделов создать файловую систему EXT2 (размер блока (байт) 1024, 2048, 4096 самый близкий размер к последней цифре в номере зачетки) (скриншоты команды форматирования и информации о файловой системе в отчет)
6. на одном из разделов создать файловую систему EXT3, включить журналирование данных (не только метаданных) (размер блока (байт) 1024, 2048, 4096 самый близкий размер к последней цифре в номере зачетки) (скриншоты команды форматирования и информации о файловой системе в отчет)
7. на одном из разделов создать файловую систему EXT4, включить журналирование данных (не только метаданных) (размер блока (байт) 1024, 2048, 4096 самый близкий размер к последней цифре в номере зачетки) (скриншоты команды форматирования и информации о файловой системе в отчет)
8. на одном из разделов создать файловую систему Btrfs (скриншоты команды форматирования и информации о файловой системе в отчет)
9. на одном из разделов создать файловую систему xfs (скриншоты команды форматирования и информации о файловой системе в отчет)
10. монтировать все разделы в подкаталоги каталога /mnt/фамилия/название файловой системы (скриншот подмонтированных разделов с колонкой "тип файловой системы" в отчет)
11. сделать автоматическое монтирование при загрузке, используя UUID дисков (скриншот fstab в отчет)
12. на одном из разделов создать файловую систему для SWAP (скриншот разделов на диске в отчет)
13. выполните проверку раздела с файловой системой EXT2  (скриншот результата проверки в отчет)
## Что надо изучить
1. диски
2. файловые системы
3. сектор
4. MBR
5. разделы
6. блоки
7. кластеры
8. суперблок
9. процесс загрузки системы
