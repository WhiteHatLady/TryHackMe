# Rooms
1. Aoc2022: https://tryhackme.com/room/adventofcyber4
2. Phising module: https://tryhackme.com/module/phishing
3. Endpoint Security Monitoring Module: https://tryhackme.com/module/endpoint-security-monitoring

# Jak Analizować emaile? 

|              Pole              	|                                                                                                                                                                            Szczegóły                                                                                                                                                                           	|   	|   	|   	|
|:------------------------------:	|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:	|---	|---	|---	|
| From                           	| adres nadawcy                                                                                                                                                                                                                                                                                                                                                  	|   	|   	|   	|
| To                             	| adres obiorcy, włączając w to CC (do wiadomości), BCC (kopia ukryta)                                                                                                                                                                                                                                                                                           	|   	|   	|   	|
| Date                           	| Data nadania                                                                                                                                                                                                                                                                                                                                                   	|   	|   	|   	|
| Subject                        	| Temat emaila                                                                                                                                                                                                                                                                                                                                                   	|   	|   	|   	|
| Return Path                    	| Adres zwrotny odpowiedzi, a.k.a. "Reply-To". Jeśli odpowiesz na wiadomość e-mail, odpowiedź trafi na adres podany w tym polu.                                                                                                                                                                                                                                  	|   	|   	|   	|
| Domain Key and DKIM Signatures 	| DKIM (DomainKeys Identified Mail) jest standardem bezpieczeństwa poczty elektronicznej zaprojektowanym, aby upewnić się, że wiadomości nie są zmieniane w tranzycie pomiędzy serwerem wysyłającym a odbiorcą. Podpisy email są dostarczane przez usługi email w celu identyfikacji i uwierzytelnienia emaili.                                                  	|   	|   	|   	|
| SPF                            	| Sender Policy Framework (SPF) to metoda uwierzytelniania wiadomości e-mail zaprojektowana w celu wykrywania fałszowania adresów nadawców podczas dostarczania wiadomości e-mail. Pokazuje serwer, który został użyty do wysłania wiadomości e-mail.Pomoże to zrozumieć, czy rzeczywisty serwer jest używany do wysyłania wiadomości e-mail z określonej domeny 	|   	|   	|   	|
| Message-ID                     	| Unikalny identyfikator wiadomości e-mail.                                                                                                                                                                                                                                                                                                                      	|   	|   	|   	|
| MIME-Version                   	| Używana wersja MIME.Pomoże to zrozumieć dostarczoną "nietekstową" zawartość i załączniki. Multipurpose Internet Mail Extensions (MIME) to standard internetowy, który rozszerza format wiadomości e-mail o obsługę tekstu w zestawach znaków innych niż ASCII, a także załączników audio, wideo, obrazów i programów użytkowych.                               	|   	|   	|   	|
| X-Headers                      	| Dostawcy poczty do odbiorników zazwyczaj dodają te pola. Dostarczone informacje są zazwyczaj eksperymentalne i mogą być różne w zależności od dostawcy poczty.Dostawcy poczty do odbiorników zazwyczaj dodają te pola. Dostarczone informacje są zazwyczaj eksperymentalne i mogą być różne w zależności od dostawcy poczty.                                   	|   	|   	|   	|
| X-Received                     	| Serwery pocztowe, przez które przeszła wiadomość                                                                                                                                                                                                                                                                                                               	|   	|   	|   	|
| X-Spam Status                  	| Spam score wiadomości e-mail                                                                                                                                                                                                                                                                                                                                   	|   	|   	|   	|
| X-Mailer                       	| Nazwa klienta poczty elektronicznej.                                                                                                                                                                                                                                                                                                                           	|   	|   	|   	|


# Tools: 
1. Sublime Text: https://www.sublimetext.com/3
2. emlAnylazer 
- online tool: https://eml-analyzer.herokuapp.com/ 
- instalacja na Ubuntu: https://pypi.org/project/eml-analyzer/
```
https://pypi.org/project/eml-analyzer/
```
3. Emailrep - online tool:  https://emailrep.io/   - email reputation  (OSINT)
4. Virustotal - onine tool: https://www.virustotal.com/gui/home/upload    -> A service that provides a cloud-based detection toolset and sandbox environment.
5. InQust - https://inquest.net/ -> A service provides network and file analysis by using threat analytics. -> 
6. IPinfo.io https://ipinfo.io/  -> A service that provides detailed information about an IP address by focusing on geolocation data and service provider.
7. Talos Reputation  -> An IP reputation check service is provided by Cisco Talos.

# Komendy: 

## emlAnalyzer 

```
emlAnalyzer -i /path-to-file/filename --header --html -u --text --extract-all
```

`-i` path-to-file 
`--header`  	Show header
`-u ` Show URLs
`--text`  Show cleartext data
`extract-all` Extract all attachments

## emllAnylazer: 
emlAnalyzer -i Urgent\:.eml --header --html -u --text --extract-all



