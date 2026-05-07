“Mini Booking” jeste Android aplikacija za rezervaciju smeštaja koja omogućava korisnicima pregled destinacija i zakazivanje termina u realnom vremenu. Cilj ove Android aplikacije jeste zakazivanje termina bez konflikata.
-Korisnička prijava: Početni ekran  za prijavu tj. login (validaciju username i password). Pre samog logina neophodno je registrovati se (drugi ekran za registraciju samog korisnika);
-Pregled kategorija tj. odabir same destinacije;
-Odabir smeštaja;
-Rezervacija termina smeštaja bez konflikata (preklapanje termina);
-Slanje, upisivanje i provera podataka u bazi podataka preko php Api-ja (Volley biblioteka zato što nam je baza na localhost-u).
	Tehnologije:
-Jezik: Java,
-Mrežna komunikacija: Volley biblioteka,
-Api: pomoću php fajla,
-Baza podataka: MySQL bazi podataka, kojom se upravlja putem phpMyAdmin interfejsa,
-Lokalni server: XAMPP (Apache server).
	Kako se pokreće aplikacija:
Za pokretanje aplikacije potrebno je kopirati ceo repozitorijum sa Github-a, takođe potrebno je prebaciti sve php fajlove u svoj lokalni server (npr. XAMPP/htdocs/Mini_Booking/), kao i importovati sql fajl u phpMyAdmin ili napraviti svoju bazu sa dve tabele (prva nam sluzi za logovanje i registraciju korisnika, a druga za rezervaciju termina). Zatim je potrebno otvoriti aplikaciju u AndroidStudio, pokrenuti preko emulatora (telefona MediumPhone), sačekati sinhronizaciju i instalaciju na emulatoru. Kada se sve to završi aplikacija se pojavljuje na telefonu i spremna je za korišćenje.
