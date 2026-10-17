*Przeczytaj w innych językach: [English](README.md), [한국어](README.ko.md), [Polski](README.pl.md)*

# Kwang Beom Park

**Senior Finance Manager (Finance Head) | Architekt FinOps i Transformacji Cyfrowej**  
*Lokalizacja: Warszawa, Polska*

> **Połączenie ładu finansowego z inżynierią operacyjną**  
> *Senior Finance Manager (Finance Head) wdrażający spójność księgową, zgodność podatkową i automatyzację procesów w europejskiej spółce.*  
> `> "Budowanie pewności operacyjnej od pierwotnego dowodu księgowego po raporty dla zarządu."`

<p align="center">
  <img src="assets/finops_ecosystem_blueprint.svg" width="100%" alt="Enterprise FinOps & Commercial Operations Ecosystem Blueprint">
</p>

[Profil LinkedIn](https://www.linkedin.com/in/kwangbeompark) · [Wszystkie repozytoria GitHub](https://github.com/KwangBeomPark?tab=repositories) · [Kontakt e-mail](mailto:park.kwangbeomi@gmail.com)

---

## 🏛️ Podsumowanie menedżerskie i filozofia przywództwa (Executive Summary)

Jestem doświadczonym liderem finansowym z wszechstronną praktyką w obszarach **rachunkowości finansowej, kontrolingu biznesowego, zarządzania ryzykiem kredytowym oraz zgodności podatkowej (VAT 23% / JPK_V7 / MSSF/IFRS)** w międzynarodowych strukturach europejskich.

Równolegle z przywództwem finansowym stosuję podejście inżynieryjne oparte na zasadzie: **„Najpierw problem biznesowy, potem technologia” (Business problem first, technology second)**. Zamiast polegać na kosztownych zewnętrznych wdrożeniach IT czy sztywnych pakietach oprogramowania, które rzadko odpowiadają realiom operacyjnym, samodzielnie projektuję i wdrażam lekkie, bezpieczne potoki automatyzacji bezpośrednio wewnątrz działu finansowego.

### Główne zasady operacyjne:
- **Spójność danych na poziomie księgi głównej (Ledger Integrity)**: Eliminacja błędów obliczeniowych i anomalii transakcyjnych u źródła, zanim trafią do systemu finansowo-księgowego.
- **Praktyczna kontrola wewnętrzna (Internal Controls)**: Projektowanie automatycznych mechanizmów prewencyjnych (matryce akceptacji, weryfikacja wizualna pól), które zapobiegają błędom ludzkim bez tworzenia zbędnej biurokracji.
- **Optymalizacja TCO i zwinność**: Dostarczanie niezawodnych narzędzi niewymagających uprawnień administratora (Non-Admin), które w pełni spełniają korporacyjne wymogi bezpieczeństwa i RODO (GDPR) bez konieczności transferu poufnych danych do chmury.

---

## 💼 Macierz rozwiązań funkcjonalnych (PL Suite)

Pakiet **PL Suite (01–08)** oraz platformy analityczne tworzą zintegrowany ekosystem operacyjny, zaprojektowany w celu ochrony spójności danych i eliminacji wąskich gardeł w całym cyklu finansowym.

| Obszar zarządzania | Rozwiązanie | Rola i kluczowy wpływ operacyjny | Architektura techniczna |
| :--- | :--- | :--- | :--- |
| **I. Przyspieszenie zamknięcia i spójność ksiąg** | [**04_DataRefinery**](https://github.com/KwangBeomPark/04_DataRefinery) | **Silnik OLAP DuckDB i ochrona formatu dziesiętnego**<br>Eliminuje błędy wynikające z europejskiego separatora dziesiętnego (przecinek `,` vs kropka `.`) oraz normalizuje złożone dane promocyjne na potrzeby rozliczeń okresowych. | Python · PySide6 · DuckDB |
| | [**06_Stepwise**](https://github.com/KwangBeomPark/06_Stepwise) | **Bezpieczny silnik księgowań w ERP / SAP GUI**<br>Automatyzuje powtarzalne wprowadzanie dekretów i danych podstawowych z wizualną weryfikacją stanu ekranu przez OpenCV, zapobiegając pomyłkom i duplikatom. | Python · PySide6 · OpenCV |
| | [**02_SwiftDeck**](https://github.com/KwangBeomPark/02_SwiftDeck) | **Centrum operacyjne FinOps i zamknięcia miesiąca**<br>Standaryzuje ścieżki zamknięcia, foldery JPK_V7/VAT i zapytania SQL za pomocą lekkiego interfejsu skrótów klawiszowych dla zespołu. | AutoHotkey v2 · Przenośne INI |
| **II. Kontrola wewnętrzna i gotowość do audytu** | [**08_OutlookTemplate**](https://github.com/KwangBeomPark/08_OutlookTemplate) | **Nadzór nad matrycą akceptacji i DW**<br>Wymusza poziomy zatwierdzeń (Kierownik vs CFO) i automatycznie wypełnia treść HTML, zapobiegając pominięciu kluczowych odbiorców w korespondencji. | AutoHotkey v2 · COM / UI Automation |
| | [**05_FileOperation**](https://github.com/KwangBeomPark/05_FileOperation) | **Archiwizacja dowodów audytowych i synchronizacja**<br>Zachowuje pierwotne znaczniki czasu (timestamp) plików i automatyzuje dystrybucję dokumentów na potrzeby ścieżki audytu (Audit Trail). | Python · PySide6 · Office COM |
| | [**07_eml-viewer**](https://github.com/KwangBeomPark/07_eml-viewer) | **Bezpieczna przeglądarka dowodów e-mail (Sandbox)**<br>Otwiera pliki `.eml` i `.msg` niezależnie od pakietu Office, wiernie renderując treść HTML i blokując zewnętrzne piksele śledzące. | Python · PySide6 · Qt WebEngine |
| | [**01_ClipOCR-Pro**](https://github.com/KwangBeomPark/01_ClipOCR-Pro) | **Lokalny OCR i uzgadnianie dokumentów źródłowych**<br>Lokalne przechwytywanie ekranu i wielojęzyczny OCR (PL/EN/KO) bez chmury, wspierający uzgadnianie danych między systemem ERP a wyciągami i fakturami. | AutoHotkey v2 · Windows OCR |
| **III. Nadzór nad raportowaniem zarządczym** | [**03_vba_PPT_Addin**](https://github.com/KwangBeomPark/03_vba_PPT_Addin) | **Standardy raportowania zarządu i poufna dystrybucja**<br>Ujednolica formaty i jednostki prezentacji dla C-Suite oraz umożliwia selektywną wysyłkę poufnych slajdów drogą mailową. | Czysty VBA · Dodatek PowerPoint |
| **IV. Inteligencja rynkowa i marże** | [**09_Market_Retail_Intelligence**](https://github.com/KwangBeomPark/09_Market_Retail_Intelligence) | **Monitoring cen e-commerce i ochrona marży brutto**<br>Śledzi codzienne ceny detaliczne, porozumienia promocyjne i warunki handlowe na polskich platformach e-commerce w celu obrony marży. | Python · Potok danych |

---

## 🛠️ Kompetencje techniczne i ład inżynieryjny

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                          TECHNO-FINANCE TOOLKIT                             │
├──────────────────────────────┬──────────────────────────────────────────────┤
│ Domena finansowa             │ MSSF/IFRS · Podatki (VAT 23%, JPK_V7) · SOX │
│ i ład korporacyjny           │ Matryca akceptacji · Uzgadnianie bilansu     │
├──────────────────────────────┼──────────────────────────────────────────────┤
│ Analiza danych               │ DuckDB (In-Process OLAP) · SQL · Excel VBA   │
│ i potoki ETL                 │ Power Query · SQLite · Relacyjne łączenie    │
├──────────────────────────────┼──────────────────────────────────────────────┤
│ Automatyzacja i UI           │ Python 3.12+ · PySide6 (Qt) · AutoHotkey v2  │
│                              │ OpenCV Computer Vision · Windows UI Auto     │
├──────────────────────────────┼──────────────────────────────────────────────┤
│ Bezpieczeństwo i zgodność    │ Oficjalny podpis cyfrowy CA Authenticode     │
│                              │ Zgodność z RODO (Zero-Cloud) · Tryb Non-Admin│
└──────────────────────────────┴──────────────────────────────────────────────┘
```

- **Podpis cyfrowy kodu**: Wszystkie pakiety wykonywalne są cyfrowo podpisane certyfikatem Code Signing (Certum Open Source Developer CA), bezproblemowo przechodząc weryfikację **Windows 11 Smart App Control** oraz korporacyjnych systemów antywirusowych.
- **Bezpieczeństwo Offline-First**: Dane finansowe są przetwarzane wyłącznie w pamięci lokalnej stacji roboczej, gwarantując 100% zgodności z tajemnicą przedsiębiorstwa i europejskimi przepisami o ochronie danych (RODO/GDPR).

---

## 🌍 Doświadczenie regionalne i języki

- **Miejsce zamieszkania**: Warszawa, Polska (Głębokie zrozumienie lokalnych przepisów księgowych, podatkowych i kultury biznesowej)
- **Języki**:
  - **Koreański (Korean)**: Język ojczysty (Native)
  - **Angielski (English)**: Płynny / Profesjonalny biznesowy (Fluent / Business)
  - **Polski (Polish)**: Podstawowy (Basic)

---

## 📬 Kontakt

- **LinkedIn**: [linkedin.com/in/kwangbeompark](https://www.linkedin.com/in/kwangbeompark)
- **GitHub**: [@KwangBeomPark](https://github.com/KwangBeomPark)
- **E-mail**: [park.kwangbeomi@gmail.com](mailto:park.kwangbeomi@gmail.com)

---

<p align="center">
  <em>Finance Leadership × Commercial Business Control × Data &amp; Process Automation</em>
</p>
