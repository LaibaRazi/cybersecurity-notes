# nmap — Network Scanner

## What is nmap?
- Network Mapper — scans open ports on any server
- Used by pen testers for reconnaissance (first step)
- Port = door to a server

## Basic Commands
```bash
nmap target.com              # basic scan — top 1000 ports
nmap -sV target.com          # version scan — what software is running
sudo nmap -sV -O target.com  # OS detection — what OS is running
nmap -p 80,443 target.com    # scan specific ports only
nmap -p- target.com          # scan ALL 65535 ports
```

## Reading Results
```
PORT      STATE  SERVICE  VERSION
22/tcp    open   ssh      OpenSSH 6.6.1p1 Ubuntu
80/tcp    open   http     Apache httpd 2.4.7
```
- Port + Version = find exact CVE exploit!

## Common Ports
| Port | Service |
|------|---------|
| 22 | SSH |
| 80 | HTTP |
| 443 | HTTPS |
| 3306 | MySQL |
| 8080 | HTTP alternate |

## Real Use
- Scan target → find open ports → find version → search CVE → exploit!