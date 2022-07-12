# CheatSheets
Cheat sheets(Linux/MacOS/Win)

# Linux Command Cheatsheet:

## => Linux keyboard shortcut commands:
### Keyboard shortcuts to help when making small errrors/adjustments in your terminal while typing out a command.
- ctrl + a = move to begining of terminal
- ctrl + e = move to end of of terminal
- ctrl + u = remove anything before curser
- ctrl + y = return what was deleted from previous command
- ctrl + k  = remove anything after curser
- alt + backspace = remove the last word
- ctrl + x + e = open and edit command in default text editor

## => Terminal:
1. tail -f file-name = To Follow enteries into a file in realtime.
2. ifconfig | grep inet  = To view network configuration and grep out "inet" that will return inet <ip>:
 * inet 127.0.0.1 netmask 0xff000000 
 * inet6 ::1 prefixlen 128 
 * inet6 fe80::1%lo0 prefixlen 64 scopeid 0x1 
 * inet6 fe80::10b4:b28c:d6ac:8ff5%en0 prefixlen 64 secured scopeid 0x4 
 * inet 10.0.1.10 netmask 0xffffff00 broadcast 10.0.1.255
 * inet6 fe80::5846:cdff:fec5:2914%awdl0 prefixlen 64 scopeid 0x9
 * inet6 fe80::72fe:5a67:f907:c962%utun0 prefixlen 64 scopeid 0xa
 * inet6 fe80::ad7:28b0:4cd7:65a4%utun1 prefixlen 64 scopeid 0xb

## => Installing Docker:
- sudo apt install docker docker.io docker-compose -y = Installing docker
- sudo systemctl start docker && sudo systemctl status docker = Start and view docker status
- sudo usermod -aG $USER = Adding your (logged in/current) user to docker group

## => Epoch time conversion in bash (one liner for loop):
- for in * ; do date -r $i ; done

## => Checking for ports in use and grepping for "(ESTABLISHED)":
- sudo lsof -i | grep "(ESTABLISHED)"
  
### Will be updated with more soon...
