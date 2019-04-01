# WiFi_Check

This is a fork of [mharizanov - WiFi_Check](https://github.com/mharizanov/WiFi_Check).

Few small changes have been made to make it work when the `wlan0` interface is not listed in the `/etc/network/interfaces` file.



### Purpose:
Script checks to see if WiFi has a network IP and if not restart the WiFi.

Uses a lock file which prevents the script from running more
than one at a time.  If lockfile is old, it removes it.

For more info:  
http://rpi.tnet.com/project/scripts/wifi_check



### Acknowledgements:

* [fossfredom user on "SIOCSIFFLAGS"](https://askubuntu.com/questions/62166/siocsifflags-operation-not-possible-due-to-rf-kill)

