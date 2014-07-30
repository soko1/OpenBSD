-= auto-wifi.sh =-

Info:

/etc/known_wifi - wifi database textfile

Good tweaks:

1.

$ cat /etc/apm/resume 
#!/bin/sh
/bin/sh $PATH_IN_SCRIPT/auto-wifi.sh -i $YOUR_WIFI_INTERFACE -y

2. 

$ cat /etc/hostname.$YOUR_WIFI_INTERFACE
!/bin/sh $PATH_IN_SCRIPT/auto-wifi.sh -i $YOUR_WIFI_INTERFACE -y
