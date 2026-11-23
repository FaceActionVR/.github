# FaceActionVR

**Projekt badawczo-programistyczny | Wirtualna rzeczywistość (VR)**

FaceActionVR to projekt narzędzia badawczego rozwijany w ramach pracy magisterskiej. System składa się z aplikacji klient–serwer oraz komponentu VR zintegrowanego z istniejącą aplikacją.

Kod źródłowy projektu został podzielony na dwa repozytoria, odpowiadające za poszczególne części systemu.

---

## Struktura projektu

| Komponent | Opis |
|---|---|
| **Klient i serwer** | Aplikacja kliencka oraz serwerowa część systemu, utrzymywane we wspólnym repozytorium. |
| **Aplikacja VR** | Zmodyfikowana aplikacja zewnętrzna, zawierająca integrację modułu VR opracowaną na potrzeby FaceActionVR. |

[Przegląd repozytoriów organizacji](https://github.com/orgs/FaceActionVR/repositories)

## Architektura i rozwój

W obecnej wersji moduł VR jest bezpośrednio zintegrowany z kodem źródłowym aplikacji bazowej. Pozostałe komponenty systemu rozwijane są niezależnie.

Planowanym kierunkiem rozwoju jest wydzielenie modułu VR do osobnej biblioteki, umożliwiającej jego ponowne wykorzystanie bez konieczności bezpośredniej modyfikacji kodu aplikacji bazowej. Rozwiązanie to nie zostało jeszcze zaimplementowane.

## Projekt źródłowy i autorstwo

Część VR projektu FaceActionVR powstała na podstawie forka projektu **[EmotiScape – projekt magisterski](https://github.com/Karolinka4/EmotiScape-projekt_magisterski)**.

**Autorka projektu źródłowego:** mgr. Karolina Sumowska ([@Karolinka4](https://github.com/Karolinka4))  
**Uczelnia:** Uniwersytet Mikołaja Kopernika w Toruniu  
**Rok:** 2026  *Projekt EmotiScape zrealizowany w ramach pracy magisterskiej.*

Oryginalna implementacja aplikacji VR pozostaje dziełem jej autorki. FaceActionVR wykorzystuje tę implementację jako podstawę oraz zawiera własne modyfikacje służące integracji z pozostałymi komponentami systemu.

Karolina Sumowska jest również współautorką obu prac wymienionych poniżej.

## Publikacje naukowe

1. **W. Duklas, K. Sumowska, V. Osińska** (2026). *Object tracking to analyze facial expressions in Virtual Reality: designing application to estimate user emotions*. **2026 Progress in Applied Electrical Engineering (PAEE)**, IEEE. [IEEE Xplore](https://ieeexplore.ieee.org/document/11660689) · [DOI: 10.1109/PAEE71887.2026.11660689](https://doi.org/10.1109/PAEE71887.2026.11660689).

2. **K. Sumowska, W. Duklas, V. Osińska** (2026). *Analiza mimiki twarzy w VR: projektowanie aplikacji z wykorzystaniem eye-, face- i object tracking*. **Manuskrypt zgłoszony do publikacji**.

**Wojciech Duklas**  
Rok: 2026
Uniwersytet Mikołaja Kopernika w Toruniu  
*Projekt zrealizowany w ramach pracy magisterskiej*
