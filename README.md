# ArchSettings
This is the Settings that is related to arch linux

## udev rules
- Zram 16GB (add `/dev/zram0 none swap defaults,pri=100 0 0` in `/etc/fstab` for it to work)

## makepkg.conf.d
- MAKEFLAGS to use all cpu cores
