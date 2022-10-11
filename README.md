# Linux commands cheatsheet

| Command | Options | Parameters | Description |
| :-----: | :---: | :--------: | :---------: |
| **whatis** | --- | (command you want to know about) | Display one-line manual page descriptions |
| **history** | --- | --- | Gives a list of all past commands typed in the current terminal session |
| **clear** </br> **CTRL+L** | --- | --- | Clears the terminal
| **finger** | --- | "username" | Gives information on all logged in user |
| **dmesg** | -wH | --- | Show bootup messages in real time |
| **cat** | --- | /proc/cpuinfo | Show CPU information |
| **free** | -h | --- | Display free and used memory |
| **lshw** | --- | --- | List hardware configuration information |
| **lsblk** | --- | --- | See information about block devices |
| **lspci** | -tv | --- | Show PCI devices |
| **lsusb** | -tv | --- | Show USB devices |
| **dmidecode** | --- | --- | Shows hardware information from de BIOS |
| **hdparm** | -i | /dev/disk | Get SATA/IDE device parameters |
| **uname** | --- |--- | Print certain system information |
| **df** | -h | --- | Report file system disk space usage |
| **du** | -sh | "example_dir/" </br> "example.file" | Estimate file space usage |
| **netstat** | -tulpn | --- | Print network connections, routing tables, interface statistics, masquerade... |
| **mtr** | --- | "adress" | Network diagnostic tool |
| **ping** | --- | "adress" | Send ICMP ECHO_REQUEST to network hosts |
| **top** | --- | --- | Display Linux processes |
| **htop** | --- | --- | Interactive process viewer |
| **sync** | --- | --- | Synchronize cached writes to persistent storage </br> Commit filesystem caches to disk |
| **w** | --- | --- | Show who is logged on and what they are doing |
| **who** | --- | --- | See who is logged on |
| **printenv** | --- | --- | Print all or part of environment |
| **tail** | -f | /var/log/syslog | See system log in realtime |
| **find** | --- | . -name "example.file" </br> . -name "*.file" | Search for specific "example.file" file </br> Search recursively for all files ending with ".file" |
| **ifconfig** | --- | --- | Configure a network interface |
| **ip** | ad | --- | Linux IPv4 protocol implementation </br> show / manipulate routing, network devices, interfaces and tunnels |
| **exit** | --- | --- | terminate the calling process </br> cause normal process termination |
| **reset** | --- | --- | terminal initialization |
| **whoami** | --- | --- | Print effective userID |
| **python3** | -m | http.server | Create a quick http server |
