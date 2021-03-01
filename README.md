# UnixTypeOSLab1

## Отчёт по лабораторной работе №1   

по дисциплине "Unix-подобные операционные системы"   
студента группы ПА-18-2   
Рябова Андрея Дмитриевича   
Кафедра Компьютерных Технологий ДНУ 2021/2022

### Постановка задачи:   

Создать отчёт из четырёх частей:
1. Основные файловые системы Windows NT и Unix
2. При помощи ПО для выполения операций над разделами жёсткого диска проанализировать структуру своего диска
3. Популярные дистрибутивы Linux
4. Описать в каких сферах Unix-подобные ОС используютя чаще всего

### Выполнение:   

#### Основные файловые системы Windows NT и Unix:   

##### Windows NT   

Windows NT 4.0 поддерживает две файловые системы: существовавшую ранее файловую систему FAT и собственную, новую файловую систему NTFS. (Все предыдущие версии поддерживали также файловую систему HPFS, разработанную для операционной системы OS/2 версии 1.х.)

##### 1. FAT   

FAT (англ. File Allocation Table «таблица размещения файлов») — классическая архитектура файловой системы, которая из-за своей простоты всё ещё широко применяется для флеш-накопителей. Используется в дискетах, картах памяти и некоторых других носителях информации. Ранее находила применение и на жёстких дисках.

Разработана Биллом Гейтсом и Марком МакДональдом (англ.) в 1976—1977 годах. Использовалась в качестве основной файловой системы в операционных системах семейств MS-DOS и Windows 9x.

Существует четыре версии FAT — FAT12, FAT16, FAT32 и exFAT (FAT64). Они отличаются разрядностью записей в дисковой структуре, то есть количеством бит, отведённых для хранения номера кластера.

##### 2. NTFS   

NTFS (аббревиатура от англ. new technology file system — «файловая система новой технологии») — стандартная файловая система для семейства операционных систем Windows NT фирмы Microsoft.

NTFS поддерживает хранение метаданных. С целью улучшения производительности, надёжности и эффективности использования дискового пространства для хранения информации о файлах в NTFS используются специализированные структуры данных.

Файловая система NTFS заменила файловую систему FAT, использовавшуюся в ОС MS-DOS и ОС Windows.

Файловая система NTFS разработана на основе файловой системы HPFS. HPFS — аббревиатура от англ. high performance file system — высокопроизводительная файловая система, разработку которой вела фирма Microsoft совместно с фирмой IBM для операционной системы OS/2.

##### Unix

##### 1. UFS
Unix File System (UFS) — файловая система, созданная для операционных систем семейства BSD и используемая в переработанном и дополненном виде на данный момент как основная в операционных системах-потомках (FreeBSD, OpenBSD, NetBSD).

Поддержка данной файловой системы имеется также в ядре Linux и операционной системе Solaris.

Пользователи некоторых коммерческих Unix систем, таких как Solaris, HP-UX и Tru64 UNIX, приняли UFS. Большинство из них перевело системы на UFS, добавило проприетарные дополнения, из-за которых пользователи других версий UNIX могли не распознать UFS. Удивительно, но многие из них продолжают использовать оригинальный размер блока данных и ширину блока, как и в оригинальной UFS, так что некоторая степень совместимости на разных платформах остается. Совместимость между реализациями неполная, в лучшем случае, и должна быть исследована перед использованием на нескольких платформах.

##### 2. System V

System V (произносится как англ. System five, AT&T UNIX System V) — одна из версий операционной системы Unix, разработанная в AT&T и выпущенная в 1983 году.

Было выпущено четыре основные версии — 1, 2, 3 и 4. Версия System V Release 4 (SVR4) была наиболее удачной и популярной. Многие Unix-подобные системы переняли от неё, например, сценарии инициализации системы — «SysV init scripts» (сценарии, размещаемые в каталоге /etc/init.d) — отвечающие за запуск системы и её выключение, и System V Interface Definition (SVID) — стандарт, описывающий работу системы System V.

#### Исследование структуры диска:

![image](https://user-images.githubusercontent.com/43186510/109475423-6130fb00-7a7e-11eb-9d01-58bd9518273f.png)

