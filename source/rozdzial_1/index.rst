=====
Wstęp
=====

:Autor:
    Jan Balazs de Borbatviz

Wstęp do sprawozdania
=====================

Wstęp do sprawozdaniaZasadniczym celem zrealizowanych zajęć laboratoryjnych było przeprowadzenie kompleksowego procesu projektowania i wdrożenia relacyjnej bazy danych na przykładzie systemu obsługującego internetowy sklep ze sprzętem elektronicznym. Prace projektowe rozpoczęto od fazy analitycznej, w ramach której zidentyfikowano kluczowe procesy , przygotowano prototyp struktury w formacie JSON oraz opracowano modele koncepcyjne (przy użyciu notacji Chena) i logiczne (w notacji IE). Zwieńczeniem całego cyklu była implementacja fizyczna wypracowanych schematów w dwóch odrębnych środowiskach – PostgreSQL oraz SQLite. Proces ten obejmował również zautomatyzowane zasilenie tabel danymi testowymi oraz skonstruowanie zestawu zaawansowanych zapytań analitycznych.

Wnioski z przeprowadzonych ćwiczeń
==================================

Przejście przez wszystkie etapy projektowania i wdrażania relacyjnej bazy danych pozwoliło na sformułowanie następujących wniosków:
* **Rola rzetelnej analizy projektowej:** Skrupulatne przygotowanie dokumentacji oraz przeprowadzenie normalizacji (do poziomu 3NF) stanowi absolutny fundament udanego wdrożenia. Poprawny model logiczny minimalizuje ryzyko błędów i znacznie przyspiesza proces mapowania na model fizyczny.
* **Przewaga systemów rygorystycznych w środowisku profesjonalnym:** Równoległa implementacja uwypukliła istotne różnice między silnikami. PostgreSQL, dzięki ścisłemu typowaniu (np. zastosowanie typów NUMERIC czy SERIAL) oraz natywnemu egzekwowaniu więzów integralności , gwarantuje znacznie wyższe bezpieczeństwo i przewidywalność danych niż elastyczny, ale uproszczony system typów oferowany przez plikową bazę SQLite.
* **Zdolności analityczne silników:** Ostatni etap prac, polegający na tworzeniu skomplikowanych kwerend (obejmujących wielokrotne złączenia tabel, podzapytania i operatory zbiorowe), potwierdził zróżnicowane przeznaczenie badanych technologii. O ile SQLite pozostaje wygodnym i szybkim narzędziem do prostych, lokalnych zastosowań, to PostgreSQL oferuje stabilność, precyzję i wydajność niezbędną do profesjonalnego przetwarzania złożonych struktur informacyjnych.  

1. Główne repozytorium sprawozdania 
---------------------------------------------------------
Link do mojego repozytorium ze sprawozdaniem:

* **Link:** https://github.com/JanBalazs/Sprawozdanie-glowne

2. Repozytorium z modelami fizycznymi bazy danych
---------------------------------------------------------

* **Link:** https://github.com/Koko9077/Model-fizyczny-baz

3. Repozytoria reszty grupy 
--------------------------------------------------
Poniżej znajdują się odnośniki do repozytoriów reszty grupy:

* **Grupa 1 (rozdzial_1):** https://github.com/karaskamil/Sprzet-dla-bazy-danych.git
* **Grupa 2 (rozdzial_2):** https://github.com/Youarecheck/Bazy_Danych_Tematyczne_Repo_MK.git
* **Grupa 3 (rozdzial_3):** https://github.com/pawlos1337/Bazy-danych-temat.git
* **Grupa 4 (rozdzial_4):** https://github.com/OskarProgrammer/monitorowanie_i_diagnostyka.git
* **Grupa 5 (rozdzial_5):** https://github.com/KMachoK/Tematyczne.git
* **Grupa 6 (rozdzial_6):** https://github.com/domino0472/Partycjonowani-Danych
* **Grupa 7 (rozdzial_7):** https://github.com/oski486/BazyDanych-Subject.git
* **Grupa 8 (rozdzial_8):** https://github.com/Koko9077/Kopie-zapasowe-i-odzyskiwanie-danych.git
