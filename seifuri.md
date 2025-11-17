# Seifuri

Se va implementa funcționalitatea unui seif cu cifru, care poate fi deblocat cu ajutorul unei chei. Clasa `Seif` va fi caracterizată de un identificator (șir de caractere), un cifru (număr), și un identificator de cheie. Toate cele trei proprietăți pot fi date prin constructor. Clasa `Cheie` va fi și ea caracterizată de un identificator propriu.

Implementați următoarele metode în clasa `Seif`:
1. `deschide(int cifru)`, care verifică dacă cifrul dat ca parametru este același cu cel din proprietatea seifului. În cazul în care se introduce un cifru greșit de 3 ori, seiful se va bloca și nu va mai putea fi deschis cu cifrul. Metoda returnează `true`, dacă s-a reușit deschiderea, și `false`, altfel.
2. `deblocheaza(Cheie cheie)`, care verifică dacă identificatorul cheii din parametru este același cu identificatorul cheii din proprietatea seifului. Dacă se apelează metoda cu o cheie validă, seiful va fi deblocat și va putea fi deschis din nou cu cifrul corect. Metoda returnează `true`, dacă deblocarea s-a făcut cu succes. Altfel, aceasta returnează `false`.
3. `schimbaCheie(Cheie cheieVeche, Cheie cheieNoua)`, care verifică dacă identificatorul cheii vechi este același cu cel din proprietatea seifului. În cazul în care cheia veche este validă, se va înlocui identificatorul din proprietate cu cel al cheii noi.
4. `schimbaCifru(Cheie cheie, int cifru)`, care verifică validitatea cheii, iar în cazul în care se dă cheia corectă, setează noul cifru pe cel dat ca parametru.

Implementați o metodă `main` în care creați un seif, pe care să-l blocați prin inserarea a 3 cifruri greșite. Veți debloca, pe urmă, seiful, îi veți schimba cifrul și îl veți debloca cu succes.
