# Platforma do kursów Niepodzielni — makieta

Klikalna makieta demonstracyjna platformy szkoleniowej Fundacji Niepodzielni.

**https://fundacja-niepodzielni.github.io/psychon-makieta/**

Repozytorium zawiera wyłącznie zbudowany plik (`index.html`) — kod źródłowy jest po stronie
wykonawcy. Cała aplikacja siedzi w jednym pliku i działa bez serwera, bez internetu
i bez logowania do czegokolwiek.

## Czym to jest

Prototyp do decyzji „budujemy własną platformę czy kupujemy gotową". **Nie jest to aplikacja
produkcyjna**: nie ma backendu, bazy, płatności, e-maili ani wideo. Stan zapisuje się wyłącznie
w przeglądarce osoby oglądającej (`localStorage`), a wszystkie dane i osoby są przykładowe.

Po wejściu wybiera się jedną z dwóch wersji:

- **MVP** — zakres uzgodniony na pierwszą edycję,
- **wersja docelowa** — pełna wizja platformy.

Wersję przełącza się w każdej chwili paskiem demo w prawym dolnym rogu.

## Konta demonstracyjne

Wypisane pod formularzem logowania — kliknięcie wypełnia pola.

| Konto | Hasło | Rola |
|---|---|---|
| `marta@demo.pl` | `demo1234` | wolontariuszka w trakcie programu |
| `ola@demo.pl` | `demo1234` | po programie — certyfikat i profil psychologa |
| `filip@demo.pl` | `demo1234` | student — węższy panel |
| `joanna@demo.pl` | `demo1234` | psycholożka prowadząca |
| `opiekun@demo.pl` | `admin1234` | opiekun projektu — bez modułu finansowego |
| `admin@demo.pl` | `admin1234` | super admin — całość |

## Uwagi

Strona ma `noindex`, więc nie trafia do wyszukiwarek — ale każdy, kto zna adres, ją otworzy.
Nie umieszczaj tu prawdziwych danych osobowych.

Aktualizacja: podmiana `index.html` w tym repozytorium.
