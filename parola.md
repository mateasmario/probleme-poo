# Parolă

Clasa `VerificatorParola`, verifică dacă o parolă nouă verifică condițiile minime de securitate. Constructorul clasei va primi ca parametru un tablou de condiții.

Fiecare condiție este reprezentată de o clasă ce implementează o interfață (sau o clasă abstractă) `Conditie`, în care este definită metoda abstractă `indeplinesteConditie(String parola)`, ce returnează `true`, dacă parola îndeplinește cerințele, și `false`, altfel.

Implementați următoarele metode:
1. Metoda `verificaParola(String parola, boolean afiseaza)`, care returnează `true`, dacă s-au îndeplinit toate condițiile din tabloul setat prin constructor, și `false`, altfel. Dacă variabila `afiseaza` e setată pe `true`, după fiecare verificare de condiție se va afișa pe ecran index-ul condiției din tablou, împreună cu status-ul (îndeplinit/neîndeplinit). Metoda se oprește la prima condiție neîndeplinită. 
2. Metoda `verificaParola(String parola)`, care apelează metoda de mai sus, cu parametrul `afiseaza` setat implicit pe `true`.

Pentru a testa funcționalitatea verificatorului, creați câte o clasă separată pentru fiecare condiție de mai jos:
1. Lungimea parolei să fie mai mare sau egală cu 8.
2. Parola să conțină atât litere mari, mici, cât și cifre.
3. Parola să conțină cel puțin unul din următoarele simboluri: `!`, `@`, `#`, `$`, `%`, `^`, `&`, `*`, `(`, `)`.

Creați o clasă separată, cu o metodă `main`, în care veți instanța un verificator cu cele trei condiții, și veți verifica corectitudinea metodelor implementate.
