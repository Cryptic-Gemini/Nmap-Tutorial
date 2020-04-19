# Nmap-Tutorial
Basic Nmap commands 

Scan network for connected device(s) with nmap:
------------------------------------------------

#ifconfig

IP= 192.168.100.04

The highlighted IP from the output indicates that our system is using 192.168.100.0 subnet mask and the range is 255. Thus our network IP range is from 192.168.100.0 to 192.168.100.255.


                      $ nmap -sP 192.168.100.0/24
                      
                      
 ref:https://vitux.com/find-devices-connected-to-your-network-with-nmap/
