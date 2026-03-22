<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1a0000,100:2d0000&height=100&section=header&text=Cybersecurity+Notes&fontSize=35&fontColor=cc0000&animation=fadeIn&fontAlignY=65"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=16&pause=1000&color=CC0000&center=true&vCenter=true&width=600&lines=Learning+Ethical+Hacking+%2F%2F+One+day+at+a+time;Laiba+Razi+Khan+%7C+Karachi%2C+Pakistan;Breaking+In+%7C+Not+Breaking+Down)](https://git.io/typing-svg)

</div>

---

## `// PROGRESS`

| Milestone | Status |
|-----------|--------|
| Kali Linux Setup | ✅ Done |
| OverTheWire Bandit | 🔄 Level 5/34 |
| nmap Basics | ✅ Done |
| PicoCTF Challenges | ⏳ Starting Soon |
| eJPT Certification | ⏳ Upcoming |
| CompTIA Security+ | ⏳ Upcoming |
| First Bug Bounty Report | ⏳ Upcoming |

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
- ✅ Level 2 — spaces in filename
- ✅ Level 3 — hidden files `(ls -la)`

### Key Concepts
- Ports = doors to a server
- Open port = entry point for attackers
- CTF = Capture The Flag challenge
- Reconnaissance = scan before you attack

---

## `// WEEK 1 — DAY 2`

### nmap Advanced
```bash
nmap -sV target.com          # version scan
sudo nmap -sV -O target.com  # OS detection
nmap -p 80,443 target.com    # specific ports only
```

### nslookup
```bash
nslookup youtube.com         # returns multiple IPs = Load Balancing
```

### Key Concepts
- IP Address = the house (server location)
- URL = the room inside the house
- Load Balancing = one domain, many servers
- DNS = phone book of the internet
- CVE = known vulnerability with an ID

---

## `// WEEK 1 — DAY 3`

### OverTheWire Bandit Continued
- ✅ Level 4 — `file ./-*` to find ASCII text file among binary files
- ✅ Level 5 — `find . -size 1033c -type f` to find file by size

### find Command
```bash
find . -size 1033c -type f       # find file by exact size
find . -type f -name "*.txt"     # find all .txt files
find . -type f -empty            # find empty files
find . -type f -perm 777         # find files with specific permissions
find . -mtime -1                 # files modified in last 24 hours
find . -type f -size +1M         # files larger than 1MB
find / -type f -name "*.conf"    # find config files (may contain passwords!)
```

### file Command
```bash
file ./-*        # check file type of all files starting with dash
file ./-file*    # same result using wildcard
```
> Returns: data (binary) or ASCII text — password is always in ASCII text file!

### Wildcards
- `*` = anything
- `-*` = everything starting with dash
- `*.txt` = all txt files

### Key Concepts
- Binary files = not human readable = not the password
- ASCII text = human readable = password lives here!
- `find` is used in real pen testing to locate config files, passwords, and sensitive data

---

<div align="center">

![Kali Linux](https://img.shields.io/badge/Kali_Linux-cc0000?style=flat-square&logo=kalilinux&logoColor=white)
![nmap](https://img.shields.io/badge/nmap-cc0000?style=flat-square&logo=linux&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-1a1a1a?style=flat-square&logo=gnubash&logoColor=cc0000)
![SSH](https://img.shields.io/badge/SSH-1a1a1a?style=flat-square&logo=openssh&logoColor=cc0000)
![Git](https://img.shields.io/badge/Git-1a1a1a?style=flat-square&logo=git&logoColor=cc0000)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2d0000,50:1a0000,100:0a0a0a&height=60&section=footer"/>

</div>
