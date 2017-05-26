# 13vjezba
## Tehmeha 13. vježba
- na početku pomoću linka na stranici “tehmeha” prijavite se na “GitHub Classroom Assignment” i tako će te kreirati novi repozitorij
- pomoću GitHub Desktop-a napravite "clone" tog repozitorija na svoje računalo i u datoteci “mini-banka.cpp” napišite C++ program koji ima niže navedene funkcionalnosti 
- nakon svake implementirane funkcionalnosti napraviti “commit” (u opisu prepisati tekst pod odgovarajućim brojem) 
- na kraju potrebno je sinkronizirati lokalni i udaljeni repozitorij                                                                                                    
<br/><b>Mini banka</b> - implementirajte sljedeće funkcionalnosti:	
1. Korisniku se prikazuje glavni izbornik (unos nove osoba, ispiši sve podatke, pretraga prema računu, pretraga prema prezimenu i imenu, izmjena salda prema broju racuna, ispiši sortirano prema prezimenu i imenu, izlaz iz programa).
2. Korisnik unosi novu osobu u banku:
  <br/> - broj racuna - unsigned long long int, pr. 3252455656
  <br/> - prezime i ime - string
  <br/> - saldo - float, pr. 152.48
3. Korisniku se mogu ispisati svi podaci, nesortirani.
4. Korisnik može pretraživati prema broju racuna te mu se ispisuju podaci pronađene osobe ili se ispiše poruka da takva osoba nije pronađena.
5. Korisnik može pretraživati prema prezimenu i imenu osobe te mu se ispisuju podaci pronađenih osoba ili se ispiše poruka da takva osoba nije pronađena.
6. Program nakon što korisnik doda novu osobu sprema te podatke u datoteku “banka.txt”.
7. Kada korisnik pokrene program učitavaju se svi podaci osoba iz datoteke “banka.txt”.
8. Korisnik prema unesenom broju računa može mijenjati saldo osobe.
9. Izmjenjeni podaci moraju biti sinkronizirani s datotekom “banka.txt”.
10. Korisniku se mogu ispisati svi podaci uzlazno sortirani po prezimenu i imenu osobe.
