# NFS Enumeration

1. NFS allows file sharing across network as if they existed in local system.
2. NMAP Enumeration:
   1. nmap --script=nfs-ls.nse,nfs-showmount.nse,nfs-statfs.nse -p 2049 IP
3. showmount Enumeration:
   1. showmount IP (apt install nfs-common , if not work)
4. Mount NFS:
   1. mount -t nfs -o ver=2 IP:/home /mnt/somedir
5. Reference:
   1. [https://book.hacktricks.xyz/pentesting/nfs-service-pentesting](https://book.hacktricks.xyz/pentesting/nfs-service-pentesting)
