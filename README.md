
# mac_changer
_____________________________________________________________

>XX          +-+-+-+ +-+-+-+-+-+-+-+-+           XX
>XX          |M|a|c| |c|h|a|n|g|e|r|!|           XX
>XX      +-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+     XX
>XX      |c|r|e|a|t|e|d| |b|y| |Z|i|g|M|u|d|     XX
>XX      +-+-+-+-+-+-+-+ +-+-+ +-+-+-+-+-+-+     XX

Current MAC = 00:11:22:25:21:11
[+] Changing MAC address for eth0 to 00:11:22:25:21:11
[+] MAC address was successfully changed to 00:11:22:25:21:11
_______________________________________________________________

A simple python script to change mac address easily
# what can this script do! :

1 -> show your logo in terminal
2 -> show your current mac address
3 -> change your mac address custumly

You are welcom to contribute :-)

# how to run the script :

type in terminal your interface which you want to change for wlan0 will be following line in terminal: 

> python mac_changer.py -i wlan0 -m 00:00:00:00:00:00

if you need more help, you can type in terminal following command:
 > python mac_changer --help

where: 

-i (your interface: wlan1/wlan0/eth0)
-m (new mac address)
-h (help)
OR
--interface
--new_mac
--help
