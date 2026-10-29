# zajecia cms zdjecia strony

Dokumentacja wizualna oraz zrzuty ekranu (full-page) lokalnego serwisu WordPress uruchomionego w środowisku Docker (MariaDB + WordPress) na systemie macOS.

---

## 📸 Galeria Zrzutów Ekranu

### 1. Strona Główna (Lista wpisów / Lekcje IT)
*Przegląd wpisów blogowych z wdrożoną paletą barw Malty i nową typografią.*
![Strona Główna](screenshots/01-strona-glowna.png)

---

### 2. Wpis: Czym jest WordPress?
*Artykuł omawiający architekturę CMS, silnik Core, motywy, wtyczki oraz REST API.*
![Czym jest WordPress](screenshots/02-wpis-czym-jest-wordpress.png)

---

### 3. Wpis: Czym jest Docker i konteneryzacja?
*Podstawy wirtualizacji na poziomie kernela, definicje obrazu, kontenera oraz Docker Engine.*
![Czym jest Docker](screenshots/03-wpis-czym-jest-docker.png)

---

### 4. Wpis: Środowisko WordPress + MariaDB na macOS
*Praktyczna konfiguracja pliku docker-compose.yml i uruchomienie bazy MariaDB oraz WordPressa na macOS.*
![Środowisko WordPress macOS](screenshots/04-wpis-srodowisko-macos.png)

---

### 5. Podstrona: HOME (Malta)
*Widok podstrony wprowadzającej z mapą Malty.*
![HOME](screenshots/05-podstrona-home.png)

---

### 6. Podstrona: FOOD (Pastizzi)
*Kulinaria i tradycyjne maltańskie pastizzi w stylizowanym kontenerze.*
![FOOD](screenshots/06-podstrona-food.png)

---

### 7. Podstrona: DISCOVER (Gozo & Gnejna)
*Miejsca i atrakcje archipelagu maltańskiego.*
![DISCOVER](screenshots/07-podstrona-discover.png)

---

## 🛠️ Specyfikacja Środowiska Lokalnego

| Komponent | Wersja / Narzędzie | Rola |
| :--- | :--- | :--- |
| **Silnik wirtualizacji** | Docker Desktop (macOS) | Konteneryzacja stosu technologicznego |
| **Baza danych** | MariaDB | Przechowywanie danych WordPressa |
| **CMS** | WordPress 6.7+ | Serwer aplikacji i generator treści |
| **Motyw** | `strona` (child theme Twenty Twenty-Five) | Szablon blokowy FSE z dedykowaną paletą Malty |
| **Adres lokalny** | `http://localhost` | Port 80 (mapowany z kontenera) |

---
*Repozytorium utworzone automatycznie: zajecia cms zdjecia strony.*
