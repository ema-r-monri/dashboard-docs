UPUTE ZA DASHBOARD v2.0.1. ZA KORISNIKA TIPA MERCHANT OPERATOR 

Korisniku tipa merchant operator nakon prijave na sistem otvara se sljedeća stranica.

				Slika 1: Izgled sučelja nakon prijave

Ova stranica predstavlja pregled stanja poslovanja merchanta.

Prikazuje:
* Net sales (sumu transakcija),
* Customers (broj korisnika) te
* Transactions (broj transakcija) 
za odabrani period.

Period se bira od strane korisnika, u gornjem desnom uglu.
Ponuđene opcije su:
* hourly (svakog sata zadnja 24 sata),
* daily (svakog dana zadnjih 31 dana) te
* monthly (svakog mjeseca zadnjih 12 mjeseci).


//dodatno objasniti transactions i recent links

Nakon klika na NetSales otvara se stranica sa sljedećim izgledom. Graf na slici predstavlja


Klikom na Transactions tab u lijevom meniju, otvara se pregled transakcija trgovca.

Slika: Prikaz transakcija

Atributi transakcija koji su prikazani su:
* id (jedinstveni redni broj transakcije),
* type (tip transakcije),
* date (datum trasnakcije),
* masked pan (maskirni broj kartice),
* amount (iznos transakcije u eurima) te
* status (status transakcije).

Transakcije se mogu pretraživati koristeći search polje iznad tabelarnog prikaza. Polja po kojima se pretraga može
vršiti su:

Klikom na id trasnakcije, otvara se detaljni prikaz transkcije, kao što je prikazano na slici ispod.

Slika: detaljni prikaz odabrane transakcije

Slika: detaljni prikaz odabrane transakcije

U detaljnom prikazu transakcije prikazane su informacije o: payment details, payment method, additional info, custom
attributes i mapa nastanka transakcije.

Moguće je izvršiti i export/izvoz transakcija. U pitanju je CSV izvještaj detaljnih podataka odabranih transakcija za
trgovca.
Prije izrade exporta, možete odabrati filtere koje želite primijeniti kako biste odabrali željene transakcije u
izvještaju.

Nakon primjene filtera, klikom na dugme export u desnom uglu izvještaj se generiše.

Na slici ispod, prikazana je primjena tri filtera - u našem izvještaju želimo transakcije koje imaju status approved, te
pripadaju vremenskom periodu od 16.11.2023 08:00 do 16.11.2023. 12:00.

//dodati samo sliku filtera

Klikom na export dugme

//dodati sliku export dugmeta

dobijemo pop-up prozorčić gdje se unosi ime izvještaja, kao što je prikazano na slici niže.

Klikom na dugme submit, izvještaj je poslan na generiranje, a na prozoru se prikazuje poruka sa obavještenjem da će
poruka o gotovom izvještaju biti dostavljena na e-mail, kao što je prikazano na slici ispod.

Klikom na Reports tab na meniju desno, otvara se prikaz svih izvještaja za trgovca, kao na slici niže.

Report/Izvještaj ima prikaz sljedećih kolona: Id, Created at, Name, From, To, File size, Status i Downloaded.

Na slici niže vidimo prikaz Izvještaja nakon što je generiran. Veličina datoteke je sada vidljiva, status je pomjeren iz
generating u generated - dakle izvještaj je uspješno generiran.

Također je opcija download sada jasno prikazana, te se izvještaj preuzeti nakon što je uspješn generiran. Izvještaj će
uvijek biti dostupan da ponovno skidanje.

//klik na id reporta sta se dobije?
//prikaz nekog reporta u csv??


