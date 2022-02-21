# Pine phone custom utils

Keep a repo to keep track of pine phone scripts I make.

## Fstab Example for mounting sd card to home directory

```
UUID=BIGLONGUUID  /mnt/external       ext4 defaults      0 0
/mnt/external/Music /home/USERNAME/Music none defaults,bind 0 0
/mnt/external/Downloads /home/USERNAME/Downloads none defaults,bind 0 0
/mnt/external/Pictures /home/USERNAME/Pictures none defaults,bind 0 0
/mnt/external/Documents /home/USERNAME/Documents none defaults,bind 0 0
/mnt/external/Videos /home/USERNAME/Videos none defaults,bind 0 0
```

Replace BIGLOGUUID with UUID found with sudo blkid

Replace USERNAME with username on pinephone. 
