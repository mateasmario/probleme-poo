# Operație

Se vor implementa clase ce reprezintă operații matematice. Acestea sunt: `Unar`, `Adunare`, `Scadere`, `Inmultire`, `Impartire` și `Putere`. Toate aceste clase vor implementa intefața `Operatie`, ce definește o metodă `efectueazaOperatie()`, care returnează un număr real.

Clasa `Unar` va avea un singur câmp de tip `double`. Celelalte clase vor avea în starea lor un tablou de operații.

## Cerința 1

Implementați metoda `efectueazaOperatie()` după următoarele reguli:
1. În clasa `Unar`, metoda va returna numărul din starea acestuia.
2. În clasele `Adunare`, `Scadere`, `Inmultire`, `Impartire` și `Putere`, se va returna rezultatul sumei (`+`), respectiv al diferenței (`-`), înmulțirii (`*`), împărțirii (`/`) și ridicării la putere (`^`) dintre toate elementele tabloului de operații conținute în acel obiect.

### Exemplu

Fie un obiect de tip `Adunare` ce conține trei operații în tablou, unde argumentele din paranteză reprezintă stările obiectelor: 
1. `Unar(3)`
2. `Unar(4)`
3. `Inmultire(Unar(5), Unar(6))`

Metoda `efectueazaOperatie` va itera prin toate elementele tabloului și va apela `efectueazaOperatie` pe fiecare element din tablou. Astfel, primul obiect va returna `3` (fiind de tip `Unar`), al doilea va returna `4`, iar al treilea va itera recursiv peste propriile sale elemente, returnând, într-un final, rezultatul înmulțirii dintre operațiile unare `5` și `6`. Rezultatul final va fi `30`.

## Cerința 2

Implementați o metodă ce returnează o operație sub formă de șir de caractere. Metoda va afișa termenii operației, împreună cu simbolul operației între acei termeni. Metoda va merge recursiv prin fiecare operație, iar în cazul în care o operație este conținută în alta, se vor deschide (respectiv închide) paranteze.

### Exemplu

Pentru obiectul de tip `Adunare` definit în exemplul din Cerința 1, se va returna următorul șir de caractere: `3+4+(5*6)`.

### Cerința 3

Implementați o metodă `main` în care să testați funcționalitatea metodelor implementate.
