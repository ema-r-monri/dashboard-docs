# Transactions

Klikom na Transactions tab u lijevom meniju, otvara se pregled transakcija trgovca.

Atributi transakcija koji su prikazani su:

* _id_ (jedinstveni redni broj transakcije),
* _type_ (tip transakcije),
* _date_ (datum trasnakcije),
* _masked_ pan (maskirni broj kartice),
* _amount_ (iznos transakcije u eurima) te
* _status_ (status transakcije).

<figure><img src="../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

Klikom na id trasnakcije, otvara se detaljni prikaz transkcije, kao što je prikazano na slici ispod.

U detaljnom prikazu transakcije prikazane su informacije o: payment details, payment method, additional info, custom attributes i mapa nastanka transakcije.

<figure><img src="../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

Transakcije se mogu pretraživati koristeći search polje iznad tabelarnog prikaza. Polja po kojima se pretraga može vršiti su:&#x20;

* _id_ (za rezultat pretrage vraća transakciju čiji je jedinstveni broj jednak unesenom),&#x20;
* _tid_ (za rezultat pretrage vraća sve transakcije čiji je terminal id - jedinstveni identifikator koji izdaje banka jednak unesenom),&#x20;
* _mid_ (za rezultat pretrage vraća sve transakcije čiji je merchant id - jedinstveni identifikator koji izdaje banka  jednak unesenom)
* _amount_ (za rezultat pretrage vraća sve transakcije čiji je iznos jednak unesenom),&#x20;
* _status_ (za rezultat pretrage vraća sve transakcije čiji je status  jednak unesenom  - approved, declined, reversed, pending, referral),&#x20;
* _cc\_brand_ (za rezultat pretrage vraća sve transakcije čiji je brend kreditne kartice koja je korištena za plaćanje transakcije jednaka unesenom- Amex, Diners, Maestro, Mastercard, Visa, Dina i Ina),
* _cc\_issuer_ (za rezultat pretrage vraća sve transakcije čiji je brend kreditne kartice koja je korištena za plaćanje transakcije jednaka unesenom sve transakcije koje su plaćene karticom kojoj je izdavač jednak unesenom - ucbm-ba, intesa-ba, rba-hr, zaba-hr, off-us, on-us..)&#x20;
* _currency_ (za rezultat pretrage vraća sve transakcije čija je valuta jednaka unesenoj),&#x20;
* _terminal_ (za rezultat pretrage vraća sve transakcije čiji je broj terminala jednak unesenom), &#x20;
* _merhcant_ (za rezultat pretrage vraća sve transakcije čiji je broj trgovca jednak unesenom),&#x20;
* _acquirer_ (za rezultat pretrage vraća sve transakcije čiji je broj banke jednak unesenom),&#x20;
* _amount\_to_ (za rezultat pretrage vraća sve transakcije sa iznosom manjim od unesenog),&#x20;
* _date\_from_ (za rezultat pretrage vraća sve transakcije sa datumom nastanka većim od unesenog),&#x20;
* _date\_to_ (za rezultat pretrage vraća sve transakcije sa datumom nastanka manjim od unesenog),&#x20;
* _installments_ (za rezultat pretrage vraća sve transakcije sa brojem rata odabranih za isplatu transakcije jednakim unesenom broju)_,_&#x20;
* _approval\_code_ (za rezultat pretrage vraća sve transakcije sa kodom odobrenja od banke jednak unesenom)_,_&#x20;
* _response\_code_ (za rezultat pretrage vraća sve transakcije sa kodom odobrenja od banke jednak unesenom)_,_&#x20;
* _merchant\_name_ (za rezultat pretrage vraća sve transakcije nastale kod trgovca sa idjem istim unesenom)_,_&#x20;
* _card\_data\_entry_ (za rezultat pretrage vraća sve transakcije koje su nastale na isti način unesenom - magstripe, concat-less, )_,_
* _transaction\_type_ (za rezultat pretrage vraća sve transakcije nastale kod trgovca sa idjem istim unesenom)_._
