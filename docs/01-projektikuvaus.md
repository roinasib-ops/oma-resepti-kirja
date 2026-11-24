\#Projektin nimi Oma reseptikirja. Reseptikirja omaan käyttöön.



\## Omaan käyttöön tarkoitettu puhelinsovellus. Auttaa pitämään kirjaa omista resepteistä. Auttaa myös valitsemaan mitä ruokaa haluaa tehdä. Syöttämällä ohjelmaan eri makuprofiileja osaa ohjelma tarjota sinulle sen mukaisia annoksia. Auttaa myös skaalaamaan ruoka aineiden määrän haluttuun annos määrään. Ohjelmaan voi myös syöttää eri ainesosia joita sinulta löytyy valmiina kaapista ja se tarjoaa reseptejä mitkä käyttävät näitä aineksia. Sovellus sisältää pääosin vain ainesosat eikä sisällä kirjallista selostusta reseptin eri vaiheista, selostuksen voi halutessaan kirjoittaa, mutta sillä reseptit ovat henkilökohtaiseen kättöön, en koe tarvitsevani selostuksia suurimmassa osin reseptejä.





\## Käyttäjäskenaariot

1: Syötän reseptin ohjelmaan, tämän jälkeen ohjelma myös kysyy minulta mikä on reseptin makuprofiili. resepti sekä sen makuprofiili tallentuvat tietokantaan.

2: Syötän ohjelmaan jonkin makuprofiilin, esim. täyteläinen. Tämän jälkeen ohjelma ehdottaa minulle ruokia, joille olen antanut makuprofiilin täyteläinen.

3: Syötän ohjelmaan yhden tai useamman ainesosan. Tämän jälkeen ohjelma tarjoaa minulle kaikki reseptit joissa käytetään näitä ainesosia.





\## Vaatimukset ja hyväksymiskriteerit:

Reseptin syöttäminen:Vaatimus: ohjelma tallentaa reseptin, sekä makuprofiilin.

&#x09;Hyväksymiskriteeri: Resepti löytyy tietokannasta.



Reseptin hakeminen: Vaatimus: ohjelma ehdottaa kaikkia reseptejä mitkä vastaavat syötettyä makuprofiilia tai ainesosia.

&#x09;Hyväksymiskriteeri: ohjelma ehdottaa kaikkia reseptejä mitkä vastaavat syötettyä makuprofiilia tai ainesosia



Reseptien tallentaminen ja jakaminen: Vaatimus: reseptit saa varmuuskopioitua omaan tiedostoon ja tuotua takaisin, mikäli reseptit poistuu. Toinen käyttäjä toisella laitteella voi tuoda toisen luoman varmuuskopion ja saada hänen reseptinsä

&#x09;Hyväksymiskriteeri: "Vie varmuuskopio" painike luo tiedoston haluamaan kohteeseen. "Tuo varmuuskopio" painike antaa valita resepti tiedoston, ja tuo sen resptit näkyville. Kaikki varmuuskopion reseptit tulevat toisella laitteelle näkyviin.



Muokkaaminen: Vaatimus:Tallennettuja reseptejä sekä ainesosia pystyy muokkaamaan sekä poistamaan.





\## Rajaus



Vähimmäiskokonaisuuteen sisältyy kaikki tässä lueteltavat asiat. Mikäli vaikuttaa siltä, että näiden toiminnalisuuksien toteuttamisen jälkeen jää runsaasti aikaa, tahtoisin tehdä sovelluksen siten, että se tukisi useita käyttäjiä. Käyttäjät voisivat mm. jakaa reseptejä toisillensa sekä seurata toisiansa.



\## Toteutuksen rakenne, oletukset ja riskit



Sovelluksen rakenne perustuu kolmeen osa alueeseen: käyttöliittymä, sovelluslogiikka ja tietokanta.



Sovellus voi aluksi tuntua hieman turhalta, sillä reseptejä ei ole vielä kertynyt paljon.



Skaalaus voi tiettyjen ainesosien kohdalla voi olla melko hölmöä, esim 1,5 kanamunaa.



Ainesosien nimet voivat vaihdella. Sovellukseen pitää luultavasti määrittää valmiiksi tiettyjä ainesosia, jotta sovellus tunnistaa ne samana. Sovelluksessa pitää luultavasti olla myös käyttöliitymässä mahdollisuus määrittää uusi ainesosa.





\## Merkittävät muutokset ja perustelut

Luovutaan erillisistä käyttäjistä. Ohjelma oli alunperinkin ajateltu omaan käyttöön. Vaikka käyttäjistä luovutaan on reseptien jako vielä mahdollista varmuuskopioiden avulla. Lisätään tämä vaatimuksiin ja hyväksymiskriteereihin.

