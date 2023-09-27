# disk_formatter


>Removing partitions on a drive at the command line using DISKPART

```sh
diskpart
```
```sh
list disk
```
```sh
select disk N
```
```sh
clean
```
```sh
create partition primary
```
```sh
select partition 1
```
```sh
active
```
```sh
format fs=fat32 quick 
```
```sh
format fs=NTFS quick 
```
```sh
format fs=ExFAT quick
```
```sh
assign
```
```sh
exit
```





