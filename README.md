# Speedy-Fastest-Live-Port-Scanner
Faster and more stable port scanner than nmap or rustscan to scan for all open ports
This is created to shorten the time of detecting open ports for CTF
place speedy binary in /usr/bin

Usage:

./speedy

choose as option:
1 - check all ports

2 - manual check

>

type in 1 to check all 65535 ports for ipv4 address

type in 2 to check for single port

>1

target ip

>192.168.0.1 (example)
Port 53 is open
Port 45555 is open
Port 80 is open
12% complete
25% complete
38% complete
51% complete
Port 443 is open
64% complete
77% complete
90% complete
#Checking for false positives...
Port 53,45555,80,443 are open!

>2
target ip
>192.168.0.1 (example)

check port
>80
Port 80 is open

Feel free to give suggestions or help to contribute to this tool.
