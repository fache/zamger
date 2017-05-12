Plan rada:
1. radna verzija - izrada dizajna
2. radna verzija - dizajn
3. radna verzija - implementacija funkcionalnosti
4. radna verzija - stranica sa svim zahtijevanim funkcionalnostima
Zavrsna verzija - ispravak nepravilnosti
+ Dokumentacija

---

1. radna verzija:
Hardkodirani podaci
Multipage web
Koristen Patternfly framework za CSS.
Lista fajlova:
bitni fajlovi se nalaze u direktorijima "podstranice", "komponente", "img", "css"

Upute:
Nakon ucitavanja stranice moguce je uociti stablo predmeta, pomocu kojeg je moguce otici na stranice za uredjivanje predmeta ili pregleda studenata (svi studenti i grupe za dati predmet).
Na pocetnoj stranici je takodjer prikazana tabela svih predmeta za koje je nastavnik odgovoran. Koloni "Naziv" je dodatna oznaka "[EDIT]" koja ima za cilj uputiti na izmjenu podataka o predmetu, koja se vrši klikom na link predmeta. 
Slicno, u koloni "Studenti" je dodata oznaka "+/-" koja podstice na izmjenu informacija o studentima.
Klikom na neki link iz kolone "Studenti" se otvara podstranica "grupesve.php".
Sljedece, klikom na studenta otvara se podstranica "student.php".
Sto se tice dijela vezanog za studente, planirana je podstranica "grupa.php", koja bi prikazivala odredjenu nastavnu grupu, na isti nacin kao sto ce biti prikazane informacije o svim studentima sa jednog predmeta.

Eventualni problemi:
kôd fajlova iz direktorija "komponente" je kopiran u index.php, sto znaci da se u slucaju promjene, mora izvrsiti promjena i u index.php

TODO:
*izbaciti raspored iz "index.php"
*zavrsiti dizajn "student.php", "grupesve.php", "grupa.php"
*dizajnirati podstranice za editovanje predmeta
*mobile view

---
