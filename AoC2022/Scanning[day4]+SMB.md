# Pokoje
1. pokój do NMAPA: https://tryhackme.com/module/nmap
2. Aoc2022: https://tryhackme.com/room/adventofcyber4

# Komendy:

## NMAP - skanowanie sieci

```nmap
nmap -sn <ip ofiary>   # Ping Scan
nmap -O <ip ofiary>    # Operating System Scan
nmap -sV <ip ofiary>   # Detecting Services
nmap -A <ip ofiary>    # All above
```

## SMB - dostęp do zasobów

1. Poprzez File Manager wpisując w pasek przeglądarki: `smb://adres-ip-ofiary/`
2. Poprzez CLI 

```smb
smbclient //<samba_name>/<share> -I <machine ip to connect to>     # domyślnie zainstalowany na Kalim
# lub
mount -t cifs //<samba_name>/<share> <mount point> -o ip=<machine ip to connect to>


```


<details><summary>Teoria</summary></details>


<details>
<summary>Praktyka</summary>

### 4.1. Wyszukiwanie nazwy serwera HTTP.  

  ```
  root@ip-10-10-59-153:~# nmap -A 10.10.165.142
  ```
  
![obraz](https://user-images.githubusercontent.com/90008283/205516553-c5eadb21-af8d-4a58-ae82-269ef43fc038.png)
  
### 4.2 Jaka usluga działa na porcie 22? 
  

  ```
root@ip-10-10-59-153:~# nmap -A 10.10.165.142  
  ```
  
![obraz](https://user-images.githubusercontent.com/90008283/205516756-2c411e74-e5bc-4209-9823-33d9150530ba.png)

  
### 4.3. + 4.4. Uzyskanie dostępu do usługi SMB oraz wyciągnięcie informacji z konkretnych plików.
  
  W pasku File Manager wpisujemy: 
  ```
  smb://10.10.165.142/
  ```
Na począatku szukałam flagi w katalogu `smb://10.10.165.142/sambashare/`. Ale tam jej nie było.
  ![obraz](https://user-images.githubusercontent.com/90008283/205517103-f694fb12-e072-473d-bd3e-39ec3b067c72.png)
  
 Następnie poszukałam flagi w katalogi `smb://10.10.165.142/admins`

  ![obraz](https://user-images.githubusercontent.com/90008283/205517204-4cbecfd9-4c18-48f6-b53d-236e46b7b3ef.png)

  
  Ostatecznie więc uzyskałam flagę. 
  

**  4.4 ** 
  ![obraz](https://user-images.githubusercontent.com/90008283/205517300-1410fb37-7e1e-40cc-a652-081fe692a995.png)

  
  
  
</details>






