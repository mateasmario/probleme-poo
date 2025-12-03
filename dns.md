# DNS

DNS este sistemul care traduce numele de domeniu în adresele IP aferente lor. Spre exemplu, adresa `google.com` va fi tradusă în `142.250.184.238`. Acest sistem este motivul pentru care nu suntem nevoiți să memorăm adrese IP ale diferitelor site-uri.

Clasa `ServerDNS` ține în starea ei un tablou de cereri și un dicționar (vezi [HashMap](https://www.w3schools.com/java/java_hashmap.asp)) cu domenii ca și cheie, și adresele IP ale acestora ca valori. Atât domeniile, cât și adresele IP, sunt reprezentate prin șiruri de caractere.

Un obiect de tip `Cerere` este reprezentat de host (șir de caractere) și de status (boolean).

Implementați următoarele metode din clasa `ServerDNS`:
1. Metoda `creeazaCerere(Cerere c)`, care simulează o navigare a unui utilizator pe o adresă web. Apelul metodei va adăuga în tabloul de cereri obiectul dat ca parametru.
2. Metoda `rezolva()`, care trece prin fiecare cerere din tablou și verifică dacă domeniul din câmpul `host` se află printre cheile din dicționarul serverului. În cazul în care domeniul există, se va seta status-ul cererii respective pe `true`, iar câmpul `host` va fi înlocuit cu IP-ul aferent domeniului din dicționar.
3. Metoda `rezolva(int maxim)`, care funcționează la fel cu metoda supraîncărcată, dar se oprește la numărul `maxim` de domenii rezolvate.

Implementați și o metodă `main`, în care să testați funcționalitatea claselor și metodelor implementate.
