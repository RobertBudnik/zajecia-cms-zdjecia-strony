# zzcms – Content Management Studio

Projekt semestralny zrealizowany w ramach zajęć CMS. Jest to autorski system typu "cyfrowy ogród", łączący w jednym ekosystemie bazę wiedzy (notatki z zajęć), dokumentację projektową oraz w pełni funkcjonalny moduł e-commerce.

## 🛠 Technologie
*   **System:** WordPress
*   **E-commerce:** WooCommerce
*   **Motyw:** Autorski motyw (Vanilla JS, CSS3, wsparcie dla FSE / `theme.json`)
*   **Środowisko:** Docker & Docker Compose (localhost)

## 🚀 Uruchomienie (Localhost)

1. Sklonuj/pobierz repozytorium projektu.
2. W folderze z projektem uruchom środowisko w terminalu:
   ```bash
   docker-compose up -d
   ```
3. Projekt będzie dostępny w przeglądarce pod adresem: `http://localhost:8081`

---

## 📸 Przegląd interfejsu (Zrzuty ekranu)

Poniżej znajduje się udokumentowany postęp prac podzielony na główne sekcje aplikacji.

### 1. Architektura i Baza wiedzy (Strona główna)
Podsumowanie semestru i główne repozytorium plików.

![Strona główna - Cyfrowe Archiwum](localhost_8081-CMS–ContentManagementStudio.jpeg)
![Repozytorium](localhost_8081-CMS–ContentManagementStudio (5).jpeg)

### 2. Laboratoria (Notatki i wdrożenia)
Udokumentowane zajęcia z konfiguracji serwera, tworzenia motywów oraz wdrożenia sklepu.

![Laboratoria - widok modułów](localhost_8081-CMS–ContentManagementStudio (1).jpeg)
![Zajęcia 01 - Środowisko i instalacja](localhost_8081-CMS–ContentManagementStudio (2).jpeg)
![Zajęcia 02 - Motywy i style](localhost_8081-CMS–ContentManagementStudio (3).jpeg)
![Zajęcia 03 - WooCommerce i kolory](localhost_8081-CMS–ContentManagementStudio (4).jpeg)

### 3. Sklep (E-commerce)
Działający moduł sprzedażowy z własnym stylem i procesem zakupowym.

![Katalog Sklepu](localhost_8081-Shop–CMS.jpeg)
![Karta Produktu](localhost_8081-RocznalicencjaIDEAIAssistant–CMS.jpeg)
![Koszyk](localhost_8081-Cart–CMS.jpeg)
![Finalizacja Zamówienia (Checkout)](localhost_8081-Checkout–CMS.jpeg)