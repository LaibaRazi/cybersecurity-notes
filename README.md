# Cybersecurity Notes — Laiba Razi Khan

## Week 1 — Day 1

### Tools Learned
- SSH — remote server connect karna
- ls — files dekhna
- cat — file padhna
- nmap — ports scan karna

### OverTheWire Bandit
- Level 0 complete
- Level 1 complete — dash file trick (./)
- Level 2 complete — spaces in filename
- Level 3 complete — hidden files (ls -la)

### Concepts
- Ports = darwaze
- Open port = entry point
- CTF = Capture The Flag game
- Reconnaissance = target ko pehle scan karna

## Week 1 — Day 2

### nmap Advanced
- nmap -sV = version scan, exact software version pata chalta hai
- sudo nmap = root permission chahiye OS detection ke liye
- IP directly use kar sakte hain domain ki jagah
- Example: sudo nmap -sV 45.33.32.156

### nmap Results Samajhna
- PORT 22 = SSH — OpenSSH 6.6.1p1 Ubuntu
- PORT 80 = HTTP — Apache httpd 2.4.7
- OS = Linux Ubuntu
- Version se pata chalta hai kaunsa CVE exploit kaam karega!

### nslookup
- nslookup youtube.com = YouTube ke IPs nikale
- YouTube ke 4 alag IPs = Load Balancing
- Load Balancing = ek website hazaron servers pe chalti hai
- IP = website ka ghar, URL = ghar ka kamra

### DNS
- /etc/resolv.conf = DNS settings file
- nameserver 8.8.8.8 = Google DNS
- nano editor se file edit ki

### Concepts
- Ports + Version = pen tester ko exact exploit dhundne mein help karta hai
- nmap basic vs advanced scan fark samjha