# disk_formatter


>Removing partitions on a drive at the command line using DISKPART
>
Запуск програми для керування дисками.
Launch Disk Management.
```sh
diskpart
```
Відображає всі підключені диски і флеш-накопичувачі.
Displays all connected disks and flash drives.
```sh
list disk
```
Вибираємо номер диску.
Select the disk number.
```sh
select disk 
```
Команда яка видалить всі файли з флешки або жорсткого диска.
A command that will delete all files from a flash drive or hard drive.
```sh
clean
```
Створюємо розділ.
We create a partition.
```sh
create partition primary
```
Вибираємо розділ і акцентуємось на ньому.
We select a section and focus on it.
```sh
select partition 1
```
Позначаємо розділ як активний. 
Mark the section as active.
```sh
active
```
Виконуємо швидве форматування в залежності від типу системи яка потрібна.
We perform quick formatting depending on the type of system that is needed.
```sh
format fs=fat32 quick 
```
```sh
format fs=NTFS quick 
```
```sh
format fs=ExFAT quick
```
Присвоєння літери носієві.
Assigning a drive letter.
```sh
assign
```
Завершення роботи додатка.
Closing the application.
```sh
exit
```





