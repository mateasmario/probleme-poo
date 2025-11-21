# Vot

Fie clasa `ManagerVoturi`, care numără și procesează voturile oamenilor din cadrul Alegerilor Prezidențiale. Clasa `Vot` este caracterizată de numele votantului și opțiunea aleasă (reprezentată de un int). Clasa `ManagerVoturi` este caracterizată atât de numărul candidaților, cât și de voturile cumulate (un tablou de obiecte `Vot` cu maximum 1024 de elemente).

Implementați următoarele metode în clasa `ManagerVoturi`:
1. Metoda `adaugaVot(Vot v)`, care adaugă un vot nou în tabloul din proprietatea clasei. Dacă se depășește numărul maxim de voturi, metoda returneaza `false`. Altfel, se face adăugarea și se returnează `true`.
2. Metoda `obtineCastigator()`, care returnează index-ul persoanei cu cele mai multe voturi.

Implementați și o metodă `main` în care să testați funcționalitatea metodelor definite mai sus.
