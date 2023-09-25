## Launch a backup

```
systemctl start __APP__-backup
```

## Launch a metadata backup check

```
systemctl start __APP__-check
```

## Launch a complete backup check

WARNING: this will read data from your backups destination server.
It may take a quite long time depending on the target server's internet upload speed and hardware performance.

```
systemctl start __APP__-check-read-data
```
