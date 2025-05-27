# homelab-windows-server-ad-router-firewall
Home lab project simulating basic IT infrastructure with Windows Server 2019, Active Directory, DHCP, DNS, NAT and virtual Router with Firewall using VirtualBox.

# 🖥️ Home Lab – Windows Server & Active Directory & Virtual Router with Firewall

## 📌 Opis projektu
Ten projekt przedstawia moje samodzielnie stworzone środowisko testowe w VirtualBox, które odwzorowuje podstawową infrastrukturę IT wykorzystywaną w firmach. Zawiera konfigurację Active Directory, DHCP, DNS oraz usługę NAT za pomocą Remote Access Service (RAS).

## 🔧 Technologie i narzędzia
- VirtualBox (hipernadzorca)
- Windows Server 2019 (kontroler domeny)
- Windows 10 (klient dołączony do domeny)
- AD DS, DNS, DHCP, RAS/NAT
- Wirtualny router pfsense z firewallem

## ✅ Zakres działań
- Konfiguracja kontrolera domeny (Active Directory Domain Services)
- Tworzenie użytkowników, jednostek organizacyjnych (OU)
- Konfiguracja DHCP i DNS na serwerze
- Dołączenie Windows 10 do domeny i testowanie logowania
- Wdrożenie RAS z NAT – przekazywanie połączenia internetowego z serwera na maszyny klienckie
- Testy połączenia z siecią z poziomu klienta
- Konfiguracja wirtualnego routera
- Konfiguracja oraz testowanie reguł firewall - blokowanie ruchu z klienta Windows 10 do sieci internet

## 👤 Automatyczne tworzenie 1000 użytkowników

Do masowego tworzenia użytkowników domenowych wykorzystałem skrypt PowerShell udostępniony przez Josha Madakora w jego tutorialu „Active Directory Home Lab”:
🔗 [Zobacz poradnik na YouTube](https://www.youtube.com/watch?v=djZ6btMS2u0)  
🔗 [Zobacz skrypt na GitHubie](https://github.com/joshmadakor1/AD_PS)

Skrypt automatycznie generuje 1000 użytkowników z losowymi nazwiskami i dodaje ich do Active Directory.


## 📷 Screeny
Zrzuty ekranu dostępne w folderze [`/screenshots`](./screenshots)

## 🎓 Czego się nauczyłem
- Konfiguracja środowiska sieciowego w systemie Windows Server
- Zarządzanie użytkownikami, domeną i usługami sieciowymi
- Symulacja komunikacji sieciowej w zamkniętym labie lokalnym
- Konfiguracja wirtualnego routera oraz firewalli
