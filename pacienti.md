 # Pacienți

Clasa `Spital` este caracterizată de metoda `adaugaPacient(Pacient p)`. Un pacient este definit prin numele său, gradul de severitate al problemei (un număr întreg între 1 și 10) și un număr de încercări anterioare de a apela la serviciile medicale. 

Un spital poate fi de două tipuri: `CameraGarda` și `UPU`. Camerele de gardă acceptă numai pacienți, ai căror grad de severitate este mai mic sau egal cu 5. UPU va accepta doar pacienți cu grad de severitate strict mai mare decât 5, sau pacienți care au un număr minim de 2 încercări la alte spitale (indiferent de gradul de severitate al problemei).

Implementați următoarele:
1. Metoda `adaugaPacient` care va returna `true`, în cazul în care adăugarea s-a făcut cu succes, și fals, în caz contrar.
2. Clasa `ManagerSpital`, care conține o colecție de spitale și oferă metoda `interneazaPacient(Pacient p)`, care încearcă să adauge un pacient în unul din spitalele disponibile. Metoda returnează `true` dacă adăugarea s-a făcut cu succes, și `false`, în caz contrar. Dacă un pacient nu e acceptat la un spital, numărul de încercări de spitalizare al acestuia se incrementează cu 1. 
