# NetBIOS Enumeration

1. Scan Network for hosts:
   1. nbtscan -r 192.168.0.1/24
   2. nbtscan IP -vh \[netbios enumeration with service detection in human readable format]
   3. nmap -sV IP --script nbstat.nse -v
2. Reference:
   1. [https://null-byte.wonderhowto.com/how-to/enumerate-netbios-shares-with-nbtscan-nmap-scripting-engine-0193957/](https://null-byte.wonderhowto.com/how-to/enumerate-netbios-shares-with-nbtscan-nmap-scripting-engine-0193957/)
