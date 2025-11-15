# Revistă

Fie clasa `Revista`, definită prin numele acesteia, editura la care a fost tipărită, și categoria revistei, toate cele trei reprezentate de șiruri de caratere. Un obiect de tip `Revista` ține în proprietățile lui și un tablou de abonamente. Lungimea maximă a tabloului este 32.

Clasa `Abonament` este definită de numele abonatului și numărul de zile pentru care e valid abonamentul..

În clasa `Revista` se vor implementa următoarele metode:
1. `adaugaAbonament`, care ia ca parametru un obiect de tip `Abonament` și adaugă obiectul respectiv în tabloul de abonamente, dacă nu există deja și dacă nu se depășește numărul maxim de abonamente. Două abonamente sunt considerate egale dacă au același nume de abonat.
2. `promotie`, care selectează un abonat aleatoriu din tablou și îi incrementează numărul de zile de abonament cu 90 (trei luni). Poziția elementului din tablou se poate genera aleatoriu folosind clasa `Random` din Java (vezi primul exemplu de [aici](https://www.geeksforgeeks.org/java/generating-random-numbers-in-java/)). Metoda returnează, mai apoi, numele abonatului ce a primit promoția.

Definiți și o metodă `main` într-o a treia clasă `Program`, unde veți testa funcționalitățile metodelor definite mai sus.
