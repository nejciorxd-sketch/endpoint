# endpoint

Jeden plik: `api-url.txt` — aktualny adres API serwera licencji StarMod.

Mod (`LicenseManager`) i launcher czytaja go co 5 minut. Zmiana hostingu = edycja
tej jednej linijki, bez przebudowy `.jar` i `.exe`.

Musi byc publiczne, bo czyta je klient bez zadnego tokena.
