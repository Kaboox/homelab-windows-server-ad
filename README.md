# homelab-windows-server-ad
Home lab project simulating basic IT infrastructure with Windows Server 2019, Active Directory, DHCP, DNS and NAT using VirtualBox.

# 🖥️ Home Lab – Windows Server & Active Directory (2024)

## 📌 Opis projektu
Ten projekt przedstawia moje samodzielnie stworzone środowisko testowe w VirtualBox, które odwzorowuje podstawową infrastrukturę IT wykorzystywaną w firmach. Zawiera konfigurację Active Directory, DHCP, DNS oraz usługę NAT za pomocą Remote Access Service (RAS).

## 🔧 Technologie i narzędzia
- VirtualBox (hipernadzorca)
- Windows Server 2019 (kontroler domeny)
- Windows 10 (klient dołączony do domeny)
- AD DS, DNS, DHCP, RAS/NAT

## ✅ Zakres działań
- Konfiguracja kontrolera domeny (Active Directory Domain Services)
- Tworzenie użytkowników, jednostek organizacyjnych (OU) i polityk GPO
- Konfiguracja DHCP i DNS na serwerze
- Dołączenie Windows 10 do domeny i testowanie logowania
- Wdrożenie RAS z NAT – przekazywanie połączenia internetowego z serwera na maszyny klienckie
- Testy połączenia z siecią z poziomu klienta

## 📷 Screeny
Zrzuty ekranu dostępne w folderze [`/screenshots`](./screenshots)

## 🎓 Czego się nauczyłem
- Konfiguracja środowiska sieciowego w systemie Windows Server
- Zarządzanie użytkownikami, domeną i usługami sieciowymi
- Symulacja komunikacji sieciowej w zamkniętym labie lokalnym
