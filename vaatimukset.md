# TiKaWe Treeni Sovellus

## Kurssin lähtökohdat

Kurssilla toteutetaan web-sovellus käyttäen Python-kieltä ja Flask-kirjastoa. Sovelluksen tiedot tallennetaan SQLite-tietokantaan.

Löydät sovelluksen toteuttamisen tueksi kurssimateriaalin tältä sivustolta. Lisäksi sinun kannattaa tutustua esimerkkisovellukseen ja siihen liittyvään videosarjaan.

Kurssilla käytetään Git-versionhallintaa ja GitHub-palvelua. Jos et tunne näitä ennestään hyvin, sinun kannattaa tutustua myös Git-ohjeisiin.

## Aiheen valinta

Hyvä aihe sovellukselle on itseäsi kiinnostava aihe. Sovelluksen voi toteuttaa hyvin monenlaisista aiheista, kunhan perusvaatimukset täyttyvät.

Sovelluksen perusvaatimukset ovat:

- Käyttäjä pystyy luomaan tunnuksen ja kirjautumaan sisään sovellukseen.
- Käyttäjä pystyy lisäämään sovellukseen tietokohteita. Lisäksi käyttäjä pystyy muokkaamaan ja poistamaan lisäämiään tietokohteita.
- Käyttäjä näkee sovellukseen lisätyt tietokohteet. Käyttäjä näkee sekä itse lisäämänsä että muiden käyttäjien lisäämät tietokohteet.
- Käyttäjä pystyy etsimään tietokohteita hakusanalla tai muulla perusteella. Käyttäjä pystyy hakemaan sekä itse lisäämiään että muiden käyttäjien lisäämiä tietokohteita.
- Sovelluksessa on käyttäjäsivut, jotka näyttävät jokaisesta käyttäjästä tilastoja ja käyttäjän lisäämät tietokohteet.
- Käyttäjä pystyy valitsemaan tietokohteelle yhden tai useamman luokittelun. Mahdolliset luokat ovat tietokannassa.
- Sovelluksessa on pääasiallisen tietokohteen lisäksi toissijainen tietokohde, joka täydentää pääasiallista tietokohdetta. Käyttäjä pystyy lisäämään toissijaisia tietokohteita omiin ja muiden käyttäjien tietokohteisiin liittyen.

Esimerkkisovellus sekä tämän sivun lopussa olevat esimerkkiaiheet selventävät, mitä perusvaatimukset tarkoittavat käytännössä.

Sovelluksen aiheesta riippuu, mitä tietokohteet ovat käytännössä. Esimerkkisovelluksessa pääasiallinen tietokohde on tavaran myynti-ilmoitus ja toissijainen tietokohde on ilmoituksessa oleva huuto.

Voit valita sovelluksen aiheen vapaasti, kunhan se ei ole keskustelualue tai huutokauppa, koska nämä sovellukset on tehty kurssimateriaalissa.

Voit halutessasi toteuttaa perusvaatimusten lisäksi sovellukseen muitakin ominaisuuksia.

## Tekniset vaatimukset

Tekniset perusvaatimukset ovat:

- Sovellus on toteutettu samaan tapaan kuin kurssimateriaalin esimerkeissä.
- Sovellus on toteutettu Python-kielellä ja Flask-kirjastoa käyttäen.
- Sovellus käyttää SQLite-tietokantaa.
- Kehitystyössä on käytetty Git-versionhallintaa ja GitHub-palvelua.
- Sovelluksen käyttöliittymä muodostuu HTML-sivuista.
- Sovelluksessa ei ole käytetty JavaScript-koodia.
- Tietokantaa käytetään suoraan SQL-komennoilla (ei ORMin kautta).
- Sovellus ei käytä Flaskin lisäksi muita erikseen asennettavia Python-kirjastoja.
- Sovelluksen ulkoasu (HTML/CSS) on toteutettu itse ilman kirjastoja.

Vältä sovelluksessa Pythonin uusimpia ominaisuuksia, koska ne eivät välttämättä toimi ohjaajalla tai vertaisarvioinnin tekijällä. Hyvä tavoite on, että sovellus toimii Pythonin versiolla 3.10.

Huomaa, että Flask-kirjasto tuo mukanaan automaattisesti joitakin muita kirjastoja (kuten Werkzeug), joiden käyttäminen on sallittua.

## Sovelluksen kieli

Sovelluksen käyttöliittymän ja README.md-tiedoston kieli voi olla suomi, ruotsi tai englanti. Sovelluksen teknisen toteutuksen (koodi, tietokanta, commit-viestit) kielen tulee olla englanti.

