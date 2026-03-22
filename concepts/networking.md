

```markdown
# Networking Concepts

## IP Address
- Every device/server has an IP address
- IP = the house (server location)
- URL/Domain = the room inside the house
- Example: google.com = 142.250.180.46

## DNS (Domain Name System)
- Phone book of the internet
- Converts domain names to IP addresses
- Example: youtube.com → 172.217.215.136
- Config file in Linux: `/etc/resolv.conf`
- Google DNS: `8.8.8.8`

## Ports
- Doors to a server
- Every server has 65535 ports
- Open port = entry point for attackers
- Common ports:
  - 22 = SSH
  - 80 = HTTP
  - 443 = HTTPS
  - 3306 = MySQL database

## Load Balancing
- One domain → many servers
- Example: YouTube has 4+ different IPs
- Why: handle millions of users at once

## Commands
- `nslookup youtube.com` — find IP of any website
- `ping 8.8.8.8` — test internet connection
- `nmap target.com` — scan open ports
- `nmap -sV target.com` — scan + find versions
```
