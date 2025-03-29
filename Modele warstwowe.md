[Źródło - Pasja Informatyki](https://pasja-informatyki.pl/sieci-komputerowe/model-tcp-ip-iso-osi/)
[Źródło - GFG](https://www.geeksforgeeks.org/tcp-ip-model/)
[Źródłó - Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite#Link_layer)
# ISO/OSI
Podzielone na warstwy:
- **Aplikacji**  - warstwa w której działają aplikacje, np. www, ftp, email, ssh...
- **Prezentacji** - formaty plików, kodowanie danych 
- **Sesji** - zarządzanie sesjami
- **Transportu** - segmentacja danych na pakiety i dodanie informacji zawartych w nagłówku [[pakiet]]u.
- **Sieci** - adresowanie danych oraz wyznaczenie najlepszej trasy danych
- **Łącza Danych** - dostęp do medium transmisyjnego i adresowanie w sieci LAN
- **Fizyczna** - kodowanie do bitów i przesyłanie przez medium do urządzeń

# TCP/IP
- **Aplikacji** - warstwa w której działają programy, protokoły działające w tej warstwie to: SMTP, FTP, SSH, HTTP itd.
- **Transportu** - segmentacja danych na pakiety, i dodanie informacji zawartych w nagłówku pakietu.
- **Internetowa** - nazywana również warstwą routingu, zapewnia odnalezienie najkrótszej trasy do hosta docelowego
- **Dostępu do sieci** - kodowanie do bitów i przekazanie do medium transmisyjnego oraz adresowanie przez MAC