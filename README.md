1.run ip a command to get the ip address

2.run nmap command along with the options to find the open ports in the ip < nmap -sS  -p- 10.0.2.15 >. 
-sS to perform the TCP syn scan. -p- to perform the port scan.

3.result-

nmap -sS  -p- 10.0.2.15 
Starting Nmap 7.95 ( https://nmap.org ) at 2025-05-26 04:56 EDT
Nmap scan report for 10.0.2.15
Host is up (0.0000090s latency).
All 65535 scanned ports on 10.0.2.15 are in ignored states.
Not shown: 65535 closed tcp ports (reset)

Nmap done: 1 IP address (1 host up) scanned in 2.05 seconds

4.conclusion-

all the ports are in ignored state. all the ports are closed, no open ports found.
