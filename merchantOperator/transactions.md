## Transakcije

Klikom na Transactions tab u lijevom meniju, otvara se pregled transakcija trgovca.

Atributi transakcija koji su prikazani su:

* id (jedinstveni redni broj transakcije),
* type (tip transakcije),
* date (datum trasnakcije),
* masked pan (maskirni broj kartice),
* amount (iznos transakcije u eurima) te
* status (status transakcije).

<figure><img src="../.gitbook/assets/C19F6B70-292B-4D06-9634-0E2DB2195048.jpeg" alt=""><figcaption><p>Slika: Prikaz transakcija</p></figcaption></figure>

Klikom na id trasnakcije, otvara se detaljni prikaz transkcije, kao što je prikazano na slici ispod.

U detaljnom prikazu transakcije prikazane su informacije o: payment details, payment method, additional info, custom attributes i mapa nastanka transakcije.

<div>

<figure><img src="../.gitbook/assets/5840A4A2-2BAC-45C1-BF20-04879585CFE6.jpeg" alt=""><figcaption></figcaption></figure>



<figure><img src="../.gitbook/assets/7E630FE3-E6E5-41E6-B241-3A42497DB747.jpeg" alt=""><figcaption></figcaption></figure>



<figure><img src="../.gitbook/assets/F78F4EFC-6F34-4D44-A078-3516725ADA99.jpeg" alt=""><figcaption></figcaption></figure>

</div>

Transakcije se mogu pretraživati koristeći search polje iznad tabelarnog prikaza. Polja po kojima se pretraga može vršiti su: id, tid, mid, amount, status, cc\_brand, cc\_issuer, currency, terminal, merhcant, acquirer, amount\_to, date\_from, date\_to, installments, approval\_code, response\_code, merchant\_name, card\_data\_entry, transaction\_type.

<figure><img src="../.gitbook/assets/572F9A64-1DB0-42F4-9E7B-AD626DB2D2B3.jpeg" alt=""><figcaption><p>Slika: Prikaz polja za pretragu transakcije</p></figcaption></figure>



Moguće je izvršiti i export/izvoz transakcija. U pitanju je CSV izvještaj detaljnih podataka odabranih transakcija za trgovca. Prije izrade exporta, možete odabrati filtere koje želite primijeniti kako biste odabrali željene transakcije u izvještaju.

Primjena filtera se naslanja na pretraživanje transakcija. Izaberete koji dataset želite, i shodno tome, primjenite pretraživanje transakcija po datim filterima. U ovom slučaju filteri su po atributima date\_from i date\_to, te služe da se filtriraju transakcije od 08:00 do 16:00, kao što je prikazano na slici niže.
