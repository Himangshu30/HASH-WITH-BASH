# HASH WITH BASH


### Dependencies
On a debian machine with MATE desktop, I haven't installed anything specific. For interactive menus and messages, `zenity` is used. If you don't have `zenity`, please install it.

### Installation:

    Make sure that the script files have executable permission.


### Details of each script is given below

# Checksum

View the checksum`(md5sum, sha1sum, sha256sum, sha512sum)` of any file 

# Open Terminal

Open `mate-terminal` from any location.

# Unmount FUSE volumes

This script can unmount any fuse mounts *(sshfs/encfs)* mounts . Once executed, the script will show a list of fuse mounts, and the user can select the one he wish to unmount.



There are two workarounds I found in the Internet, but I dont like any of them
1. Open terminal and execute `fusermount -u <mountpoint>`.

    If Caja supports mounting the sshfs from GUI, it should be removable from GUI. It should be that simple.
