** QEMU Raspberry PI rootfs image for testing purposes **  

The differences from the original images are as follows:
* userconf.txt was added to the boot partition 
  in order to skip initial setup. 
* /lib/systemd/system/getty@.service and /etc/passwd were
  changed to allow root login by default without a password.
