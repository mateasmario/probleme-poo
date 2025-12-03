# Adaptor

Pentru început, se vor defini următoarele clase:  `Laptop`, `USB` și `CD`. Clasa `Laptop` este caracterizată de un tablou de date (șiruri de caractere), iar celelalte două clase sunt caracterizate de un șir de caractere ce reprezintă datele stocate pe dispozitiv. Se va crea o clasă comună pentru `StickUSB` și `CD`.

Dispozitivele vor conține o metodă comună `extrageDate()`, care va returna șirul de caractere stocat în starea dispozitivului pe care este apelată.

## Cerința 1
În clasa `Laptop`, implementați metoda `extrageDate(USB s)`, care va adăuga datele din stick-ul USB dat ca parametru în tabloul laptop-ului.

## Cerința 2
Fiind un laptop modern, acesta nu beneficiază și de un cititor de CD-uri, așa că va fi nevoie de un adaptor. Creați clasa `AdaptorCDLaUSB`, care va extinde clasa `USB` și va primi un `CD` prin constructor. Metoda `extrageDate()` din adaptor va delega apelul către CD.

## Cerința 3
Implementați și o metodă `main`, în care să verificați funcționalitatea adaptorului, dându-l ca parametru metodei `extrageDate(USB s)` din Laptop, în locul unui stick USB.