## Aikataulu

| Päivä        | Tapahtuma                              |
| ------------ | -------------------------------------- |
| ti 12.5.2026 | Aloitusluento klo 16–18 (Exactum D122) |
| su 17.5.2026 | Välipalautus 1                         |
| su 31.5.2026 | Välipalautus 2                         |
| su 7.6.2026  | Vertaisarvioinnin deadline             |
| su 14.6.2026 | Välipalautus 3                         |
| su 21.6.2026 | Vertaisarvioinnin deadline             |
| su 28.6.2026 | Lopullinen palautus                    |

## Yleiset vaatimukset

- Välipalautuksen 1 deadlineen mennessä sinun tulee kirjautua Labtooliin ja ilmoittaa siellä linkki sovelluksesi GitHub-repositorioon.
- Välipalautuksen 2 deadlineen mennessä repositoriossasi tulee olla koodia, jossa on toteutettu joitakin sovelluksen ominaisuuksia.
- Vertaisarvioinnit ovat pakollisia, ja sinun tulee tehdä kumpikin arviointi deadlineen mennessä.
- Sovelluksen tulee olla valmis lopullisen palautuksen deadlineen mennessä.

## Välipalautus 1

- Luo GitHubiin julkinen repositorio harjoitustyötä varten. Nimeä repositoriosi kuvaavasti.
- Valitse projektille aihe ja kirjoita README.md-tiedostoon kuvaus, joka esittelee sovelluksen keskeiset toiminnot. Kirjoita kuvaus samassa muodossa kuin aloitussivun esimerkkiaiheissa ja esimerkkisovelluksessa.
- Kirjaudu Labtooliin ja ilmoita siellä projektisi GitHub-osoite.
- Saat seuraavan viikon alussa ohjaajalta palautteen aiheesta Labtooliin.
- Vinkkejä palautukseen:
  - Valitse repositorion nimi niin, että se kuvaa hyvin sovellustasi. Esimerkiksi jos teet reseptisovelluksen, voit valita esimerkiksi nimen reseptit.

## Välipalautus 2

- Tavoitteena on, että sovelluksessa on ainakin seuraavat toiminnot:
  - Käyttäjä pystyy luomaan tunnuksen ja kirjautumaan sisään sovellukseen.
  - Käyttäjä pystyy lisäämään, muokkaamaan ja poistamaan tietokohteita.
  - Käyttäjä näkee sovellukseen lisätyt tietokohteet.
  - Käyttäjä pystyy etsimään tietokohteita hakusanalla tai muulla perusteella.
- README.md-tiedoston tulee kuvata, millainen sovellus on ja miten sitä voi testata.
- Saat seuraavan viikon alussa ohjaajalta palautteen sovelluksesta Labtooliin.
- Vinkkejä palautukseen:
  - Muista antaa README.md-tiedostossa ohjeet siihen, miten sovelluksen testaaja saa käynnistettyä sovelluksen omalla koneellaan.
  - Tiedosto database.db ei kuulu repositorioon. Sovelluksen testaajan pitäisi pystyä luomaan tietokanta .sql-tiedostojen perusteella.

## Välipalautus 3

- Tavoitteena on, että sovelluksessa on ainakin seuraavat toiminnot:
  - Sovelluksessa on käyttäjäsivut, jotka näyttävät tilastoja ja käyttäjän lisäämät tietokohteet.
  - Käyttäjä pystyy valitsemaan tietokohteelle yhden tai useamman luokittelun. Mahdolliset luokat ovat tietokannassa.
  - Käyttäjä pystyy lähettämään toisen käyttäjän tietokohteeseen liittyen jotain lisätietoa, joka tulee näkyviin sovelluksessa.
- README.md-tiedoston tulee kuvata, millainen sovellus on ja miten sitä voi testata.
- Saat seuraavan viikon alussa ohjaajalta palautteen sovelluksesta Labtooliin.
- Vinkkejä palautukseen:
  - Muista estää sovelluksessasi CSRF-aukko kurssimateriaalin mukaisesti.
  - Pylint on hyödyllinen työkalu, jonka avulla voit saada ehdotuksia koodisi parantamiseksi.

## Lopullinen palautus

- Kurssi arvostellaan tämän sovelluksen version perusteella.
- README.md-tiedoston tulee kuvata, millainen sovellus on ja miten sitä voi testata.
- Ohjaaja arvostelee työn ja antaa palautetta Labtooliin. Ohjaaja arvostelee työn kuukauden kuluessa deadlinesta.
