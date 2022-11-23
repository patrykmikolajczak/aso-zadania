# 

## VirtualBox
Pobierz i zainstaluj VirtualBox
https://www.virtualbox.org/wiki/Downloads 

## Pobierz Ubuntu
Pobierz ubuntu server https://ubuntu.com/download/server  
Pobierz ubuntu https://ubuntu.com/download/desktop

## W VirtualBox
### Dodaj nowe maszyny
W każdej maszynie ustaw konto zsp i hasło zsp.
Nazwa maszyny jest podana w zadaniu, ta sama nazwa powinna być ustawiona podczas instalacji.
W każdej maszynie ustaw 2 karty sieciowe  
Karta 1 ustaw na NAT
![alt text for screen readers](/img2.png "Text to show on mouseover")  
Karta 2 ustaw na Sieć wewnętrzną i nazwij intnet-1
![alt text for screen readers](/img1.png "Text to show on mouseover")
1. Dodaj nową maszynę z systemem Ubuntu Server i nazwij ją DHCP1
2. Dodaj nową maszynę z systemem Ubuntu Server i nazwij ją DNS1
3. Dodaj nową maszynę z systemem Ubuntu i nazwij ją User1
4. Dodaj nową maszynę z systemem Ubuntu i nazwij ją User2
5. Dodaj nową maszynę z systemem Ubuntu i nazwij ją User3

### Zaloguj się na maszynę 
Na każdej utworzonej maszynie zaloguj się i ustaw kartę sieciową:  
DHCP1 - ip: 192.168.0.9 maska: 255.255.255.0  
DNS1 - ip: 192.168.0.10 maska: 255.255.255.0  
User1 - ip: 192.168.0.11 maska: 255.255.255.0  
User2 - ip: 192.168.0.12 maska: 255.255.255.0  
User3  - ip: 192.168.0.13 maska: 255.255.255.0  

### sprawdź połączenie
Uruchom wszystkie maszyny wirtualne.
Sprawdź połączenie między wszystkimi maszynami używając 'ping'  