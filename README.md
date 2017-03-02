# sfos-init
Here's the mounts from /proc/mounts

rootfs / rootfs rw,seclabel 0 0

tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,size=451312k,nr_inodes=112828,mode=755 0 0

devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0

proc /proc proc rw,relatime 0 0

sysfs /sys sysfs rw,seclabel,relatime 0 0

selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0

tmpfs /tmp tmpfs rw,seclabel,relatime,size=451312k,nr_inodes=112828 0 0

pstore /sys/fs/pstore pstore rw,seclabel,relatime 0 0

adb /dev/usb-ffs/adb functionfs rw,relatime 0 0

/dev/block/mmcblk0p30 /data ext4 rw,seclabel,nosuid,nodev,noatime,data=ordered 0 0

/dev/block/mmcblk0p30 /sdcard ext4 rw,seclabel,nosuid,nodev,noatime,data=ordered 0 0

/dev/block/mmcblk0p24 /cache ext4 rw,seclabel,nosuid,nodev,noatime,data=ordered 0 0

/dev/block/mmcblk1p1 /external_sd ext4 rw,seclabel,relatime,data=ordered 0 0

/dev/block/mmcblk0p23 /system ext4 rw,seclabel,relatime,data=ordered 0 0
