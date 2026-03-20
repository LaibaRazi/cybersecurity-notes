<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1a0000,100:2d0000&height=100&section=header&text=Cybersecurity+Notes&fontSize=35&fontColor=cc0000&animation=fadeIn&fontAlignY=65"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=16&pause=1000&color=CC0000&center=true&vCenter=true&width=600&lines=Learning+Ethical+Hacking+%2F%2F+One+day+at+a+time;Laiba+Razi+Khan+%7C+Karachi%2C+Pakistan;Breaking+In+%7C+Not+Breaking+Down)](https://git.io/typing-svg)

</div>

---

## `whoami`

```
Name     :: Laiba Razi Khan
Path     :: Cybersecurity Student → Penetration Tester
Location :: Karachi, Pakistan
Started  :: March 2026
Goal     :: eJPT → Security+ → OSCP
```

---

<div align="center">

## `// PROGRESS TRACKER`

| Milestone | Status |
|-----------|--------|
| Kali Linux Setup | ✅ Done |
| OverTheWire Bandit | 🔄 Level 3/34 |
| nmap Basics | ✅ Done |
| eJPT Certification | ⏳ In Progress |
| PicoCTF Challenges | ⏳ Starting Soon |
| CompTIA Security+ | ⏳ Upcoming |
| First Bug Bounty Report | ⏳ Upcoming |

</div>

---

## `// WEEK 1 — DAY 1`

### Tools Learned
- **SSH** — connect to remote servers
- **ls** — list files in directory
- **cat** — read file contents
- **nmap** — scan ports on a target

### OverTheWire Bandit
- ✅ Level 0 — SSH connection
- ✅ Level 1 — dash file trick `(./-)`
- ✅ Level 2 — spaces in filename `(./--spaces\ in\ filename--)`
- ✅ Level 3 — hidden files `(ls -la)`

### Key Concepts
```
Ports       = doors to a server
Open port   = entry point for attackers
CTF         = Capture The Flag challenge
Recon       = scan before you attack
```

---

## `// WEEK 1 — DAY 2`

### nmap Advanced Scanning
```bash
nmap target.com              # basic scan — top 1000 ports
nmap -sV target.com          # version scan — what software is running
sudo nmap -sV -O target.com  # OS detection — what OS is running
nmap -p- target.com          # scan ALL 65535 ports
nmap -p 80,443 target.com    # scan specific ports only
```

### Reading nmap Results
```
PORT      STATE  SERVICE  VERSION
22/tcp    open   ssh      OpenSSH 6.6.1p1 Ubuntu
80/tcp    open   http     Apache httpd 2.4.7 (Ubuntu)
9929/tcp  open   nping-echo
31337/tcp open   Elite
```
> Port + Version = find exact CVE exploit 🔴

### nslookup — Finding IP Addresses
```bash
nslookup youtube.com      # get YouTube's IP
nslookup google.com       # get Google's IP
nslookup instagram.com    # get Instagram's IP
```
> YouTube returned 4 different IPs = **Load Balancing**
> One website runs on thousands of servers worldwide

### DNS Fix in Kali
```bash
sudo nano /etc/resolv.conf
# Add this line:
nameserver 8.8.8.8         # Google's DNS server
```

### Key Concepts
```
IP Address    = the house (server location)
URL/Domain    = the room inside the house
Load Balancing = one domain → many servers
DNS           = phone book of the internet
CVE           = known vulnerability with an ID
```

---

<div align="center">

## `// TOOLS ARSENAL`

![Kali Linux](https://img.shields.io/badge/Kali_Linux-cc0000?style=flat-square&logo=kalilinux&logoColor=white)
![nmap](https://img.shields.io/badge/nmap-cc0000?style=flat-square&logo=linux&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-1a1a1a?style=flat-square&logo=gnubash&logoColor=cc0000)
![SSH](https://img.shields.io/badge/SSH-1a1a1a?style=flat-square&logo=openssh&logoColor=cc0000)
![Git](https://img.shields.io/badge/Git-1a1a1a?style=flat-square&logo=git&logoColor=cc0000)

</div>

---

<div align="center">

*"The quieter you become, the more you are able to hear"*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2d0000,50:1a0000,100:0a0a0a&height=60&section=footer"/>

</div>