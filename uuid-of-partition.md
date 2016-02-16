To get uuid of partition in linux

```
ls -l /dev/disk/by-uuid/
```

Result look like
```
lrwxrwxrwx 1 root root 10 Feb 16 15:25 0A9A348A9A347473 -> ../../sdb1
lrwxrwxrwx 1 root root 10 Feb 16 15:25 30f1615c-162d-4104-a76f-b4d0a066ccc1 -> ../../sda5
lrwxrwxrwx 1 root root 10 Feb 16 15:25 558287F42885F703 -> ../../sdb2
lrwxrwxrwx 1 root root 10 Feb 16 15:25 583a3d81-041e-4110-8247-e740d141f570 -> ../../sda1
lrwxrwxrwx 1 root root 10 Feb 16 15:25 7F449A70630C478D -> ../../sda6
lrwxrwxrwx 1 root root 10 Feb 16 15:25 f07b07c8-5257-4f81-b53b-206043a3f75a -> ../../d

```
