
Plug in the external USB drive first 

```bash
lsblk
```
The above command will show all the drives that are plugged in to the computers. Among the list of drives find out the id of one which is need to be mounted (started with sda or sdb)

```bash
sudo mount /dev/drive_id /media
```
Now to show the drive -
```bash
cd
cd /media
```

To unmount the drive

```bash
sudo umount /media
```
