# Disk Partitioning Using fdisk

## Commands Used
- lsblk
- fdisk
- mkfs
- mount
- df -h

## Example
```bash
lsblk
fdisk /dev/sdb
mkfs.ext4 /dev/sdb1
mount /dev/sdb1 /data

## Real-World Use Case
Preparing new disks for application data, backups, and log storage.
