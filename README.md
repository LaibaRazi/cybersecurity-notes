# Cybersecurity Notes — Laiba Razi Khan

## Week 1 — Day 1

### Tools Learned
- SSH — connect to remote servers
- ls — list files in directory
- cat — read file contents
- nmap — scan ports on a target

### OverTheWire Bandit
- Level 0 complete
- Level 1 complete — dash file trick (./)
- Level 2 complete — spaces in filename
- Level 3 complete — hidden files (ls -la)

### Concepts
- Ports = doors to a server
- Open port = entry point for attackers
- CTF = Capture The Flag challenge
- Reconnaissance = first step, scan before you attack

## Week 1 — Day 2

### nmap Advanced
- nmap -sV = version scan, reveals exact software version
- sudo nmap = root permission required for OS detection
- Can use IP directly instead of domain name
- Example: sudo nmap -sV 45.33.32.156

### Reading nmap Results
- PORT 22 = SSH — OpenSSH 6.6.1p1 Ubuntu
- PORT 80 = HTTP — Apache httpd 2.4.7
- OS = Linux Ubuntu
- Version info helps find exact CVE exploits!

### nslookup
- nslookup youtube.com = reveals YouTube's IP addresses
- YouTube has 4 different IPs = Load Balancing
- Load Balancing = one website runs on thousands of servers
- IP = the house, URL = the room inside the house

### DNS
- /etc/resolv.conf = DNS configuration file
- nameserver 8.8.8.8 = Google's DNS server
- Edited file using nano editor

### Key Concepts
- Port + Version = helps pen tester find exact exploit
- Difference between basic and advanced nmap scan