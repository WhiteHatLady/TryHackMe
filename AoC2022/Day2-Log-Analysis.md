# Rooms
1. Aoc2022: https://tryhackme.com/room/adventofcyber4
2. Windows Event Logs: https://tryhackme.com/room/windowseventlogs
3. Endpoint Security Monitoring Module: https://tryhackme.com/module/endpoint-security-monitoring

# Gdzie przechowywane są logi? 


# Komendy: 

## Linux 

```
ls -lah    # list catalogs and files
pwd  # current working directory
grep    # searching for a given text in file 
```
### GREP

```
grep -i "helloworld" log.txt   # case insensitives search
grep -E "thm|tryhackme" log.txt   # Searches using regex (regular expressions). For example, we can search for lines that contain either "thm" or "tryhackme"
grep -r "helloworld" mydirectory 	# Search recursively. For example, search all of the files in a directory for this value.
```

# Practise: 

## Dane do SSH: 

```
    IP address: 10.10.206.213
    Username: elfmcblue
    Password: tryhackme!
```
2.1. I connect with ssh: 

```
ssh elfmcblue@10.10.206.213
```
And I enter the password. 

![obraz](https://user-images.githubusercontent.com/90008283/205988434-f416d3fe-b5df-4d89-aa19-6d7544697c13.png)


2.2. + 2.3 Wyświeltenie plików w folderze gdzie się obecnie znajdujemy. 

```
elfmcblue@day-2-log-analysis:~$ pwd
/home/elfmcblue
elfmcblue@day-2-log-analysis:~$ ls
SSHD.log  webserver.log
```
2.4 + 2.5 + 2.6 Sprawdzenie ile linijek ma ten plik i czy warto mi go otwierać w jakimkolwiek edytorze

```
elfmcblue@day-2-log-analysis:~$ grep -i -E " 200 " webserver.log    # wyświetlenie lisyu który na pewno został pobrany - kod 200 

```
![obraz](https://user-images.githubusercontent.com/90008283/205992483-71270796-16dc-4e9f-b090-03fc7a72f861.png)

2.7 Znajduję flagę w katalogu w którym obecnie się znajduję
```
elfmcblue@day-2-log-analysis:~$ grep -i -r "thm{" .
```

![obraz](https://user-images.githubusercontent.com/90008283/205993016-b18a11a0-3db4-4b87-8150-aa2b62937e7a.png)







