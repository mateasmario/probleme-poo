# Vas

Creați o clasă `Vas`, definită prin capacitatea maximă (ml) și prin capacitatea actuală a acestuia. Capacitatea maximă a vasului va fi dată în momentul creării unui obiect nou.

Implementați următoarele metode:
1. Metoda `adauga(int ml)`, care adaugă cantitatea dată ca parametru în vas, și returnează cantitatea rămasă în afară, dacă în urma adăugării s-a depășit capapcitatea maximă. Exemplu: pentru un vas gol cu o capacitate maxima de `500 ml`, un apel pe metoda `adauga(600)` va returna `100`.
2. Metoda `adauga(Vas v)`, care adaugă cantitatea din vasul `v` în vasul pe care se apelează metoda, pe baza aceleiași logici de mai sus. La final, se elimină cantitatea adăugată în vasul nou din `v`.
3. O metodă ce returnează reprezentarea unui vas sub forma unui șir de caractere. Șirul de caractere va avea forma: `Vas: <capacitateActuala> ml / <capacitateMaxima> ml`.

Creați, într-o clasă separată, și o metodă `main`, în care să testați funcționalitatea metodelor implementate.
