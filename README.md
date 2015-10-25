# debian-thinkpad
Debian Thinkpad configs and info

# Synapse config - launches with Super Key now
#/home/kory/.config/hotkeys
[hotkey:activate]
Owner=synapse
Signature=Super_L

# fix synapse launch so I can still use super for other combos...

# Filesystem tweaks

# Ramdisks
tmpfs   /tmp    	tmpfs   defaults,noatime,size=2048M     0       0
tmpfs   /var/log        tmpfs   defaults,noatime,size=512M	0	0

# fileserver samba mounts
//IP/SHARE cifs credentials=[redacted location],iocharset=utf8,file_mode=0777,dir_mode=0777 0 0

