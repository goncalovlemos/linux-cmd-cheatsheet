# Linux Commands Cheatsheet

| Command | Options | Parameters | Description |
| :-----: | :---: | :--------: | :---------: |
| **cat** | --- | /proc/cpuinfo | Show CPU information |
| **clear** </br> **CTRL+L** | --- | --- | Clears the terminal
| **command time** | -v | Program executable | Run programs and summarize system resource usage |
| **df** | -h | --- | Report file system disk space usage |
| **dmesg** | -wH | --- | Show bootup messages in real time |
| **dmidecode** | --- | --- | Shows hardware information from the BIOS |
| **du** | -sh | "example_dir/" </br> "example.file" | Estimate file space usage |
| **exit** | --- | --- | terminate the calling process </br> cause normal process termination |
| **find** | --- | . -name "example.file" </br> . -name "*.file" | Search for specific "example.file" file </br> Search recursively for all files ending with ".file" |
| **finger** | --- | "username" | Gives information on all logged in user |
| **free** | -h | --- | Display free and used memory |
| **grep** | -rnw . -e | "pattern to find" | Search for pattern recursively in directory |
| **hdparm** | -i | /dev/disk | Get SATA/IDE device parameters |
| **history** | --- | --- | Gives a list of all past commands typed in the current terminal session |
| **ifconfig** | --- | --- | Configure a network interface |
| **ip** | ad | --- | Linux IPv4 protocol implementation </br> show / manipulate routing, network devices, interfaces and tunnels |
| **htop** | --- | --- | Interactive process viewer |
| **lshw** | --- | --- | List hardware configuration information |
| **lsblk** | --- | --- | See information about block devices |
| **lspci** | -tv | --- | Show PCI devices |
| **lsusb** | -tv | --- | Show USB devices |
| **memusage** | -T | Program executable | Profile memory usage of a program |
| **mtr** | --- | "adress" | Network diagnostic tool |
| **netstat** | -tulpn | --- | Print network connections, routing tables, interface statistics, masquerade... |
| **nmap** | -sT -O | "address e.g. 192.168.1.0/24" | Show addresses in LAN |
| **notify-send** | --uregency= | low </br> normal </br> critical | A program to send desktop notifications |
| **ping** | --- | "adress" | Send ICMP ECHO_REQUEST to network hosts |
| **printenv** | --- | --- | Print all or part of environment |
| **python3** | -m | http.server | Create a quick http server |
| **reset** | --- | --- | terminal initialization |
| **sync** | --- | --- | Synchronize cached writes to persistent storage </br> Commit filesystem caches to disk |
| **tail** | -f | /var/log/syslog | See system log in realtime |
| **top** | --- | --- | Display Linux processes |
| **uname** | --- |--- | Print certain system information |
| **whatis** | --- | (command you want to know about) | Display one-line manual page descriptions |
| **w** | --- | --- | Show who is logged on and what they are doing |
| **who** | --- | --- | See who is logged on |
| **whoami** | --- | --- | Print effective userID |

