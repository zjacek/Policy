# Policy

Konwencja nazewnicza

####Resource groups

<krótka nazwa projektu>-<rodzaj środowiska>-rg-<numer porządkowy>

- "krótka nazwa projektu" - nazwa identyfikująca projekt, 4 znaki
- "rodzaj środowiska" - np. [PRD|TST|DEV], 3 znaki
- "numer porządkowy" - 2 cyfry

####Storage

<krótka nazwa projektu><rodzaj środowiska>-st-<unikalny ciąg znaków>

- "krótka nazwa projektu" - nazwa identyfikująca projekt, 4 znaki
- "rodzaj środowiska" - np. [PRD|TST|DEV], 3 znaki
- "unikalny ciąg znaków" - unikalny ciąg znaków generowany z funkcji "uniqueString(resourceGroup().id))", 13 znaków
- <całość maksymalnie 24 znaki>

####Virtual Network

<krótka nazwa projektu>-<rodzaj środowiska>-vnet-<numer porządkowy>

- "krótka nazwa projektu" - nazwa identyfikująca projekt, 4 znaki
- "rodzaj środowiska" - np. [PRD|TST|DEV], 3 znaki
"- numer porządkowy" - 2 cyfry

####Virtual Machine

<krótka nazwa projektu><rodzaj środowiska><rola serwera><numer porządkowy>

- "krótka nazwa projektu" - nazwa identyfikująca projekt, 4 znaki
- "rodzaj środowiska" - np. [PRD|TST|DEV], 3 znaki
- "rola serwera" - np. [app|web|dba], 3 znaki
- "numer porządkowy" - 2 cyfry
- <całość maksymalnie 15 znaków>

####Disk

<nazwa maszyny wirtualnej>-disk-<numer porządkowy>

- "nazwa maszyny wirtualnej" - nazwa maszyny wirtualnej do której będzie przynależał dysk
- "numer porządkowy" - 2 cyfry
