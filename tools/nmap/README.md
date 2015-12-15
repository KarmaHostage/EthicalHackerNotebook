#nmap

###What it is

> TODO

###Example Usages
---

**Do a verbose traceroute scan of the following host name**

    nmap -v -A scanme.nmap.org

**Probe open ports to determine service/version information**

    nmap -v -sV 192.168.1.1

**Do a OS-discovery scan**

    nmap -O localhost

**Do a scriptscan**

    nmap -sC localhost

**Specify specific ports**

    nmap -p1-65535 localhost

**Different Scan Techniques**

    -sS/sT/sA/sW/sM: TCP SYN/Connect()/ACK/Window/Maimon scans
    -sU: UDP Scan
    -sN/sF/sX: TCP Null, FIN, and Xmas scans
    -sI <zombie host[:probeport]>: Idle scan
    -sY/sZ: SCTP INIT/COOKIE-ECHO scans
    -sO: IP protocol scan
