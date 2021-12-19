# nmap

1. Used for host discovery and network auditing
2. Usage:
   1. nmap -sn ip/mask \[nmap -sn 10.10.10.0/24 or nmap -sn 10.10.10.0-255] - ping scan for host discovery
   2. nmap -sV ip - service discovery
   3. nmap -p- -sV ip - service discovery all ports
   4. nmap -p 80,443 -sV ip - service discovery for mentioned ports
   5. nmap -A ip - os detection,script scanning and traceroute
   6. nmap --script="some\_script" ip - Run nmap specific nmap script
3. Reference:
   1. [https://hackertarget.com/nmap-cheatsheet-a-quick-reference-guide/](https://hackertarget.com/nmap-cheatsheet-a-quick-reference-guide/)
