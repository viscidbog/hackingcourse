# Ensimmäinen tehtävä

## a) Tutustu kurssin sanastoon, joka on määritelty SFS-EN ISO/IEC 27000:2020:en standardissa, kappaleessa 3. Terms and Definitions. Selvitä seuraavien kappaleiden määritteet ja selitä omin sanoin mitä ne tarkoittavat  3.2, 3.31, 3.56, 3.58, 3.77

### 3.2
Attack - hyökkäys: yritys tuhota, varastaa tai muuten sotkea jotakin omaisuutta, tai saada luvaton pääsy johonkin omaisuuteen. Omaisuus tässä tarkoittaa mitä tahansa laitetta, ohjelmaa, tiedostoa, dataa, jne.

### 3.31
information security incident - tietoturvatapaus: yksi tai useampia ei-haluttuja tai yllättäviä tapahtumia, jotka voivat tarkoittaa mahdollista tietoturvamurtoa, ja joilla on huomattava riski uhata liiketoimintaa tai tietoturvaa.

### 3.56
Requirement - vaatimus: tarve tai ennakko-odotus joka on selkeästi määritelty dokumenteissa, yleisesti käytössä tai pakollinen.

### 3.58
Review - tilannekatsaus: tällä määritetään jonkin asian (esim. toimintatavan) toimivuus, sopivuus ja riittävyys, jotta vaaditut määränpäät saavutetaan.

### 3.77
Vulnerability - haavoittuvuus: Omaisuuden (kts. edellä) tai prosessin, käytännön, jne. heikkous jota jokin uhka voi käyttää hyväksi.

## b) Tutustu standardiin ISO 27034-1 - 5. Selvitä mistä standardikokonaisuudesta on kyse.

ISO 27034-1 - 5:
Standardikokonaisuudessa on kyse tarkoista ohjeista, kuinka yritys voi tehdä itselleen toimivan tietoturvaohjelman. 

## c) Kuuntele Podcast: Laatulöpinät 30: Tietoturvallisuus ohjelmistokehityksessä. Mieti mitä podcastin väittämistä?

### 1. Mikään ohjelmisto ei ole täysin tietoturvallinen.

- Olen samaa mieltä, sillä kaikkia ohjelmistoja käyttää ihminen ja ihmiset ovat erehtyväisiä sekä manipuloitavissa.

### 2. Hallinnollinen tietoturva on teknisen tietoturvan onnistumisen edellytys.

- Samaa mieltä, samasta syystä kuin edellisessä kohdassa.

### 3. Automaatiotestaus on ohjelmiston tietoturvan kannalta erittäin tärkeää.

- Osittain samaa mieltä, sillä automaatiotestaus on vain yksi testauksen osa-alue, eikä se yksinään riitä.

### 4. Ohjelmistoa suunniteltaessa voidaan tehdä paljonkin auttamaan käyttäjää toimimaan tietoturvallisesti. Usein nämä toimenpiteet kuitenkin vaikuttavat negatiivisesti käytettävyyteen.

- Podcastissa annettu esimerkki, jossa käyttäjä pakotetaan rekisteröityessä antamaan tietoturvallien salasana, on osuva esimerkki siitä, miten käytettävyys saattaa kärsiä. En itse tosin allekirjoita tätä täysin, sillä oma kokemukseni on, että suurin osa tietoturvasta ohjelmistossa on usein käyttäjän näkymättömissä.

### 5. Ohjelmiston tietoturvallisuuden suunnitteluun vaikuttaa paljolti se, kuinka arkaluonteisia tietoja ohjelmistolla on tarkoitus käsitellä.

- En sanoisi että välttämättä paljoa, mutta kuitenkin jonkin verran. Kuten podcastissa puhuttiin, jos tiedot ovat erityisesti arkaluonteisia, tulee jo lainsäädännön vuoksi tähän kiinnittää erityistä huomiota, mutta yleisellä tasolla tietoturvallisuus on todella tärkeää joka tapauksessa.

### 6. Ohjelmistokehittäjät näkevät omat ohjelmistonsa aina merkittävästi riskialttiimpina, kuin muiden tekemät ohjelmistot.

- Oma kokemukseni on päinvastainen, sillä olen yleensä ollut kehittämässä vain jotain osa-aluetta enkä koko ohjelmistoa ja näin ollen tietoturvan tärkeys jäi hieman hämäräksi.

## d) Tee itsellesi riskienhallintasuunnitelma. Suunnitelmassa pitää olla kuvaus ympäristöstä. Miten varmistat, että ympäristöön ei päästä tunkeutumaan ulkopuolisten toimesta. Jos tutkit ympäristössä epäilyttäviä tiedostoja niin miten varmistat sen, että mahdolliset haittaohjelmat eivät pääse leviämään ympäristön ylkopuolelle.

Omalla tietokoneella toimiva virtuaalikone, jolla ei ole pääsyä internetiin. 

Virtuaalikoneen asetukset on laitettu siten, että sillä ei ole pääsyä isäntäkoneeseen millään tavalla.

## Lähteet

https://www.arter.fi/podcast/laatulopinat-podcast-tietoturvallisuus-ohjelmistokehityksessa-tarkastele-kokonaisuutta-ja-hyodynna-viitekehykset/
