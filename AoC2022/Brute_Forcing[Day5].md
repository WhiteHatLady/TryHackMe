# Rooms
1. Aoc2022: https://tryhackme.com/room/adventofcyber4
2. Hydra: https://tryhackme.com/room/hydra

# Wordlist and Tools: 


| Resource                              |                    Source                    |
| ------------------------------------- |:--------------------------------------------:|
| rockyou.txt                           |      `/usr/share/wordlists/rockyou.txt`      |
| Seclists                              |  https://github.com/danielmiessler/SecLists  |
| FuzzDB                                |   https://github.com/fuzzdb-project/fuzzdb   |
| Bruteforce-database                   | https://github.com/duyet/bruteforce-database |
| Tool for privilage escalation to root |      https://github.com/d4t4s3c/suForce      |
| Hydra wordlist                        |  https://github.com/vanhauser-thc/thc-hydra  |



# Commands

## HYDRA - brute-force SSH

```nmap
hydra -l username -P wordlist-passwords.txt server-IP service
hydra -L wordlist-usernames -P wordlist-passwords.txt server-IP service
#równoważne przykłady
hydra -l mark -P /usr/share/wordlists/rockyou.txt 10.10.40.141 ssh
hydra -l mark -P /usr/share/wordlists/rockyou.txt ssh://10.10.40.141
```
`mark ` as the username as it iterates over the provided passwords against the SSH server.
**Others porotcoles** : rdp, vnc, ftp, pop3
**Flags**:
`-V` or `-vV` :  verbose
`-d` :  debug mode


## Connect to VNC

### Tool: Remmina

#### Installation Remmina: 
https://remmina.org/how-to-install-remmina/

```copy
sudo apt-add-repository ppa:remmina-ppa-team/remmina-next
sudo apt update
sudo apt install remmina remmina-plugin-rdp remmina-plugin-secret
```

For Ubuntu: 

![obraz](https://user-images.githubusercontent.com/90008283/205734772-e93b6a0d-08b2-45c7-94dd-fee53d74da16.png)

![obraz](https://user-images.githubusercontent.com/90008283/205734818-639ee0ca-d5d2-4536-8cf3-741df5f992e7.png)

![obraz](https://user-images.githubusercontent.com/90008283/205734847-30b0218d-07a1-4396-b300-f2b5d3226cf9.png)

![obraz](https://user-images.githubusercontent.com/90008283/205734897-d5b50c77-0026-4a6d-beec-419c0701be1d.png)



## Remote Access Services


| Protocole | PORT |         Stands By         | Interface |                        OS                        |
| --------- |:----:|:-------------------------:| --------- |:------------------------------------------------:|
| SSH       |  22  |       Secure Shell        | CLI       |            Linux, Putty for MSWindows            |
| RDP       | 3389 |  Remote Desktop Protocol  | GUI       |                    MS Windows                    |
| VNC       | 5900 | Virtual Network Computing | GUI       | Linux, MS Windows, MacOS, Android, Raspberry Pi. |


## HYDRA

Support for protools: ` SSH, VNC, FTP, POP3, IMAP, SMTP,`



<details>
<summary>Practice</summary>


  
  
</details>






