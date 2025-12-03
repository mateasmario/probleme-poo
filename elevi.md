# Elevi

Creați un sistem de repartiție al elevilor într-un liceu. Un obiect de tip `Liceu` este caracterizat de numele acestuia și de un tablou cu obiecte de tip `Clasa`. O clasă este caracterizată de un număr maxim de elevi și un tablou de nume (șiruri de caractere).

Pentru repartiția elevilor vor exista doi algoritmi:
- Minim: un elev va fi repartizat în clasa cu cel mai mic număr de elevi din liceu (ținând cont de numărul maxim de elevi)
- Round-robin ("fiecare la rând"): primul elev va fi repartizat în prima clasă, al doilea în a doua clasă, ș.a.m.d. (ținând cont că nu se depășește numărul maxim de elevi - caz în care se va trece la prima clasă care nu este plină)

Cei doi algoritmi vor fi implementați în două clase diferite, ce implementează interfața `AlgoritmRepartitie`, caracterizată prin metoda `repartizeaza(String numeElev, Clasa[] clase)`.

Implementați următoarele metode din clasa Liceu:
1. Metoda `adaugaClasa(Clasa c)`, care adaugă clasa dată ca parametru în tabloul de clase.
2. Metoda `adaugaClasa(int numarMaximElevi)`, care creează o nouă clasă cu numărul de elevi dat ca parametru și o adaugă în tablou de clase.
3. Metoda `repartizeazaElev(String numeElev, AlgorithmRepartitie a`), care apelează metoda `repartizeaza` din al doilea parametru cu numele elevului și tabloul de clase din proprietatea liceului.

Implementați și o metodă `main` în care să testați funcționalitatea algoritmilor de repartiție.
