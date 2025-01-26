# PAP_sreca

Za pravilno pokretanje programa samo je potrebno preuzeti sve tri datoteke u "projekt" direktoriju. 
Potrebno je koristiti JupyterNotebook za pokretanje programa, i sve 3 datoteke moraju biti u istom folderu.

Jedina stvar vrijedna napomenuti je sekcija sa stvaranjem baze.
Ukoliko se više puta pokreću isti segmenti kôda, iste vrijednosti će se duplo spremati pa je u tom slučaju potrebno izbrisati tablice ako se u tablicu preko INSERT metode unesu podaci više puta. Ako se ne izbrišu, tablice će biti pune dupliciranih vrijednosti i u tom slučaju nije zagarantirano ispravno prikazivanje ostalih dijelova.

Dakle, ako ne dođe do nikakvih poteškoća i svaka čelija se pokrene točno jednom, nema potrebe za ikakvih dodatnim koracima. Ako se u bazi tablice zbog kojeg god razloga odluće puniti više puta putem INSERT metode, bit će potrebno odkomentirati segmente namijenjene za brisanje tablica.

Osim toga, prilikom pokretanja stranice, potrebno je u posebnom prozoru pristupiti adresi http://127.0.0.1:5005/
Tamo su dodatne upute kako filtrirati podatke prema određenim kriterijima. Ako piše, primjerice, "dostupna relacija: /indeks_sreca/country?country_name=Ime", potrebno je taj dio nadodati na adresu. Dakle http://127.0.0.1:5005/indeks_sreca/country?country_name=Ime, a umjesto "Ime" pišete ime države za koju želite da se ispišu podaci. Npr., http://127.0.0.1:5005/indeks_sreca/country?country_name=Zimbabwe. Također, postoji "Pretty-print" opcija u gornjem lijevom kutu nakon učitavanja relacije koja omogućava ljepši prikaz podataka.
