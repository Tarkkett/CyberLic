# Linux core — Lesson 0
## Getting started:

- Download [CyberChef](https://gchq.github.io/CyberChef/CyberChef_v10.19.4.zip)
- Download [Wire Shark](https://2.na.dl.wireshark.org/win64/Wireshark-4.6.0-x64.exe)
- Download FoxyProxy browser extension
- Download [Team Repo](https://github.com/Tarkkett/CyberLic/tree/main)
- Download [Burp Suite](https://portswigger.net/burp/releases/professional-community-2025-8-8)
- Download [Burp Suite](https://portswigger.net/burp/releases/professional-community-2025-8-8)
- Download [WinSCP](https://winscp.net/download/files/202510161434a25db9abd484be9106bec968804622e6/WinSCP-6.5.4-Setup.exe)
- Download [VirtualBox](https://download.virtualbox.org/virtualbox/7.2.2/VirtualBox-7.2.2-170484-Win.exe)
- Download [Kali linux image](https://cdimage.kali.org/kali-2025.3/kali-linux-2025.3-installer-amd64.iso)
- Download [rockyou.txt](https://weakpass.com/download/90/rockyou.txt.gz)
- Download [VS Code](https://code.visualstudio.com/Download) if not already installed.
- Download [OpenStego](https://github.com/syvaidya/openstego/releases/download/openstego-0.8.6/Setup-OpenStego-0.8.6.exe)

## Web tools:
- CyberChef https://gchq.github.io/CyberChef/
- Aperi'Solve https://www.aperisolve.com/
- StegOnline https://georgeom.net/StegOnline/upload
- Linux Cheat Sheet https://www.geeksforgeeks.org/linux-unix/linux-commands-cheat-sheet/


---

## Filesystem & paths
- `/home/<user>` — user files  
- `/root` — root home  
- `/etc` — configuration files  
- `/var/log` — logs (auth, syslog, apps)  
- `/tmp`, `/dev/shm` — writable temp areas (useful for uploads/escalation)  
- `/usr/bin`, `/usr/sbin`, `/bin`, `/sbin` — executables  
- `/proc` — process & kernel info (procfs)  
- `/sys` — kernel/device sysfs

![HRC](img/fJlVaulJb.png)

---

## Navigation & file ops
```bash
pwd # Print working directory
ls -la # List all files
cd /path/to/dir # Change directory
cp src dest # Copy files
mv src dest # Move/rename files
rm file # Remove files
mkdir -p somedir # Make directory
stat file # Metadata
file somefile # Check file type
```

## Common commands
```bash
man # Manual
ssh user@192.168.0.1 # Secure shell
su - # Log in as root
sudo # Execute commands with root privileges
usermod -aG sudo alice # add user to sudo
chmod # Modify file access permissions
chown # Change file owner
ip a # Network statistics
ip a a 192.168.0.1 dev eth1 # Add ip adress
ip a d 192.168.0.1 dev eth1 # Remove ip adress
```

