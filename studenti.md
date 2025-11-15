# Studenti

Fie o clasă `Facultate` ce administrează studenții unei facultăți. Un student este caracterizat de un număr matricol (sub formă de șir de caractere), numele studentului, anul înmatriculării și media generală a acestuia. Clasa `Facultate` are in proprietatea ei și un tablou de studenți. Numărul maxim de studenți va fi specificat în constructorul clasei.

Implementați următoarele metode din clasa `Facultate`:
1. Metoda `adaugaStudent`, care cere ca parametru un student și îl adaugă în tablou, în cazul în care mai sunt locuri și dacă nu există deja studentul în tablou. Dacă adăugarea s-a facut, această metodă returnează `true`. Altfel, va returna `false`.
2. Metoda `stergeStudent`, care ia ca parametru numărul matricol al studentului și îl șterge din tablou. Metoda returnează `true` dacă studentul cu numărul respectiv a fost găsit. Altfel, va returna `false`.
3. Metoda `calculNumarStudentiTrecuti`, care returnează numărul de studenți care au medie de trecere.
4. Metoda `calculNumarStudentiPicati`, care returnează numărul de studenți picați, **fără să parcurgă** tabloul. Metoda trebuie să se folosească de `calculNumarStudentiTrecuti`.

Se va implementa și o metodă `main` într-o clasă separată, care va testa funcționalitatea metodelor definite mai sus.
