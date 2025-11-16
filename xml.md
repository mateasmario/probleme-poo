# XML

Se consideră clasa `Eticheta`, ce descrie o etichetă ("tag") a unui document XML. Printe proprietățile acestei clase se numără și: numele etichetei, un tablou de atribute ale etichetei și un tablou de etichete "copii", conținute în interiorul obiectului părinte. Pentru clarificare, un exemplu de document XML se poate găsi mai jos:

```xml
<parinte>
  <copil-1>
  </copil-1>
  <copil-2>
    <copil-3>
    </copil-3>
  </copil-2>
</parinte>
```

Aici se poate vedea eticheta `parinte`, ce incorporează alte două etichete copil. Cel de-al doilea copil are și el o etichetă interioară. De asemenea, se poate observa că fiecare etichetă deschisă se și închide. Pentru simplitate, cerința presupune că etichetele se închid numai ca în exemplul de mai sus.

Clasa `Atribut` descrie anumite caracteristici ale unei etichete XML. Fiecare atribut se va da în format cheie-valoare ("key-value"). Acestea sunt și proprietățile clasei, definite sub formă de șiruri de caractere.

Etichetele cu atribute arată așa:

```xml
<parinte atribut1="valoare1" atribut2="valoare2">
</parinte>
```

Implementați următoarele metode în clasa `Eticheta`:
1. `adaugăCopil(Eticheta e)`, care adaugă eticheta dată ca parametru în tabloul de etichete al obiectului pe care este apelat
2. `adaugaAtribut(Atribut a)`, care adaugă atributul dat ca parametru în tabloul de atribute al obiectului pe care este apelat
3. `toString()`, care afișează eticheta, cu tot cu atributele și copiii ei, în structura corectă XML, exemplificată mai sus.

Creați o metodă `main` într-o clasă separată, unde veți crea structura definită mai jos și veți verifica dacă reprezentarea sub formă de șir de caractere este corectă.

```xml
<studenti>
  <student nume+"Alexandru Alexandrescu" facultate="AC" anul_inmatricularii="2020">
    <nota materie="Programarea Orientata pe Obiecte" valoare="5"></nota>
    <nota materie="Programarea Orientata pe Obiecte" valoare="7"></nota>
    <nota materie="Matematici Speciale" valoare="6.5"></nota>
  </student>
  <student nume+"Radu Radulescu" facultate="AC" anul_inmatricularii="2023">
    <nota materie="Sisteme Multimedia" valoare="9"></nota>
    <nota materie="Analiza Matematica" valoare="8.5"></nota>
  </student>
</studenti>
```
