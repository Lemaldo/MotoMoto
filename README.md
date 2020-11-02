# **MotoMoto**

## Twórcy: 
 **Mateusz Lemański 136276**
 **Mateusz Kempa 139952**

### Opis funkcjonalności projektu



MotoMoto jest to serwis z ofertami sprzedaży aut lub motocykli. Do stworzenia aplikacji użyje [**PostgreSQL + Python3**](https://www.postgresql.org/)(zarządzanie relacyjną bazą danych) oraz framework [**FastAPI**](https://fastapi.tiangolo.com/)(interfejs graficzny). Aplikacja będzie posiadać 2 tryby: **sprzedawca i kupiec**. Wspólnymi funkcjami dla tych trybów będzie czat i panel transakcyjny. Sprzedawca oraz kupiec będą mieli możliwość komunikacji się, ze sobą w celu dogadania szczegółów kupna/sprzedaży lub specyfikacji auta. W celu kupna auta, kupiec będzie mógł złożyć ofertę, jeśli transakcja dojdzie do skutku, dana oferta trafi do archiwum, a wszystkie inne oferty od innych użytkowników do tej samej oferty zostaną automatycznie odrzucone.

**Sprzedawca:**

- wystawia/usuwa/edytuje oferty sprzedaży
- akceptuje/odrzuca oferty kupna wysłane przez kupców(transakcja)
- komunikuje się poprzez wiadomości z kupcami



**Kupiec:**

- przegląda/wyszukuje oferty sprzedaży
- dodaje/usuwa oferty sprzedaży do ulubionych/obserwowanych
- proponuje oferty kupna sprzedającemu(transakcja)
- komunikuje się poprzez wiadomości ze sprzedawcą

------

**Widoki:**

1. Czat - lista konwersacji -> widok wiadomości w konwersacji
2. Transakcje - lista transakcji. Po stronie kupca informacja o transakcji(zaakceptowana/odrzucona/on hold)
3. Lista z ofertami + wyszukiwarka + filter ulubione(Tylko po stronie kupca) 
4. Dodaj/usuń/edytuj(Tylko po stronie sprzedawcy)

**Encje:**

SOON
