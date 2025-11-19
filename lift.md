# Lift

Creați clasa `Lift`, caracterizată de un număr maxim de persoane.

Un lift va avea următoarele metode:
1. Metoda `adaugaPersoana(int etaj)`, care adaugă etajul dorit de persoană într-un tablou (de tip [stivă](https://www.geeksforgeeks.org/dsa/stack-data-structure/)). Se vor adăuga și duplicatele în tablou. În cazul în care liftul este deja plin (de persoane), metoda va returna `false` și adăugarea nu se va efectua. Altfel, metoda returnează `true`.
2. Metoda `porneste()`, care duce liftul la următorul etaj din stivă. Pot fi eliminate toate intrările de etaj cu numărul respectiv din stivă. Spre exemplu, într-un lift există următoarele etaje, în ordinea în care au fost cerute: `1, 2, 1, 1, 3, 4`. În momentul apelării metodei `porneste()`, liftul va ajunge la etajul 1, și va elimina toate intrările de `1` din stivă, presupunând că fiecare persoană ce a vrut să ajungă la etajul respectiv coboară atunci.

Implementați o metodă `main`, într-o clasă separată, unde veți testa funcționalitatea metodelor de mai sus.
