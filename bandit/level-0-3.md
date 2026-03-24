# OverTheWire Bandit — Level 0 to 5

## Level 0
- Connect via SSH
- Command: `ssh bandit0@bandit.labs.overthewire.org -p 2220`
- Password: `bandit0`

## Level 1
- File named `-` (dash) — cannot use `cat -` directly
- Solution: `cat ./-`
- Why: `./` tells terminal "this is a file, not a flag"

## Level 2
- File has spaces in filename
- Solution: `cat ./--spaces\ in\ this\ filename--`
- Why: `\` escapes the space character

## Level 3
- Hidden file inside `inhere` folder
- Solution: `cd inhere` → `ls -la` → `cat ...Hiding-From-You`
- Why: files starting with `.` are hidden — `ls -la` shows them

## Level 4
- 10 files in `inhere` folder — only one is ASCII text
- Solution: `file ./-*` → find ASCII text file → `cat ./-file07`
- Why: `file` command tells you what type a file is
- `*` wildcard = check all files at once

## Level 5
- 20 folders, password file is 1033 bytes
- Solution: `find . -size 1033c -type f` → `cat ./maybehere07/.file2`
- Why: `find` searches by conditions — size, type, permissions

## Level 8 
- `sort` line by line code sorted
- `uniq` handle duplicated lines



## Commands Learned
- `ssh` — connect to remote server
- `ls -la` — show hidden files
- `cat ./-` — read dash-named file
- `cd` — change directory
- `file ./-*` — check file types with wildcard
- `find . -size 1033c -type f` — find file by size
- `find / -name "password*" 2>/dev/null`